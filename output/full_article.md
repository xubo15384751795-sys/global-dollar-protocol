# Global Dollar Protocol & Financial Function Translation

V1 正文。GDP 份额、SWIFT、1998 已核。USD/HKD 日序列已接（Yahoo 市场报价）。HIBOR / CNH–CNY / Connect 官方历史本轮未下载。

写作链：Premises → Structure → Risk → Translation → Market

---


# 00 Introduction

V0 原稿冻结在 `archive/original/original.md`。本章是按类型判定之后的正文，不是把旧判断改成“可能”。

服从 `foundations/`。定义以 `definitions.md` 为准。

---

## 1. 传统问题问错了什么

常见问法有两种：美元会不会崩，人民币会不会取代美元。

这两种问法把身份、功能和国际秩序绑成一块。它们预设：美元是整块的；功能要么全在、要么全无；若美元受限，就会有另一种货币顶上。

V0 原稿的标题走的是第三条路：“不是人民币崛起，而是美元失效”。后半句里有一个值得保留的直觉，也有一个不能进结论的跳跃。直觉是：美元的问题不必表现为信用崩塌。跳跃是：把功能受压写成体系失效，再写成接管方案。

本文只保留前半。不问美元会不会崩，也不问谁来取代它。问的是：

> 美元和美元资产分别承担哪些功能？这些功能在哪一层、哪条协议上可能被约束？约束之后，市场能否通过另一条协议把功能接续回来？这种变化怎样进入价格？

香港是观察窗口，不是已经证实的“全球唯一接口”。

---

## 2. 两个起点

```text
Asset Identity ≠ Asset Function
USD = US Fiscal + Federal Reserve + Global Dollar Protocol
```

第一式：一项 claim 在法律上是什么，不等于它此刻能干什么。美债不是美元，但可以通过 repo 获得美元融资功能。港币是香港法币，信用锚在美元。CNH 是离岸人民币，主权信用来自中国，市场在香港。

第二式：普通主权货币大致是财政 + 央行 + 本国市场。美元多一层已经全球化的协议：银行美元、offshore dollars、correspondent banking、FX swap、repo、Treasury collateral、贸易计价、清算、套保、储备管理、管辖与合规。

财政层、货币层和协议层可以不同步。后文的美元风险首先是某项功能受损，或层与层之间错配。

---

## 3. 为什么从香港看

制度上，香港同时容纳：

- 中国主权下的特别行政区法律身份
- 普通法合约与独立的金融监管安排
- HKD 联系汇率 / 货币局，锚在美元
- CNH 离岸人民币市场
- 美元融资、清算与国际银行业务
- 与中国在岸市场的 Connect 等准入安排

这是观察 identity / function 分离的合适案例。原稿把它写成“全球唯一”，本文降为待检验命题：在哪些功能上，香港目前仍是主要通道；在哪些功能上，新加坡、伦敦或在岸直连已经可以替代。

原稿还有一句价值判断：香港 GDP 占全国比重下降，因此香港变成“信用负资产”。前半是可核验的相对体量变化。后半把价值、成本、信用和因果捆在一起，没有中间机制。本文把它拆成竞争假说，放在第 1 章，不作为引言结论。

---

## 4. 文章路径

```text
Premises → Structure → Risk → Translation → Market
```

| 章 | 问题 |
|---|---|
| 01 | 香港是怎样一种金融结构？ |
| 02 | 美元究竟是什么？ |
| 03 | 什么才叫美元风险？ |
| 04 | 功能受限后，能否被另一条协议接续？ |
| 05 | 这些结构怎样进入价格？ |
| 06 | 反事实、压力情景与证伪 |
| 07 | 能说什么，不能说什么 |

不讨论：人民币是否取代美元、长期去美元化、多锚世界秩序设计、全球货币制度改革方案。原稿后半的 IMF 2.0、全面接管、联合特区设计，不进入正文结论；需要时只作为第 6 章的情景或反事实。

