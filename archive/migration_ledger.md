# Pass 2–5 — Claim sanitization, causal repair, scope, marketization

Source: `archive/original/original.md`  
Classification: `archive/working_classified.md`  
规则：不把强判断改成“可能”。强度必须对应证据。原意先保留，再决定降级、条件化、改成问题、假说、反事实，或删除。

语言等级：

| 状态 | 表达 |
|---|---|
| 已确认事实 | 数据显示 / 制度规定 / 已存在 |
| 强支持解释 | 这表明 / 这与……一致 |
| 条件判断 | 在 A、B 条件下，预计 |
| 假说 | 本文提出 / 一种可能解释是 |
| 情景 | 若……则可以推演 |

---

# Pass 2 — Claim sanitization

不是正则替换。每一处绝对用语只判 A–E。

| 原文要点 | 词 | 判定 | 处理 |
|---|---|---|---|
| HKD 由美元储备支持的货币局 | — | A 有制度事实 | 保留强表述 |
| 香港 GDP 份额 18.4%→2.1% | — | A 待核数字后可保留 | [V] 后可进正文 |
| 香港是全球唯一接口 | 唯一 | C 假说 | 降为待检验 H；比较新加坡/伦敦/在岸直连 |
| 全球可以绕开中国不能绕开香港 | 无法 | C/D | 改成问题：哪些功能目前仍主要经过香港 |
| 信用负资产 | 已从…转化为 | E 价值判断 | 拆 Observation / Question / H1 H2 / Test |
| 香港社会沉溺殖民幻觉 | — | D/E | 删除群体心理；留下制度接口问题 |
| 世界害怕没有备用锚 | 世界 | D | 改为：依赖美元融资/结算的参与者面临约束 |
| 资本天然偏好模糊 | 资本天然 | D | 改为：模糊法域如何进入风险定价和合约选择 |
| 回归前狙击香港一定被击穿 | 一定 | B 条件判断 | 条件：无最终流动性、储备有限、固定汇率 |
| 中国必然出手 | 必然 | C | 1998 是案例，不是定律 |
| 中国不出手香港必然溃败 | 必然 | B/CF | 标反事实，写清机制链 |
| 资本无法做空新香港 | 无法 | D 设计断言 | 标 [D]；可提取：退出摩擦如何改变空头成本 |
| 全球资本无法拒绝的诱惑 | 无法 | D | 见下方改写树，不进结论 |
| 只要一市场陷落其余向中国靠拢 | 只要 | C | 补 C1–C3 条件 + flow 验证 |
| 只要中国接住一个锚资本不会溃散 | 只要 | C | 假说 + 谁吸收 + 证伪 |
| 单锚结构正在系统性瓦解 | 正在 | C/D | 不预设瓦解；拆功能 |
| 人民币将定义未来路径协议 | 将 | 情景 | [S] 或 Design experiment |
| 全面接管美元霸权 | 全面 | E/N | ARCHIVE；提取协议竞争问题 |
| 彻底清算港英遗产 / 让他们不再重要 | 彻底 | E | 删除 |
| 三层以上禁止 / 必须缴纳 | 必须 | D | illustrative parameter，不是可行性证明 |
| SWIFT 50.2% / RMB 4.33% | — | A 待核 | 核原口径后再当事实 |

典型改写（保留强度，补类型）：

**“全球资本无法拒绝的诱惑。”**  
若该结构能同时降低跨境准入摩擦并保留足够退出流动性，相对直接进入在岸的成本优势可能提高。需用资金流、融资成本、参与度验证。

**“单锚结构正在系统性瓦解。”**  
本文不预设美元主导体系正在瓦解，而区分储备、融资、抵押、清算、司法可达性。某一功能受压 ≠ 体系整体失效。

**“美元信用不会崩塌，但美元无法释放信用才是更危险的场景。”**  
本研究关注一种区别于美元信用损失的风险：美元及相关资产的信用质量可能保持稳定，但特定参与者在融资、抵押、结算或跨法域使用上的功能可达性下降。定义为 Dollar Functional Risk。

**“美国建立了全球资本的运行速度，中国将定义全球信用的容器结构。”**  
不进结论。提取问题：跨境金融竞争是否部分从货币使用份额，转移到 collateral eligibility、market access、clearing 和 settlement protocol？

---

# Pass 3 — Causal repair

找 `A → C` 缺 B 的箭头。中间无证据的箭头变成 research question。

### 3.1 GDP → 负资产

```text
GDP share ↓
       ?
financial function ↓
       ?
cross-border usage ↓
       ?
interface value ↓
```

问：经济体量下降是否意味着跨境金融接口价值同步下降？  
Test：跨境融资、CNH、Connect、清算、市场深度。

### 3.2 接口摩擦 → 香港更有价值

```text
direct USD access friction ↑
       ?
HK / CNH / Connect usage ↑
       ?
interface premium ↑
```

证伪：friction ↑ 同时 HK flows / CNH liquidity / Connect ↓，资金改道。

### 3.3 市场陷落 → 靠拢中国

```text
some market fails
       ?
who absorbs
       ?
why HK/CNH not SG/London/onshore
       ?
flows actually move
```

缺吸收者和替代通道。

### 3.4 1998 出手 → 人民币信用出海

```text
HKMA intervention 1998
       ?
HKD peg holds
       ?
RMB internationalization later
```

后一跳过长。1998 至人民币国际化不是同一机制。

### 3.5 功能受限 → 转译自动成功

```text
Function_B blocked
       ?
Protocol exists
       ?
C_direct > C_intermediation + R
       ?
Function recovered
```

中介不是前提。

### 3.6 设计规则 → 风险消失

```text
HPV-Scan / 三层禁止
       ?
opacity ↓
       ?
haircut/liquidity ?
```

