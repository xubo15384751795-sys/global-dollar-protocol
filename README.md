# Global Dollar Protocol & Financial Function Translation  
# 全球美元协议与金融功能转译

## 1. 项目概述

本项目研究全球美元体系中的一个基础问题：

> **金融资产“是什么”，与它在特定制度和市场条件下“能够做什么”，是否是同一件事？**

传统宏观分析通常将货币视为国家经济、财政与中央银行体系的映射。但美元与一般主权货币存在一个重要差异：美元不仅运行于美国财政与美联储体系内部，还运行于一个规模庞大、跨越司法辖区和资产负债表边界的全球金融网络中。

因此，本项目将美元粗略拆分为三个相互连接但并不完全重合的层次：

```text
USD = US Fiscal Layer + Federal Reserve Monetary Layer + Global Dollar Protocol Layer
```

其中：

- **Fiscal Layer**：美国财政、美国国债、财政信用与安全资产供给；
- **Monetary Layer**：Federal Reserve、基础美元、准备金、利率与最终流动性支持；
- **Global Protocol Layer**：全球银行体系、离岸美元、repo、FX swap、抵押品网络、支付清算、贸易计价、储备管理、跨境融资与司法/合规准入。

本研究关注的不是“美元是否会崩溃”，也不是“人民币是否会取代美元”。

真正的问题是：

> **美元及美元相关资产分别承担哪些金融功能？这些功能在什么条件下可能受到限制？当一种资产无法直接完成某项功能时，市场是否能够通过抵押品、融资、清算、离岸市场或其他制度安排，将另一种金融 claim 转化为所需要的功能？**

香港是本项目最重要的现实观察场之一。

HKD、CNH、美元融资、中国资本市场接口、普通法金融框架、Connect 机制以及全球金融基础设施在香港同时存在，使香港成为观察以下现象的天然案例：

- 主权归属与货币信用来源的部分分离；
- 在岸与离岸流动性的分离；
- 资产身份与金融功能的分离；
- 不同金融体系之间的市场接口；
- 跨法域资金、抵押品与结算功能的重新组合。

本项目最终是一项**宏观金融与市场研究项目**。

制度与结构分析不是终点。

所有核心判断最终都应尽可能回答：

> So what for markets?

---

# 2. 核心研究命题

本项目建立在两个基础前提之上。

## Premise 1 — 美元不是普通意义上的单一主权货币体系

一般主权货币可以粗略理解为：

```text
Currency_i ≈ Fiscal_i + CentralBank_i + DomesticMarket_i
```

其货币使用、信用创造、融资、储备和资产定价主要围绕本国或本区域经济体系运行。

美元则额外具有一个全球协议层：

```text
USD = Fiscal + Monetary + Global Protocol
```

大量美元活动可以发生在：

- 美国之外；
- 非美国银行之间；
- 非美国企业之间；
- 与美国国内贸易无直接关系的交易中；
- 离岸融资和衍生品体系中；
- 全球抵押品和储备资产网络中。

因此：

```text
Global Dollar Usage ≠ US Domestic Dollar Usage
```

美元风险不能只通过美国 GDP、财政赤字或 Federal Reserve 政策解释。

---

## Premise 2 — Asset Identity ≠ Asset Function

一项资产的法律身份、发行主体或计价货币，并不能完全决定其金融功能。

例如：

```text
UST --[Repo]--> USD Liquidity
```

US Treasury security 本身不是美元现金，但它可以通过 repo 获得美元融资功能。

同样，一项资产可以同时具有不同属性：

- issuer；
- sovereign origin；
- denomination；
- collateral eligibility；
- liquidity currency；
- settlement system；
- legal jurisdiction；
- market access。

这些属性不必完全重合。

因此本项目采用：

```text
Asset Identity ≠ Asset Function
```

以及：

```text
Function = f(Asset, Institution, Market, State)
```

作为第二个基础分析前提。

---

# 3. 核心研究问题