---

### Research status

```text
Current conclusion:
问题已锁定为功能分层、约束、转译与价格，而不是崩溃或替代。

Evidence:
美元三层和 identity ≠ function 是概念起点；香港多层市场并存是制度事实。

Counterevidence:
若美元功能在经验上几乎从不分层，或香港不能同时观察到 HKD / CNH / USD / China access，选题入口减弱。

Market implication:
引言不给出交易方向。

Watch:
后文是否把香港唯一性重新写成前提；是否把功能受压写成美元体系瓦解。

Falsifier:
正文重新收成“美元会不会崩”或“人民币会不会取代美元”。

Last updated: 2026-09-05
```


# 01 Hong Kong Structure

## 问题

香港究竟是一种怎样的金融结构？

不评价它重要不重要，也不先问它是不是中介层。先把层拆开。

---

## 1. 可确认的制度事实

香港是中华人民共和国的特别行政区。合约和金融纠纷大量使用普通法。它有独立关税区地位，以及相对独立的货币、支付和监管安排。

港元实行联系汇率。货币基础的扩张和收缩，制度上与美元储备和兑换保证相连。因此：

```text
HKD identity: 香港法定货币
HKD anchor: USD
HKD liquidity: 货币局、Aggregate Balance、贴现窗、银行体系
```

这三件事不必重合。港币不是“强主权信用货币”，也不因此没有金融功能。它是制度壳：身份在香港，锚在美元。

CNH 是另一种组合：身份是人民币，场所主要在香港离岸市场，与在岸 CNY 的利率、清算和可兑换性分开。CNH ≠ CNY，CNH ≠ HKD。

香港还同时存在美元存贷、清算、国际银行业务，以及 Stock Connect、Bond Connect 等与中国在岸市场的准入安排。

以上是结构描述。它们说明香港可以把主权归属、货币锚、离岸人民币和美元资金放在同一空间里。它们还不证明香港“全球唯一”，也不证明这些功能只能在这里完成。

---

## 2. 相对经济体量下降是观察，不是接口判决

World Bank 现价美元 GDP（`NY.GDP.MKTP.CD`）：1997 年香港约为中国内地的 18.3%；2021 年为 2.0%。这是市场汇率口径，对汇率敏感，不是 PPP，也不是金融功能度量。

观察只到这一句：

> 香港相对于中国整体经济的 GDP 权重显著下降。

原稿由此写成：“香港已从价值资产转化为需额外负担的信用负资产。” 这一句同时包含价值定义、成本收益、信用判断和因果，中间没有机制。本文不采用。

拆成竞争假说：

```text
Observation:
香港相对 GDP 权重下降。

Question:
经济体量下降是否意味着跨境金融接口价值同步下降？

H1: 体量下降 ⇒ 边际金融功能同步弱化。
H2: 接口价值主要来自制度、流动性、清算和市场准入，因此与 GDP 权重并不同比。

Test:
跨境融资、CNH 流动性、Connect 使用、清算量、市场深度。
```

若 H2 成立，GDP 份额下降不能单独否定香港的接口功能。若 H1 成立，接口指标应与份额同比变差。这是经验问题。

---

## 3. 接口命题：有协议，不等于必然被用

原稿的强命题是：全球可以绕开中国，但不能绕开香港；香港是唯一能同时被中国主权体系和美元体系接入的接口。

制度事实支持较弱的命题：香港确实同时接到普通法合约、美元资金链和中国市场准入。比较组不支持把它写成公理。新加坡处理大量美元和财富管理，但不嵌入中国资本账户。上海在岸，监管和可兑换性不同。伦敦是全球美元和合约中心，对中国在岸准入不是同一套。澳门体量小。

因此：

```text
H_interface:
在中国资本账户未完全开放、且国际合约仍依赖普通法/离岸美元安排时，
香港对若干跨境功能仍具有成本或准入上的优势。
```

