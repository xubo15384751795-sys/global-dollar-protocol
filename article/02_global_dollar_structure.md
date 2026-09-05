# 02 Global Dollar Structure

## 问题

美元究竟是什么？

本章把 USD 拆成三层。它是理解后文“美元风险”的必要条件，不在这里预测美元指数。

---

## 三层

```text
US Fiscal
    ↓
Treasury
    ↓
UST

Federal Reserve
    ↓
Base money
Liquidity
Monetary policy

Global Protocol
    ↓
Banks
Repo
FX swaps
Clearing
Collateral
Funding
Trade
Reserves
```

$$
\boxed{\text{USD} = \text{US Fiscal} + \text{Federal Reserve} + \text{Global Dollar Protocol}}
$$

---

## Treasury ≠ Dollar

UST 是财政层的负债，不是美元本身。它成为美元功能，要经过协议：

$$
\text{Treasury} \xrightarrow{\text{financial protocol}} \text{Dollar Function}
$$

最常见的一条是 repo：持有 UST，并不等于持有现金美元；拿到 UST 抵押融资，才获得美元 funding function。

因此：

- Treasury supply 变化首先是财政层事件
- 它能否变成美元流动性，取决于 dealer、repo、抵押品资格和清算
- Fed 可以提供准备金和设施，但不必与财政供给同步
- 全球借款人通过 FX swap / 离岸银行美元使用美元功能，更不必与美国国内政策目标同步

---

## 协议层不是“海外美元现钞”

Global Protocol 包括：

- 银行美元与 offshore dollars
- correspondent banking
- FX swap
- repo 与 Treasury collateral
- trade invoicing
- clearing
- hedging
- reserve management
- jurisdiction / compliance

这一层使美元可以在美国财政和美联储并不直接操作的地方继续作为功能货币。它也使美元风险可以出现在美国国内指标看起来并不极端的时候。

---

## 层可以不同步

财政扩张、Fed 收紧、全球美元借款需求上升，可以同时发生。此时受损的不是“美元身份”，而是某一层的功能，或层与层之间的匹配。

后文把这种错配写成 $R_{\text{interaction}}$。本章只需要确立：三层分开是合法的，合并成一个“美元涨跌”是不够的。

---

### Research status

```text
Current conclusion:
美元必须按财政、货币、全球协议三层来写。Treasury 可以转译出美元功能，但它不是美元。

Evidence:
UST repo、FX swap、离岸银行美元、correspondent banking 在制度上把非现金资产和境外主体接到美元功能上。

Counterevidence:
若全球美元使用在经验上几乎完全由 Fed 资产负债表解释，协议层就没有独立分析价值。

Market implication:
看 UST 供给时，同时看 dealer / repo；看 Fed 时，同时看 FX basis 和离岸 funding。不要把 DXY 当成三层的充分统计量。

Watch:
Treasury issuance vs dealer capacity；SOFR / repo vs Fed 政策利率；cross-currency basis vs 美国国内流动性。

Falsifier:
三层指标长期同向、同幅，层间错配无法被市场观察量分开。
```