项目围绕五个问题展开。

---

## Q1 — 香港究竟是一种怎样的金融结构？

问题不是：

> 香港重要吗？

也不是：

> 香港 GDP 占中国多少？

而是：

> **香港如何将主权、货币信用、流动性、市场形成、资本准入和国际金融协议重新组合在同一个金融空间中？**

重点研究：

### HKD

分析：

- Hong Kong jurisdiction；
- Currency Board；
- USD anchor；
- HKD monetary base；
- Aggregate Balance；
- HIBOR；
- HKD/USD；
- 香港银行体系。

重点问题：

> HKD 的主权/制度归属、信用锚、市场流动性和最终流动性来源是否属于同一个层次？

---

### CNH

分析：

- RMB sovereign origin；
- offshore price formation；
- CNH liquidity；
- CNH funding；
- CNH-CNY spread；
- offshore RMB deposits；
- offshore bonds；
- RMB liquidity arrangements。

重点问题：

> 为什么人民币可以在中国资本账户之外形成具有自身价格、流动性和融资结构的离岸市场？

---

### Hong Kong interface

研究：

- Stock Connect；
- Bond Connect；
- Swap Connect；
- USD clearing；
- RMB clearing；
- collateral arrangements；
- cross-border financing；
- international legal compatibility；
- capital access。

核心假说：

```text
V_HK = f(Access, Liquidity, Compatibility, Collateral, Exit, Friction)
```

香港的金融价值不被视为固定属性。

它可能取决于：

> 两个金融体系之间存在多少摩擦，以及香港自身是否仍然能够以足够低的成本处理中间转换。

---

# Q2 — 全球美元体系究竟由哪些层构成？

这一部分拆解的是 USD，而不是把“美元”作为单一变量。

核心结构：

```text
US Fiscal Layer
        │
        ├── Treasury issuance
        ├── sovereign credit
        └── US Treasury securities
                │
                ↓
        global collateral system

Federal Reserve
        │
        ├── reserves
        ├── monetary policy
        ├── liquidity facilities
        ├── swap lines
        └── lender-of-last-resort functions

Global Dollar Protocol
        │
        ├── global banks
        ├── offshore dollars
        ├── repo
        ├── FX swaps
        ├── correspondent banking
        ├── payments
        ├── clearing
        ├── collateral
        ├── trade invoicing
        ├── derivatives
        └── reserves
```

关键区分包括：

```text
Treasury ≠ Dollar
```

但：

```text
Treasury --[Repo / Collateral]--> Dollar Function
```

因此美国国债既是：

> 美国财政负债

也是：

> 全球金融协议中的 collateral / liquidity / benchmark asset。

这一部分重点研究三层之间：

- 如何连接；
- 是否同步；
- 哪些情况下出现错配；
- 哪些压力属于财政问题；
- 哪些属于央行问题；
- 哪些属于全球协议层问题。

---

# Q3 — 什么才叫“美元风险”？

本项目不采用以下简单定义：

```text
Dollar Risk = Dollar Collapse
```

也不采用：

```text
Dollar Risk = Dollar Shortage
```

美元荒被视为某些压力状态下的结果，而不是理论起点。

本项目定义：

> **Dollar Functional Risk：美元或美元相关金融资产在特定制度、市场或资产负债表状态下，无法继续以原有成本、范围或可靠性完成某项金融功能的风险。**

需要区分：

### Fiscal Risk

- Treasury supply；
- fiscal credibility；
- debt service；
- issuance structure；
- term premium。

### Monetary Risk

- Fed policy；
- reserve conditions；
- balance-sheet policy；
- liquidity facilities；
- lender-of-last-resort capacity。

### Funding Risk

- offshore dollar funding；
- bank funding；
- FX swap funding；
- short-term refinancing。

### Collateral Risk

- collateral scarcity；
- haircut；
- eligibility；
- repo capacity；
- market depth。

### Settlement Risk