这不是“资本无法拒绝”。若该结构能降低准入摩擦并保留退出流动性，相对直接进入在岸的成本优势可以提高。是否提高，看流量、融资成本和市场深度。

香港是不是中介层，留到第 4 章用成本条件检验。本章只把结构画清楚。

---

## 4. 必须落到市场

没有这些观察量，结构描述停在制度图：

```text
HKD / USD/HKD / Convertibility Undertaking
HIBOR / Aggregate Balance / HKMA operations

CNH / USD/CNH / CNH HIBOR / CNH–CNY spread
CNH deposits / offshore issuance

Connect northbound / southbound
HK equity / China offshore credit
```

已接到序列的只有 USD/HKD（Yahoo 日收，2014-09 至 2026-09，n=3122）。约 96% 的交易日停在 7.75–7.85 内；贴强方（<7.75）107 日，贴弱方（>7.85）11 日。最近在 7.84 附近，靠弱方。HIBOR、Aggregate Balance、CNH–CNY、Connect 本轮没有拉到官方历史文件，不填假数。细节：`analysis/q5_market/usdhkd_cu_band.md`。

Dollar → HK 链的第一观察是 HKD 流动性和 HIBOR，不是港股故事。China → HK 链的第一观察是 CNH–CNY 和 Connect 流量。

---

### Research status

```text
Current conclusion:
香港是多层身份并存的结构：HKD 锚美元，CNH 源自中国主权信用，USD funding 与中国市场接口同场。相对 GDP 下降是观察。接口价值是否同步下降，未决。香港是否中介层，未决。

Evidence:
货币局、普通法安排、CNH、Connect、美元银行业务在制度上同时存在。World Bank：HK/CN GDP 份额 1997 年 18.3%，2021 年 2.0%。

Counterevidence:
若 HKD 已与美元锚脱钩运行，或 CNH / Connect 主场已不在香港，本章结构图失效。若接口指标随 GDP 份额同比塌缩，H2 被削弱。

Market implication:
先盯 HIBOR、Aggregate Balance、CNH-CNY、USD/CNH、Connect flows。

Watch:
USD/HKD 贴在 CU 哪一侧；CNH 流动性是否仍集中在香港；Connect 是否仍是主要准入通道。

Falsifier:
friction ↑ 同时 HK flows、CNH liquidity、Connect usage ↓，资金改走其他通道。

Last updated: 2026-09-05 (USD/HKD daily panel added)
```


# 02 Global Dollar Structure

## 问题

美元究竟是什么？

把 USD 拆成三层。不在这里预测美元指数，也不把支付份额当成三层的充分统计量。

---

## 1. 三层

```text
US Fiscal → Treasury → UST

Federal Reserve → base money / liquidity / policy

Global Protocol → banks, repo, FX swaps, clearing,
                  collateral, funding, trade, reserves
```

```text
USD = Fiscal + Monetary + Global Protocol
```

UST 是财政层负债，不是美元本身。它成为美元功能，要经过协议：

```text
Treasury --[repo / collateral]--> Dollar Function
```

持有美债不等于持有现金美元。用 UST 做抵押融资，才获得 funding function。

因此 Treasury supply 首先是财政事件。它能否变成美元流动性，取决于 dealer、repo、抵押品资格和清算。Fed 可以提供准备金和设施，不必与财政供给同步。全球借款人通过 FX swap 和离岸银行美元使用美元功能，更不必与美国国内政策目标同步。

---

## 2. 协议层不是海外现钞

Global Protocol 至少包括：银行美元与 offshore dollars、correspondent banking、FX swap、repo 与 Treasury collateral、贸易计价、清算、套保、储备管理、管辖与合规。

这一层使美元可以在美国财政和美联储并不直接操作的地方继续作为功能货币。它也使美元风险可以出现在美国国内指标看起来并不极端的时候。

