# 04 Financial Function Translation

## 问题

当某项功能受到限制以后，能不能被另一条协议接续？

本章研究：

$$
\text{Asset}_A \xrightarrow{\text{Protocol}} \text{Function}_B
$$

关键不是设计一个新系统，而是问：

> **现实市场已经有哪些 translation-like mechanisms？**

---

## 什么算转译

一项金融 claim 通过制度或市场协议，获得它原本并不直接具备的金融功能。

算：

$$
\text{UST} \rightarrow \text{Repo} \rightarrow \text{USD Liquidity}
$$

不算：

$$
\text{USD} \rightarrow \text{RMB}
$$

普通换汇只替换余额身份。转译改变的是这项 claim 能做什么。

---

## 已有机制

```text
Repo

Collateral transformation

FX swap

Cross-currency repo

Clearing arrangement

Liquidity facility

Connect mechanism

Offshore market

Correspondent network
```

待写入的不是机制清单本身，而是每条机制：

- 输入的是哪种 identity
- 输出的是哪种 function
- cost / haircut / liquidity / access / legal constraints
- 失败时功能停在哪一层

模板见 `models/translation_protocol.md`。

---

## 中介层是否必然出现

不预设。

只有当直达更贵或不可得时，中介才值得存在：

$$
C_{\text{direct}} > C_{\text{intermediation}} + R_{\text{intermediation}}
$$

因此：

> 香港是不是中介层？

是 empirical question，不是 premise。

可能的结果有三种，都必须开着：

1. 香港持续完成某些不可替代的转译
2. 香港能做，但其他通道也能做，只是成本不同
3. 摩擦上升后，功能改道，香港接口被绕开

第 3 种是第 6 章的证伪方向。

---

### Research status

```text
Current conclusion:
转译是既有协议给 claim 接上新功能。香港是否中介层，不能从定义推出，必须看成本和替代通道。

Evidence:
UST repo、FX swap、Connect、CNH 离岸市场，都是已存在的 translation-like mechanisms。

Counterevidence:
若这些机制在功能上只是普通换汇或普通跨境投资，转译概念就是多余的。

Market implication:
看转译是否还在工作：repo haircut、FX basis、Connect 额度/流量、CNH 流动性。不要把“有接口”写成“接口一定被用”。

Watch:
$C_{\text{direct}}$ 与中介成本/风险的相对变化；替代清算和替代离岸中心是否吸收流量。

Falsifier:
功能受限后，价格和流量显示市场直接完成了原功能，转译协议既无溢价也无使用。
```