- payment access；
- clearing；
- settlement delay；
- infrastructure disruption。

### Jurisdiction / Access Risk

- sanctions；
- compliance；
- correspondent access；
- legal restriction；
- capital controls。

### Intermediation Risk

- dealer balance-sheet constraints；
- bank balance-sheet constraints；
- leverage；
- margin calls；
- NBFI intermediation。

### Interaction Risk

尤其关注层间错配 `R_interaction`：

即：

> 单个层自身可能仍然稳定，但两个层之间的连接出现压力。

例如：

```text
Treasury Supply ↑
但 Dealer Capacity 未上升
```

从而出现：

```text
Fiscal → Protocol
```

的接口压力。

---

# Q4 — 金融功能能否被“转译”？

本项目使用 **Financial Function Translation** 描述：

> 一项金融 claim 通过市场或制度协议获得原本并不直接具有的金融功能。

基本表达：

```text
Asset_A --[Protocol]--> Function_B
```

现实中可能涉及：

- repo；
- reverse repo；
- collateral transformation；
- FX swap；
- cross-currency swap；
- cross-currency repo；
- liquidity facility；
- clearing arrangement；
- Connect mechanism；
- offshore market；
- correspondent banking；
- margin collateral；
- rehypothecation。

例如：

```text
UST → Repo → USD Funding
```

这里发生的不是资产身份变化。

发生的是：

> 一项 fiscal claim 获得 liquidity function。

因此本项目不把所有换汇行为称作“转译”。

单纯：

```text
USD → RMB
```

不是本研究意义上的充分转译机制。

真正重要的是：

> 某个制度或市场协议是否改变了资产能够承担的金融功能。

---

## 中介层不是预设结论

本项目不假定市场必然产生中介层。

直接路径：

```text
A → B
```

成本为 `C_D`。

通过中介：

```text
A → I → B
```

成本为：

```text
C_I + R_I
```

只有当：

```text
C_D > C_I + R_I
```

时，中介结构才有经济价值。

因此：

> 香港是不是重要的金融中介层？

是 empirical question。

而不是 premise。

---

# Q5 — 金融功能变化如何进入市场价格？

所有结构性判断最终应尽可能建立：

```text
Structure → Trigger → Transmission → Observable → Price
```

的传导链。

例如：

## Treasury transmission

```text
Treasury issuance
        ↓
investor absorption
        ↓
dealer balance sheet
        ↓
repo / collateral
        ↓
USD funding
        ↓
FX swap / cross-currency basis
        ↓
global asset pricing
```

---

## Dollar → Hong Kong

```text
USD funding
        ↓
HKD liquidity
        ↓
HIBOR
        ↓
local financing conditions
        ↓
HK property / equities / credit
```

---

## China → Hong Kong

```text
China monetary / financial conditions
        ↓
CNY
        ↓
CNH
        ↓
offshore liquidity
        ↓
Connect / capital flows
        ↓
HK / China asset prices
```

市场研究重点不是机械预测资产涨跌。

更重要的是识别：

> 如果一个结构判断成立，哪些价格和资金流应该最先发生变化？

---

# 4. 研究方法

本项目采用多层验证，而不是单一统计模型。

## 4.1 Institutional Analysis

确认：

- 货币制度；
- 账户体系；
- collateral rules；
- clearing arrangements；
- liquidity facilities；
- market access；
- legal arrangements；
- capital controls。

主要解决：

> **系统实际上允许参与者做什么？**

---

## 4.2 Balance-Sheet Analysis

关注：

- Treasury；
- Fed；
- banks；
- dealers；
- central banks；
- NBFIs；
- HKMA；
- offshore financial institutions。

主要解决：

> **谁承担资产？谁提供流动性？谁承担中间风险？**

---

## 4.3 Market Plumbing

研究：

- repo；
- FX swaps；
- settlement；
- clearing；
- collateral；
- margin；
- liquidity facilities；
- dealer intermediation。

