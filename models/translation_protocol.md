# Translation Protocol

回答：

```text
Asset A
→ Rule / Institution
→ Function B
```

以及：

```text
cost
haircut
liquidity
access
legal constraints
```

普通 `USD → RMB` 换汇不填本表。

---

## 记录格式

```text
Asset A:
Protocol:
Function B:

cost:
haircut:
liquidity:
access:
legal constraints:

fails if:
reroutes to:
```

---

## 起步清单

| Asset A | Protocol | Function B |
|---|---|---|
| UST | repo | USD liquidity / funding |
| non-UST collateral | collateral transformation | repo eligibility |
| local currency cash | FX swap | USD funding |
| local collateral | cross-currency repo | USD / HKD funding |
| claim in one CSD | clearing arrangement | settlement access |
| bank / official | liquidity facility | residual funding |
| onshore China asset | Connect | offshore market access |
| CNY identity | CNH offshore market | offshore RMB function |
| non-correspondent bank | correspondent network | USD settlement |

香港出现在哪一行，是经验填写，不是默认值。

中介值得存在的粗条件：

$$
C_{\text{direct}} > C_{\text{intermediation}} + R_{\text{intermediation}}
$$
