# Market Transmission

回答：

```text
shock
→ first market
→ transmission channel
→ second market
→ asset price
```

必须能映射回：

$$
\text{Structure} \rightarrow \text{Trigger} \rightarrow \text{Transmission} \rightarrow \text{Observable} \rightarrow \text{Price}
$$

---

## 记录格式

```text
Structure:
Trigger / shock:
First market:
Channel:
Second market:
First observable:
Price:
Reroute if broken:
```

---

## 三条默认链

**Treasury → Protocol**  
shock: issuance / TGA / dealer constraint  
first market: UST / repo  
channel: dealer absorption, collateral, USD funding  
second market: FX basis, global assets

**Dollar → HK**  
shock: USD funding  
first market: HKD liquidity / USD/HKD  
channel: currency board, Aggregate Balance  
second market: HIBOR, HK financing, property / equities / credit

**China → HK**  
shock: China policy / liquidity  
first market: CNY  
channel: convertibility, offshore positioning  
second market: CNH, Connect, HK offshore China assets

若 first observable 不动，不要用最终价格硬圆这条链。