主要解决：

> **宏观冲击究竟通过什么具体路径传递？**

---

## 4.4 Market Data

使用：

- prices；
- spreads；
- rates；
- flows；
- volumes；
- holdings；
- balance sheets；
- market depth；
- issuance；
- liquidity indicators。

重点是形成：

```text
Mechanism ↔ Observable
```

关系。

---

## 4.5 Historical Cases

历史案例不是为了讲故事。

每个案例用于测试：

> 一个特定机制在压力状态下是否真实存在。

可能包括：

- 1997–98 Asian/Hong Kong stress；
- 2008 Global Financial Crisis；
- 2019 repo stress；
- 2020 dash for cash / global dollar shortage；
- major sanctions episodes；
- HKD liquidity episodes；
- CNH liquidity stress episodes。

案例数量服从研究问题，不追求全面历史覆盖。

---

## 4.6 Counterfactual Analysis

反事实用于识别真正承担作用的变量。

例如：

- 如果香港没有 CNH，会发生什么？
- 如果 HKD 不与 USD 挂钩，香港接口结构会怎样改变？
- 如果中国资本账户完全开放，香港接口价值会如何变化？
- 如果 UST 不再具有当前 collateral status，会发生什么？
- 如果美元 clearing friction 显著下降，但中美制度差异仍然存在，香港价值是否下降？

反事实不被视为事实预测。

它们用于：

**Mechanism Identification**

---

## 4.7 Scenario Analysis

Scenario 不等于 forecast。

场景用于：

> 改变关键条件，观察模型如何重新排列传导路径。

主要变量可包括：

```text
Treasury supply
Fed liquidity
USD funding condition
dealer balance-sheet capacity
collateral availability
jurisdiction friction
China capital openness
CNH liquidity
HKD liquidity
Hong Kong interface credibility
```

极端美元荒、Treasury dysfunction 等可作为 tail scenarios，但不作为项目主叙事。

---

# 5. 数据原则

本项目不是计量论文，也不要求所有判断都达到同一种统计标准。

数据的作用主要包括：

1. 描述结构；
2. 判断当前 regime；
3. 验证传导链；
4. 识别市场状态变化；
5. 证伪关键命题；
6. 比较不同案例。

数据质量优先级：

### 一级

官方、市场基础设施和监管数据：

- Federal Reserve；
- New York Fed；
- US Treasury；
- BIS；
- IMF；
- HKMA；
- PBoC；
- SAFE；
- HKEX；
- CIPS；
- official Connect statistics。

### 二级

可靠市场数据库和机构研究。

### 三级

新闻、媒体与二手资料。

二手资料不能独立承担核心制度事实或关键量化结论。

---

# 6. 来源体系

本项目来源分为三组。

## Official / Institutional

主要用于：

- 制度事实；
- 官方数据；
- 市场基础设施；
- 政策工具；
- balance-sheet structure。

核心机构：

- BIS / CGFS；
- Federal Reserve；
- New York Fed；
- US Treasury；
- IMF；
- HKMA；
- HKIMR；
- PBoC；
- SAFE；
- HKEX。

---

## Academic

主要用于：

- dominant currency；
- safe asset；
- global financial cycle；
- global banking；
- dollar funding；
- network effects；
- collateral；
- financial intermediation。

---

## Market Research

用于回答：

> 结构变化如何被市场参与者实际映射到价格、flow、rates、FX 和资产配置？

重点参考：

- Standard Chartered；
- JPMorgan；
- Citi；
- Goldman Sachs；
- HSBC；
- MUFG；
- Gavekal；
- ASR；
- CrossBorder Capital；
- 其他具有 global macro / FX / rates / liquidity 专长的研究机构。

机构观点本身不是事实。

需要区分：

```text
Data ≠ Institutional Interpretation ≠ Project Interpretation
```

---

# 7. 市场观察框架

核心市场指标不要求固定不变。

根据研究问题动态增加。

