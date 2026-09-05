# 05 Market Pricing and Rerouting

## 问题

前面的结构最终怎么进入市场？

本章把课题收成宏观/市场研究。统一使用：

$$
\boxed{\text{Structure} \rightarrow \text{Trigger} \rightarrow \text{Transmission} \rightarrow \text{Observable} \rightarrow \text{Price}}
$$

总图在 `foundations/market_transmission_map.md`。本章写链，不写“所以看多/看空人民币”。

---

## Treasury → Protocol

```text
Treasury issuance
↓
dealer absorption
↓
repo
↓
USD funding
↓
cross-currency basis
↓
global asset prices
```

Trigger 可以是供给、TGA、SOMA、监管对 dealer 资产负债表的约束。  
First observable：repo spreads、UST depth、dealer inventories。  
Price：UST yields、USD FX、全球风险资产。若 repo 没动而风险资产先动，优先怀疑认错了这条链。

---

## Dollar → HK

```text
USD funding condition
↓
HKD liquidity
↓
HIBOR
↓
HK financing
↓
property / equities / credit
```

HKD 锚住美元，不意味着 HKD 流动性自动复制 Fed。货币局把美元条件转成港元市场条件，但 Aggregate Balance、HIBOR 和本地信贷有自己的时滞和放大。

---

## China → HK

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

在岸政策先碰到 CNY，再通过可兑换性、预期和离岸头寸变成 CNH。香港在这里是离岸腿，不是中国货币政策本身。

---

## Market map

| Structure | First observable | Secondary | Asset |
|---|---|---|---|
| USD funding stress | basis / repo | CNH / HKD funding | FX / rates |
| Treasury stress | repo / depth | USD funding | UST / FX |
| HK interface strengthening | flows / CNH liquidity | spreads | HK / China assets |
| translation failure | funding spread | flows reroute | cross-asset |

Rerouting 出现时，不要只看原来的资产价格。还要看流量改道：Connect 相对其他准入、CNH 相对其他离岸人民币场所、HKD funding 相对美元直融。

---

### Research status

```text
Current conclusion:
结构必须落到 Structure → Trigger → Observable → Price。当前三条主链是 Treasury-Protocol、Dollar-HK、China-HK。

Evidence:
repo / basis / HIBOR / CNH-CNY / Connect flows 都是可独立观察的中间量。

Counterevidence:
若最终资产价格变动时，这些中间量系统性地不反应，则传导图需要重画。

Market implication:
先读第一观察，再读资产价格。本章不给出人民币或港股方向。

Watch:
core indicators 是否按链的顺序动；流量是否在压力期改道。

Falsifier:
结构冲击之后，指定的 first observable 长期沉默，只有最终价格故事。
```
