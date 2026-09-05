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

Last updated: 2026-09-05
```