当前主要包括：

## USD / Global Dollar

- DXY / broad dollar indices；
- FX swap basis；
- cross-currency basis；
- offshore USD credit；
- bank dollar funding；
- Fed swap line usage；
- FIMA repo usage；
- global dollar credit。

## Treasury

- Treasury yields；
- curve；
- term premium；
- issuance；
- dealer holdings；
- repo rates；
- Treasury basis；
- bid-ask spreads；
- market depth；
- foreign holdings。

## HKD

- USD/HKD；
- Convertibility Undertaking activity；
- Aggregate Balance；
- HIBOR；
- HKD forward；
- local banking liquidity。

## CNH

- USD/CNH；
- CNY-CNH spread；
- CNH HIBOR；
- offshore RMB deposits；
- offshore RMB issuance；
- RMB clearing data。

## Cross-border Access

- Stock Connect；
- Bond Connect；
- Swap Connect；
- Northbound / Southbound flows；
- collateral usage；
- cross-border repo；
- RMB settlement。

## Asset Prices

根据具体机制进一步映射到：

- Hong Kong equities；
- China equities；
- China government bonds；
- offshore China credit；
- property；
- EM FX；
- gold；
- Treasury；
- global risk assets。

---

# 8. 可证伪原则

本项目不接受：

> “无论发生什么，都可以通过事后解释证明理论正确。”

所有关键命题都需要尽可能满足：

```text
Claim → Mechanism → Observable Implication → Falsifier
```

---

## 8.1 Premise-level falsification

如果：

```text
Fiscal + Fed
```

已经能够充分解释全球美元融资、跨境美元使用、流动性和市场压力，而所谓 Global Protocol variables 没有显著增加解释能力，则：

> “Global Dollar Protocol Layer”这一分析概念需要被削弱或删除。

---

## 8.2 Function-level falsification

如果制度、collateral eligibility、clearing access 等规则发生显著变化，但相关资产：

- financing capacity；
- liquidity；
- haircut；
- turnover；
- spread；
- settlement ability

长期没有系统性变化，则：

> Financial Function Translation 的解释价值需要下调。

---

## 8.3 Mechanism-level falsification

例如命题：

> 跨体系摩擦上升会提高金融接口价值。

必须附带条件：

- interface liquidity 保持；
- trust 保持；
- exit ability 保持；
- market depth 保持。

如果：

```text
Friction ↑
同时
HK Flows ↓
CNH Liquidity ↓
Connect Usage ↓
```

并且资金系统性转向其他渠道，则：

> Hong Kong interface premium hypothesis 被削弱。

模型允许最终出现：

```text
V_Interface = f(Friction)
```

为倒 U 型，而不是强制：

```text
∂V/∂Friction > 0
```

---

## 8.4 Transmission falsification

市场传导必须按链条验证。

如果假设：

```text
A → B → C → D
```

那么：

- A 出现而 B 不出现：第一段机制需要重新评估；
- B 出现而 C 不出现：第二段机制存在问题；
- C 出现而 D 不出现：跨市场传递可能被其他因素抵消。

不能仅凭最终资产价格方向判断整套模型成败。

---

## 8.5 Comparative falsification

香港不能只与自身比较。

需要在适当情况下与：

- Singapore；
- London；
- Dubai；
- direct mainland channels；
- other offshore structures

比较。

如果香港市场表现完全可以由：

```text
Global Liquidity + China Beta
```

解释，而无法识别独立的 interface effect，则：

> Hong Kong 不应继续被视为理论核心，只能作为案例之一。

---

# 9. 适用范围

本项目主要适用于：

> **存在明确市场价格、跨境融资、清算、抵押品和金融基础设施的美元及美元相关金融体系。**

重点研究：

- 正常市场状态；
- liquidity tightening；
- funding stress；
- collateral stress；
- jurisdiction friction；
- market rerouting；
- infrastructure changes。

主要时间尺度：