设计参数不是已实现机制。

这一遍直接生成任务：Q1 接口是否随 GDP 同比；Q1 香港 vs 新加坡；Q2/Q3 功能分层；Q3 1998 案例核实；Q4 既有转译协议；Q5 传导链。

---

# Pass 4 — Scope migration

每段只有四种结果。

| 材料 | 结果 | 去向 |
|---|---|---|
| HKD 货币局、普通法、单独关税/清算身份 | KEEP | article/01，analysis/q1 |
| CNH / Connect / 美元资金同场 | KEEP | article/01，analysis/q4 |
| 港币是壳、制度才是接口 | MOVE + REDEFINE | Q1/Q2；Identity ≠ Function |
| 美元信用 vs 使用功能 | KEEP 种子 | Q3 Functional Risk；见 candidates |
| 中介价值随直接路径摩擦变化 | KEEP 种子 | Q4/Q1；证伪已写在 Loop |
| GDP 份额下降 | KEEP 为 observation | Q1 competing H |
| 2019 股市/零售/游客数字 | MOVE | analysis/q1，须核实 |
| 1998 港元保卫战事实机制 | MOVE | analysis/q3；删猎杀修辞 |
| 新加坡/上海/伦敦不可替代表 | CANDIDATE | 比较组，不是公理 |
| 深港角色对调 | ARCHIVE 大部；少量 CF | article/06：功能能否迁移 |
| 中日韩联合特区 / TRZ | ARCHIVE | 少量作 Q4 counterfactual |
| IMF 2.0 / 全面接管 | ARCHIVE | 出 scope |
| 沙特双锚、SR-Token、AI 节奏 | ARCHIVE | 出 scope；AI 主题禁扩 |
| HPV/ASP/三层禁止 | ARCHIVE 为设计；提取抵押品不透明问题 | Q3/Q4 design hypothesis |
| 彻底清算港英 / 造反锚点 / 顺从型退出 | ARCHIVE | 不进新版 |
| 世界害怕 / 资本无法拒绝 | ARCHIVE 修辞 | 抽象成约束分析 |
| SWIFT 份额等数据 | CANDIDATE until verified | data/indicators 核后再用 |
| 节奏饥渴、补液器、安全带 | 比喻 | 能映射 observable 才许出现在论证 |

HKD/CNH 双轨：KEEP。  
美元信用释放路径：MOVE + REDEFINE → Q3。  
索罗斯五步法：核实后留压力机制，删戏剧。

---

# Pass 5 — Marketization

只对 KEEP / 正式假说问这六句。过不了的：可留背景或 H，不进核心结论。

### K1 香港是分层金融结构

- Mechanism：主权/法律、HKD-USD 锚、CNH、USD funding、Connect 同场，identity 与 function 可分离。  
- Who absorbs：HKMA、在港银行、交易所、清算行。  
- Observable：USD/HKD、Aggregate Balance、HIBOR、CNH HIBOR、CNH–CNY、Connect flows。  
- First：HIBOR / Aggregate Balance / CNH spread，不是港股口号。  
- Alt：仅 China beta + global liquidity。  
- Falsifier：HKD 脱锚运行，或 CNH/Connect 主场已不在香港。

### K2 GDP 权重下降 ≠ 接口价值下降

- Mechanism：未决。H1 同比弱化；H2 制度/流动性/准入主导。  
- Who absorbs：视 H 而定。  
- Observable：上列接口指标 vs 名义 GDP 份额。  
- First：flows 和 funding，不是 GDP。  
- Alt：上海/新加坡替代。  
- Falsifier：份额下降期间接口指标同步崩溃且不可逆。

### K3 Dollar Functional Risk

- Mechanism：财政/货币/协议层可不同步；信用质量稳定时，funding/collateral/settlement/access 仍可受损。  
- Who absorbs：全球美元借款人、dealer、离岸银行、外储管理者。  
- Observable：repo、FX basis、haircut、swap line/SRF、offshore credit。  
- First：repo/basis，不是 DXY。  
- Alt：单纯美元短缺或美元崩溃叙事。  
- Falsifier：所谓美元风险出现时，功能指标均无压力。

### K4 转译是协议接功能，不是换汇

- Mechanism：`Asset_A --[Protocol]--> Function_B`。  
- Who absorbs：repo dealer、清算行、Connect 中介、对应行。  
- Observable：haircut、basis、Connect 额度/流量、CNH 流动性。  
- First：协议价格，不是人民币国际化口号。  
- Alt：只是普通 FX。  
- Falsifier：所谓转译与 FX 在数据上无法区分。

### K5 摩擦↑ → 香港接口价值↑

- Mechanism：仅当香港流动性、信任、退出仍在。  
- Who absorbs：在港中介资产负债表。  
- Observable：HK flows、CNH depth、Connect、相对新加坡份额。  
- First：流量和深度。  
- Alt：改道其他中心或在岸直连。  
- Falsifier：friction↑ 且香港量价同弱、资金改道。

过不了 Pass 5 的：IMF 2.0、全面接管、资本无法拒绝、世界害怕、HPV 三层禁令作为必然规则、港深对调作为政策结论。

---

# 种子 vs 旧叙事

值得救：

- 香港作为制度接口  
- 美元“信用”与“使用功能”的区别  
- 主权层与信用层可以部分分离  
- claim 可通过协议获得另一种金融功能  
- 中介价值随直接路径摩擦变化  

不能靠润色救，必须回类型判定：

- 全球唯一  
- 全面接管  
- 世界必然  
- 资本无法拒绝  
- 最终都会  
- 信用负资产（作为已证事实）

旧文定位：高密度但 epistemic status 混乱的 V0 research notebook。不是等待把语气改软的终稿。