原稿把这一层写成“美元节奏权 / 清算权 / 法理权”。作为分类提示可以使用。作为“三根支柱正在被接管”的结论，证据不够，也不在本文范围。本文只需要确立：三层分开是合法的；合成一个“美元涨跌”不够。

---

## 3. 层可以不同步

财政扩张、Fed 收紧、全球美元借款需求上升，可以同时发生。受损的不是美元身份，而是某一层的功能，或层间匹配。

后文把这种错配写成层间互动风险。本章只准备好分类：问题属于财政、货币，还是协议。

港币是一个对照。HKD 的身份不在美国，锚在美元，流动性由香港货币局形成。这再次说明 issuer、anchor、liquidity currency 可以分开。

---

### Research status

```text
Current conclusion:
美元必须按财政、货币、全球协议三层来写。Treasury 可以转译出美元功能，但它不是美元。

Evidence:
UST repo、FX swap、离岸银行美元、correspondent banking 在制度上把非现金资产和境外主体接到美元功能上。HKD 货币局把同一逻辑写进另一法域。

Counterevidence:
若全球美元使用几乎完全由 Fed 资产负债表解释，协议层没有独立分析价值。

Market implication:
看 UST 供给时同时看 dealer / repo；看 Fed 时同时看 FX basis 和离岸 funding。DXY 不是三层的充分统计量。

Watch:
issuance vs dealer capacity；SOFR / repo vs 政策利率；basis vs 美国国内流动性。

Falsifier:
三层指标长期同向同幅，层间错配无法被观察量分开。

Last updated: 2026-09-05
```


# 03 Dollar Functional Risk

## 问题

什么才叫美元风险？

不要：

```text
Dollar Risk = Dollar Collapse
Dollar Risk = Dollar Shortage
```

而是：

> Dollar Functional Risk：美元或美元相关资产在特定状态下，无法继续完成它原本承担的某项金融功能。

V0 原稿里最值得救的一句是：

> 美元信用不会崩塌，但美元无法释放信用才是更危险的场景。

这句话不能靠加“可能”保存。它的分析核是：信用质量与功能可达性可以分开。本文把它收成正式定义。原稿后半把它接去“节奏饥渴”“补液器”“接管美元”，那些不进本章。

---

## 1. 拆开功能

```text
Fiscal / safe-asset
Monetary / liquidity
Funding access
Collateral eligibility
Settlement access
Jurisdiction / access
Balance-sheet / intermediation
Layer mismatch
```

身份可以还在。DXY 可以不崩。受损的是：期限匹配的融资、可接受抵押、清算时点、账户与合规准入，或中介资产负债表接不住。

美元荒是 funding access 全面受损、且替代转译也接不上时的极端情形。它是输出，不是全文根因。

---

## 2. 层间错配

最值得追的是互动风险：单层看起来稳定，连接出问题。

例：Treasury supply 上升，dealer capacity 跟不上，repo 和融资条件变紧。财政身份还在，协议功能受损。

例：Fed 政策对美国合适，全球美元借款人承压。这是美元作为全球协议货币的特有风险，不是普通主权货币的国内过热或过冷。

例：抵押品仍合格，但结算或管辖准入受阻。资金和证券都在，功能走不通。

---

## 3. 1998 港元压力是案例，不是定律

制度事实：联系汇率把 HKD 钉在美元。开放的小经济体、固定汇率、有限储备，面对投机压力时，货币局必须用利率、流动性和储备兑换来守锚。

1998 年 8 月，财政司司长指示金管局动用外汇基金，在股票和期货市场操作，针对当局所说的港元–恒指期货“double play”：抛售港元抽紧同业、推高利率，从股市空头获利。操作约 10 个交易日，8 月 28 日结束；当日成交约 790 亿港元。联系汇率没有脱钩。9 月推出七项技术措施，强化兑换保证和贴现窗。公开行动主体是金管局和外汇基金。细节见 `analysis/q3_functional_risk/hk_1998_double_play.md`。