```text
Days → Months → Several Years
```

尤其适合研究：

- liquidity cycle；
- policy transition；
- funding regime；
- market infrastructure；
- cross-border flow；
- collateral regime。

---

# 10. 不适用范围

本研究不试图回答：

- 美元霸权具体哪一年终结；
- 人民币什么时候全面取代美元；
- 世界最终应该采用什么国际货币制度；
- 全球政治秩序应该如何设计；
- 全面战争后的国际金融体系；
- 所有金融法律和市场规则失效后的系统状态；
- 与金融功能传导无关的中国国内宏观问题；
- 与美元体系无关的一般国际关系问题。

如果：

```text
Institutional Rules → Undefined
```

则本项目赖以研究的“protocol”本身已经不存在。

这类状态属于模型外部。

---

# 11. 项目不做什么

本项目不是：

- 全球金融数据库；
- 通用宏观研究系统；
- knowledge graph；
- 自动交易系统；
- 投资组合优化器；
- 人民币国际化宣传项目；
- 去美元化预测模型；
- 全球制度设计项目。

项目允许：

- 内容扩大；
- 案例增加；
- 数据增加；
- 模型加深；
- 市场覆盖扩展。

但不为了管理研究而不断增加治理系统。

原则：

> **结构化论证，而不是结构化所有信息。**

---

# 12. 文章结构

主文章暂定：

```text
article/
00_introduction.md
01_hong_kong_structure.md
02_global_dollar_structure.md
03_dollar_functional_risk.md
04_financial_function_translation.md
05_market_pricing_and_rerouting.md
06_boundaries_and_counterfactuals.md
07_conclusion.md
```

逻辑顺序：

```text
Premises → Structure → Risk → Translation → Market
```

---

# 13. 项目目录

```text
global-dollar-protocol/
│
├── README.md
│
├── article/
│   ├── 00_introduction.md
│   ├── 01_hong_kong_structure.md
│   ├── 02_global_dollar_structure.md
│   ├── 03_dollar_functional_risk.md
│   ├── 04_financial_function_translation.md
│   ├── 05_market_pricing_and_rerouting.md
│   ├── 06_boundaries_and_counterfactuals.md
│   └── 07_conclusion.md
│
├── foundations/
│   ├── definitions.md
│   ├── premises.md
│   ├── assumptions.md
│   └── market_transmission_map.md
│
├── analysis/
│   ├── dollar/
│   ├── treasury/
│   ├── hong_kong/
│   ├── hkd/
│   ├── cnh/
│   ├── china_market/
│   └── cross_market/
│
├── models/
│   ├── dollar_layers.md
│   ├── functional_risk.md
│   ├── translation_protocol.md
│   ├── market_transmission.md
│   └── scenarios.md
│
├── data/
│   ├── raw/
│   ├── processed/
│   ├── indicators/
│   └── charts/
│
├── sources/
│   ├── official/
│   ├── academic/
│   ├── market_research/
│   └── source_notes.md
│
├── archive/
│   └── original/
│
└── output/
    ├── full_article.md
    ├── research_note.md
    ├── executive_summary.md
    └── figures/
```

目录允许根据研究需要自然增长。

不要求各目录对称。

---

# 14. 单章研究标准

每个主要章节最终应尽可能回答以下六个问题。

## Current Conclusion

现在认为发生了什么？

## Evidence

最重要的现实证据是什么？

## Counterevidence

哪些事实不支持当前判断？

## Mechanism

为什么会发生？

## Market Implication

如果判断成立，市场上首先应该在哪里看到？

## Falsifier

什么现象持续出现意味着当前判断需要被削弱或放弃？

建议章节末尾统一使用：

```text
Research Status

Current conclusion:
Evidence:
Counterevidence:
Market implication:
Watch:
Falsifier:
```

不需要将其做成数据库。

---

# 15. 模型原则

本项目中的模型首先是：

> **机制模型和状态模型。**

