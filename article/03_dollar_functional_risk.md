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