原稿把这一段写成：没有中国出手香港必然溃败；有中国出手人民币信用就此出海。两跳都过长。大陆银行或政治信号如何进入盘口，尚未被这些官方文本证明。守住联系汇率，也不等于启动人民币国际化。

条件判断可以保留：

```text
若货币局 + 开放账户 + 利率自动抽紧
→ 汇市压力可以传到股市
→ 空头可同时做货币和指数
1998 不是因为“市场永远赢”，也不是因为“主权永远赢”。
```

---

## 4. 支付份额不是功能充分统计量

SWIFT 2025 年 12 月 Tracker：含欧元区内支付，USD 约 50.5%，CNY 约 2.73%；剔除欧元区内支付，USD 约 58.6%，CNY 约 2.13%。V0 的人民币 4.33% 与近年 Tracker 不符，不采用。BIS 2025 年 FX 调查里美元出现在约 89% 的交易一侧，那是外汇成交，不要和支付份额混用。

支付份额高，不证明融资、抵押和清算可达性没有局部分化。DXY 和 SWIFT 份额都不是三层美元的充分统计量。

---

### Research status

```text
Current conclusion:
美元风险应定义为功能受损。优先对象是层间错配。信用稳定与功能可达性下降可以并存。

Evidence:
定义与三层结构一致。1998 年 HKMA 官方记录了 double play、外汇基金入市和联系汇率未脱钩。SWIFT 显示美元仍占支付一半左右，人民币约 2–3%。

Counterevidence:
若所有美元压力都能被单一短缺或崩溃指标概括，分类过细。

Market implication:
先判断受损的是 funding、collateral、settlement 还是 access，再决定看 repo、basis、UST depth 还是离岸利差。

Watch:
dealer vs supply；FX basis；SRF / FIMA / swap line；haircut 与资格变化。

Falsifier:
出现“美元风险”时，功能指标均无压力，只有叙事或 DXY。

Last updated: 2026-09-05 (SWIFT / HKMA 1998 verified)
```


# 04 Financial Function Translation

## 问题

当某项功能受到限制以后，能不能被另一条协议接续？

```text
Asset_A --[Protocol]--> Function_B
```

不设计新系统。问现实市场已经有哪些 translation-like mechanisms，以及中介是否值得存在。

---

## 1. 什么算转译

一项金融 claim 通过制度或市场协议，获得它原本并不直接具备的金融功能。

算：UST → repo → USD liquidity。  
不算：普通 USD → RMB 换汇。

换汇只替换余额身份。转译改变这项 claim 能做什么：证券变成融资，离岸余额变成在岸入口，本地货币余额经货币局变成美元可兑换性。

原稿用“信用转译器”“制度 NAT 网关”“信用路由器”指同一类现象。比喻可以留在解释里。论证必须落到协议、成本、haircut、准入和法律约束。任何核心比喻若无法映射到机制或 observable，不得承担关键论证。

---

## 2. 已有机制

```text
Repo
Collateral transformation
FX swap / cross-currency swap
Cross-currency repo
Clearing arrangement
Liquidity facility
Connect
Offshore CNH market
Correspondent network
```

香港出现在其中若干条上，是经验填写，不是默认值。

对每条机制要能回答：输入哪种 identity，输出哪种 function，cost / haircut / liquidity / access / legal constraints，失败时功能停在哪一层。

港币是转译的清晰例子：HKD 身份不是美元，货币局协议把它接到美元可兑换和美元锚。CNH 是另一例：人民币身份，离岸协议形成另一套定价、融资和套保功能，不等于在岸 CNY。Connect 是市场准入转译，不是换汇。

---

## 3. 中介不是前提

不预设市场必然产生中介层，也不预设香港必然是中介。

```text
仅当 C_direct > C_intermediation + R_intermediation
中介才有经济理由。
```

三种结果都开着：