不是为了追求复杂数学。

模型价值来自：

1. 明确输入；
2. 明确传导；
3. 明确中间状态；
4. 明确输出；
5. 明确失败位置；
6. 明确可观察变量。

模型需要能够回答：

> What changes?

> Through which channel?

> Who absorbs it?

> Where should we observe it?

> What would prove the mechanism wrong?

---

# 16. 市场化原则

“市场化”不意味着每一章都必须给出交易建议。

市场化意味着：

> 所有重要结构判断最终都需要尽可能映射到可观察的价格、利率、spread、flow、liquidity 或 balance-sheet variable。

研究优先回答：

> 如果这个判断真的成立，市场应该按照什么顺序发生变化？

而不是简单回答：

> 看多还是看空？

最终理想结构：

```text
Structural Claim
        ↓
Trigger
        ↓
Transmission Mechanism
        ↓
First Observable
        ↓
Secondary Observable
        ↓
Asset Pricing
        ↓
Counter-signal
```

---

# 17. 项目核心判断的状态管理

本项目不建立复杂的 claim registry。

但所有核心判断应允许以下三种结果：

### Supported

当前证据支持。

### Conditional

只在特定条件下成立。

### Rejected / Weakened

现实证据或反事实明显削弱。

允许：

- 香港不是特殊中介；
- 某种 translation mechanism 没有经济价值；
- 某种 dollar functional risk 被高估；
- 某些市场变量并不存在预想中的传导。

局部假说失败不意味着整个研究项目失败。

项目级失败只发生在：

> 整套“金融功能—协议层—转译—市场传导”框架长期无法提供超越传统宏观变量的额外解释能力时。

---

# 18. 项目最终目标

本项目最终希望形成三个层次的结果。

## Layer 1 — Structural Understanding

回答：

- 美元体系究竟如何运行？
- 美元、美债、Fed、Treasury 和全球金融网络如何连接？
- 香港的特殊性究竟来自哪里？
- HKD 与 CNH 为什么可以产生不同的金融组合？

---

## Layer 2 — Mechanism

回答：

- 什么叫美元功能风险？
- 哪一层会出现风险？
- 风险如何跨层传播？
- 金融功能如何通过协议重新获得？
- 中介什么时候有价值，什么时候失效？

---

## Layer 3 — Markets

回答：

- 哪些价格最早反映变化？
- 哪些资金流能够验证机制？
- 哪些市场承担最终风险？
- 什么价格关系说明市场正在重路由？
- 什么现象意味着当前模型判断错误？

---

# 19. 最终研究原则

本项目遵循以下原则：

### 1. 不预设美元衰落

美元可以继续非常强，同时某些美元功能出现局部压力。

### 2. 不预设人民币替代美元

人民币、CNH 和中国资产只是研究金融功能转译的重要对象。

### 3. 不预设中介层一定成功

中介是否产生价值取决于成本、信任、流动性和市场深度。

### 4. 不把极端情景当作基准情景

美元荒和系统性危机用于 stress testing。

### 5. 区分资产身份和资产功能

这是整个研究最重要的分析原则之一。

### 6. 区分财政、央行和全球协议层

不得将所有美元现象简单归因于 Federal Reserve。

### 7. 每个宏观判断最终尽可能连接市场 observable

不能落到价格、flow、spread 或 balance sheet 的判断，应明确其证据边界。

### 8. 允许理论被削弱

研究目标不是证明最初观点正确。

而是不断缩小：

> What is actually true?

---

# 20. 一句话定义

> **本项目研究美元、美债、HKD、CNH 等金融 claim 在财政、央行、全球金融协议和跨境市场结构中如何获得不同金融功能；这些功能在什么条件下受到限制、如何被其他资产或制度路径接续，以及这些变化如何最终反映在全球市场价格、流动性与资金流中。**

最简表达：

```text
Asset → Institution → Function → Risk → Rerouting → Market
```

这就是项目的研究边界。
