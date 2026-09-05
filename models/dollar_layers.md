# Dollar Layers

用途：把一个问题、冲击或市场现象分到哪一层。不预测价格。

```text
Fiscal
Monetary
Protocol
```

$$
\text{USD} = \text{Fiscal} + \text{Monetary} + \text{Global Protocol}
$$

---

## 分类

| Layer | 典型对象 | 不是这一层 |
|---|---|---|
| Fiscal | Treasury issuance, TGA, UST identity, fiscal deficit | Fed 政策利率 |
| Monetary | IORB, SOFR 走廊, 准备金, QT/QE, 流动性设施 | 全球 FX swap 需求 |
| Protocol | repo, FX swap, correspondent banking, clearing, collateral eligibility, offshore dollars, jurisdiction | 美国税收 |

一条观察可以同时碰到两层。这时不要强行归到一层，标成 mismatch。

---

## 使用

1. 先写事件属于哪一层。
2. 再问另外两层有没有同步。
3. 不同步 → 交给 `functional_risk.md` 的 $R_{\text{interaction}}$。
4. 若功能改走另一条协议 → 交给 `translation_protocol.md`。