1. 香港持续完成某些替代成本更高的转译  
2. 香港能做，其他通道也能做，只是成本不同  
3. 摩擦上升后功能改道，香港被绕开

第 3 种是第 6 章的证伪方向。

原稿“全球资本无法拒绝的诱惑”“只要一个市场陷落，剩下的就会向中国靠拢”“只要中国接得住一个锚，全球资本就不会溃散”，都把 A 写成必然的 C。补上中间节点之后，它们最多是条件假说：

```text
若直接美元融资或清算摩擦上升
且香港/CNH 等路径仍有流动性、法律可达性和退出能力
则部分资金会重新评估这些中介路径。
资金是否迁移，用 flow、funding cost、市场深度验证。
```

谁吸收变化：在港银行、dealer、清算行、Connect 中介的资产负债表。答不出承担者，传导链还没走完。

---

### Research status

```text
Current conclusion:
转译是既有协议给 claim 接上新功能。香港是否中介层，不能从定义推出。

Evidence:
UST repo、FX swap、货币局、CNH、Connect 都是已存在的 translation-like mechanisms。

Counterevidence:
若这些机制在数据上与普通换汇或普通跨境投资无法区分，转译概念多余。

Market implication:
看转译是否还在工作：repo haircut、FX basis、Connect 流量、CNH 流动性。有接口 ≠ 接口被用。

Watch:
C_direct 与中介成本/风险的相对变化；其他清算和离岸中心是否吸收流量。

Falsifier:
功能受限后，市场直接完成原功能，香港协议既无溢价也无使用。

Last updated: 2026-09-05
```


# 05 Market Pricing and Rerouting

## 问题

前面的结构怎样进入市场？

```text
Structure → Trigger → Transmission → First Observable → Second Observable → Asset
```

不输出“看多/看空人民币”。市场化首先是：哪个价格先动，哪个后动。“当前没有可交易表达”是合法结论。

---

## 1. 三条主链

### Treasury → Protocol

```text
Treasury issuance
↓
dealer absorption
↓
repo / collateral
↓
USD funding
↓
cross-currency basis
↓
FX / global asset prices
```

第一观察：repo spreads、UST depth、dealer inventories。若 repo 没动而风险资产先动，优先怀疑认错了这条链。

### Dollar → HK

```text
USD funding condition
↓
HKD liquidity / USD/HKD
↓
HIBOR / Aggregate Balance
↓
HK financing
↓
property / equities / credit
```

HKD 锚住美元，不意味着 HKD 流动性自动复制 Fed。货币局把美元条件转成港元市场条件，但 Aggregate Balance 和 HIBOR 有自己的时滞。

USD/HKD 日收（Yahoo，2014–2026）几乎都在 7.75–7.85 内。第一观察因此不是“脱锚与否”，而是贴强方还是弱方。HIBOR 和 Aggregate Balance 仍缺官方序列，这条链后半段还没接上。

### China → HK

```text
China policy / liquidity
↓
CNY
↓
CNH
↓
HK offshore market
↓
Connect / China assets
```

在岸政策先碰到 CNY，再通过可兑换性、预期和离岸头寸变成 CNH。香港是离岸腿，不是中国货币政策本身。

---

## 2. Market map

| Structure | First observable | Secondary | Asset |
|---|---|---|---|
| USD funding stress | basis / repo | CNH / HKD funding | FX / rates |
| Treasury stress | repo / depth | USD funding | UST / FX |
| HK interface strengthening | flows / CNH liquidity | spreads | HK / China assets |
| translation failure | funding spread | flows reroute | cross-asset |

Rerouting 出现时，还要看流量改道：Connect 相对其他准入、CNH 相对其他离岸场所、HKD funding 相对美元直融。

---

## 3. 价格没按模型动时

不要立刻宣布模型失败。按顺序问：Trigger 是否发生；第一层 transmission 是否发生；有没有对冲机制；是否已经 price in；observable 是否选错；时间尺度是否不匹配。最后才是模型被证伪。

