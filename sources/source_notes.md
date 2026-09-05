# Source notes

来源只分三类。三角结构：

$$
\text{Institution} + \text{Theory} + \text{Market}
$$

原始文件分别放进 `official/`、`academic/`、`market_research/`。本页只记：一类来源负责什么，以及迁入时不要混用。

---

## Official

BIS / Fed / NY Fed / US Treasury / IMF / HKMA / PBoC。

负责：体系到底怎么运行、数据是什么。

用于：三层结构、货币局、CNH 清算、Connect 规则、repo 设施、官方统计。

不用于：直接写成交易观点。

## Academic

NBER / journals / universities。

负责：dominant currency、safe asset、global financial cycle、offshore dollar、safe-asset shortage 等理论。

用于：给 P1/P2 和 functional risk 找既有理论接口。

不用于：把理论模型的世界秩序含义写进本文范围。

## Market Research

Standard Chartered / JPM / Citi / Goldman / HSBC / Gavekal / MUFG / ASR 等。

负责：结构怎样被真正映射到 rates、FX、flows、asset prices。

用于：第 5 章传导链、观察量选择、压力期案例。

不用于：把卖方结论当成证伪已经完成。

---

## Verified this round

- World Bank `NY.GDP.MKTP.CD`：HK/China GDP 份额 1997=18.3%，2021=2.0%。
- SWIFT RMB Tracker 2025-12：USD ~50.5% / CNY ~2.73%（含欧元区）；剔除欧元区后 USD ~58.6% / CNY ~2.13%。
- BIS 2025 FX：美元约 89% 的成交一侧。不要和 SWIFT 支付份额混用。
- HKMA / 财政司司长 1998-08-14：外汇基金入市股票与期货；8-28 结束；联系汇率未脱钩。不是“影子央行”已证。

## 使用顺序

1. 制度怎么运行：official
2. 概念有没有文献位置：academic
3. 市场怎样定价：market research
4. 最终判断仍回 `article/` 的 Research status，尤其是 Counterevidence 和 Falsifier
