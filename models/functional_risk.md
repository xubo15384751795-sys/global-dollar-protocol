# Functional Risk

输入状态，输出哪些功能受损。不输出价格预测。

---

## Inputs

```text
fiscal state
Fed state
funding state
collateral state
jurisdiction state
intermediary capacity
```

## Outputs

```text
哪些功能受损？
受损发生在哪一层？
是否是层间错配？
是否已接近极端 funding stress？
```

---

## 功能清单

| Function | 受损看起来像什么 |
|---|---|
| Fiscal / safe-asset | UST 身份或供给条件变化，安全资产功能动摇 |
| Monetary liquidity | 准备金/设施不能按需提供基础流动性 |
| Funding access | 期限匹配的美元融资变贵或断掉 |
| Collateral eligibility | haircut 上升、资格收窄、可质押资产不足 |
| Settlement access | 清算、交割、时点失败 |
| Jurisdiction / access | 账户、合规、制裁、清算行退出 |
| Intermediation | dealer / 银行无法继续做市或转译 |

美元荒 = funding access 全面受损，且替代转译也接不上。它是输出的极端值，不是默认输入。

---

## 层间错配

$$
R_{\text{interaction}}
$$

常见组合：

```text
fiscal supply ↑  +  intermediary capacity 不足
Fed 对美国合适  +  全球 funding state 紧张
collateral 仍合格  +  settlement / jurisdiction 受阻
```

先填六项输入，再标受损功能。不要从 DXY 倒推。