不要用单日价格否定数年制度变化，也不要用长期结构判断解释单日波动。

---

### Research status

```text
Current conclusion:
结构必须落到 Structure → Trigger → Observable → Price。当前三条主链是 Treasury-Protocol、Dollar-HK、China-HK。

Evidence:
repo / basis / HIBOR / CNH-CNY / Connect flows 都是可独立观察的中间量。

Counterevidence:
若最终资产价格变动时这些中间量系统性不反应，传导图需要重画。

Market implication:
先读第一观察，再读资产价格。本章不给出人民币或港股方向。

Watch:
core indicators 是否按链的顺序动；压力期流量是否改道。

Falsifier:
结构冲击之后，指定的 first observable 长期沉默，只有最终价格故事。

Last updated: 2026-09-05 (USD/HKD CU-band panel)
```


# 06 Boundaries and Counterfactuals

反事实用来识别机制，不是写未来小说。Scenario 是改变一个现实可能变化的参数。极端情景可以有，不作为基准。原稿里的全球系统崩溃、IMF 2.0、全面接管，只作 tail 或 archive。

---

## 1. Counterfactual

每次只放松一条工作假设。

**如果香港没有 CNH？**  
少了一条人民币离岸定价和融资腿。香港仍可能有 HKD 和美元资金。可以识别 CNH 对接口价值的贡献是不是独立的。

**如果 HKD 不锚美元？**  
货币局转译断开。Dollar → HK 链要重画。这能识别美元锚对 HIBOR、融资和资产价格的作用。

**如果中国资本账户完全开放？**  
Connect 和离岸中介的成本优势可能下降。这是对“香港接口随摩擦而存在”的直接反事实。开放之后是否仍需要香港，看法律、清算、时区和网络，不是定义。

**如果 Treasury 不再具有当前抵押品地位？**  
UST identity 还在，repo 转译出的美元功能减弱。可以识别安全资产身份与抵押功能的分离。

**如果 USD clearing 摩擦下降，而中美制度摩擦仍在？**  
清算摩擦和制度摩擦不是同一个变量。若资金仍走香港，接口价值更可能来自法律和准入，而不是美元清算本身。

**如果把国际接口迁到深圳、香港内收？**  
这是 V0 原稿的主设计，本文只作反事实。真正的分析问题是：

> 香港的金融功能能否脱离当地法律、人才、机构和网络效应而迁移？

制度规则可以搬家。合约习惯、清算会员、人才和信任不一定同步搬家。这是经验问题，不是政策处方。原稿中的“彻底清算港英遗产”“顺从型退出”“让他们不再重要”删除，不服务 Q1–Q5。

---

## 2. Stress scenarios

只保留有研究价值的少数情景：

```text
美元融资压力
Treasury market dysfunction
jurisdiction fragmentation
China liquidity shock
HK interface deterioration
```

美元荒放在第一项的极端端。Jurisdiction fragmentation 打在 access / settlement。HK interface deterioration 直接打接口命题。

沙盒里把联邦基金利率拉到 7%、再报生存概率 80% / 60%，是设计演算，不是预测。本文不采用这些数字。有用的只是清单：funding 冲击之后，应先看到 basis/repo，再看到 HKD/CNH funding。

中日韩联合特区、沙特双锚、结构币、AI 调锚：作为“若多主权共享清算容器会怎样”的情景可以一笔带过，不进入主叙事。它们超出本文范围。

---

## 3. Falsification

**H：跨系统摩擦越高，香港接口价值越高。**

必要件：香港流动性仍够、退出仍可能、市场信任仍在。

若 friction ↑ 同时：

```text
HK flows ↓
CNH liquidity ↓
Connect usage ↓
```

且资金改道其他通道，则接口命题被削弱。允许最终是倒 U：摩擦极高时接口本身也坏掉。

