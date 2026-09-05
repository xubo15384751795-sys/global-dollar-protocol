# Market Transmission Map

全文统一用这一条链。结构讨论若不能接到这条链，就还停留在概念层。

$$
\boxed{\text{Structure} \rightarrow \text{Trigger} \rightarrow \text{Transmission} \rightarrow \text{Observable} \rightarrow \text{Price}}
$$

本页是总图。展开分析在 `article/05_market_pricing_and_rerouting.md` 和 `models/market_transmission.md`。

---

## 三条主链

### Treasury → Protocol

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

第一观察：repo、dealer inventories、UST depth。  
第二观察：USD funding premium、FX basis。  
资产：UST、USD FX、全球风险资产。

### Dollar → HK

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

第一观察：USD/HKD、Aggregate Balance、HIBOR。  
第二观察：HK 贷款、股市融资条件。  
资产：HKD rates、HK equities、property、credit。

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

第一观察：CNH–CNY spread、CNH HIBOR、USD/CNH。  
第二观察：Connect flows、离岸信用、港股中资资产。  
资产：CNH、HK/China equities、offshore credit。

---

## Market map

| Structure | First observable | Secondary | Asset |
|---|---|---|---|
| USD funding stress | basis / repo | CNH / HKD funding | FX / rates |
| Treasury stress | repo / depth | USD funding | UST / FX |
| HK interface strengthening | flows / CNH liquidity | spreads | HK / China assets |
| translation failure | funding spread | flows reroute | cross-asset |

---

## 使用规则

- 先点名 Structure，再点 Trigger。不要从价格倒推故事。
- First observable 必须比最终资产价格更靠近机制。
- 若第一观察没动、价格先动，优先怀疑认错了 Structure。
- 本章不输出“看多/看空人民币”。最多说功能约束进入了哪一组价格。