其他必须可打掉的判断：

| 判断 | 证伪信号 |
|---|---|
| 美元必须分三层 | 三层观察量无法分离 |
| UST 通过协议获得美元功能 | repo/collateral 失效后 UST 仍直接等于美元流动性 |
| 转译 ≠ 换汇 | 所谓转译与普通 FX 无法区分 |
| GDP 份额下降不等于接口下降 | 接口指标与份额同比、持续塌缩 |
| 香港是有效观察窗口 | HKD / CNH / USD / China access 不再同场 |

---

### Research status

```text
Current conclusion:
最硬的证伪针对“摩擦↑ → 香港接口价值↑”。港深角色对调只保留“功能能否迁移”这一问。极端崩溃和接管方案不作为主叙事。

Evidence:
证伪依赖流量和流动性，不依赖地位叙事。

Counterevidence:
若替代通道在制度上不存在，“绕开香港”这条证伪路径本身不成立，需要另写。

Market implication:
压力期同时看香港的量和价，以及是否改道。量价同弱且改道成立，接口命题受损。

Watch:
Connect 与其他准入的相对份额；CNH 对其他离岸场所；清算摩擦与制度摩擦是否同向。

Falsifier:
列出的证伪信号出现后，正文仍把原判断写成不易证伪的结构真理。

Last updated: 2026-09-05
```


# 07 Conclusion

收束能说什么、不能说什么。不在这里补新机制。不把第 6 章的反事实改写成新世界观。

---

## 可以锁住的

1. 问题不是美元崩溃或人民币替代，而是功能分层与约束。  
2. 美元按财政、货币、全球协议三层来写。  
3. 资产身份不等于资产功能。UST、HKD、CNH 都适用。  
4. 美元风险首先是 functional risk。信用质量稳定时，融资、抵押、结算或准入仍可下降。  
5. 转译是既有协议接续功能，不是普通换汇，也不是新系统设计。  
6. 结构必须进入 Structure → Trigger → Observable → Price。  
7. 香港是观察窗口。它是不是中介层，仍是经验问题。  
8. 香港相对 GDP 权重下降是观察。它是否等于接口价值下降，未决。

该强的地方仍然强：联系汇率把 HKD 接到美元储备和兑换保证，这是制度规定，不必写成“可能”。

---

## 不能说的

- 香港全球唯一  
- 摩擦越高香港越有价值（待检验，且有证伪条件）  
- 中介层必然出现  
- 香港是信用负资产  
- 世界害怕、资本无法拒绝、市场认为  
- 人民币将定义未来路径协议  
- 全面接管、IMF 2.0、多锚世界秩序  
- 某资产因此应当看多或看空

V0 里值得救的直觉已经进正文：接口、功能与信用分开、主权层与信用层可分离、claim 可通过协议获得另一种功能、中介价值随直接路径摩擦变化。  
V0 里不能靠润色救的句子已经降级或归档：全球唯一、全面接管、世界必然、资本无法拒绝、最终都会、把 GDP 下降写成负资产事实。

---

## 主链

```text
Premises → Structure → Risk → Translation → Market
```

验证仍靠：Data + Evidence + Counterfactual + Falsification。

下一步不是再发明体系，而是核实官方序列、补 core indicators、用 1998 / repo / Connect 案例把中间节点填实。

---

### Research status

```text
Current conclusion:
V1 正文已按类型重写。实质性市场检验仍薄，数字和案例需回官方来源。

Evidence:
制度事实强于市场检验。功能风险定义与三层结构一致。

Counterevidence:
见第 6 章证伪表。任何一条被打中，改对应章节结论，不改引言问题。

Market implication:
无交易结论。

Watch:
article/ 是否用 foundations/ 的词；candidates/ 是否未经审核写进结论。

Falsifier:
结论章重新引入去美元化、多锚秩序或新货币系统设计。

Last updated: 2026-09-05
```
