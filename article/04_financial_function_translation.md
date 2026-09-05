# 04 Financial Function Translation

## 问题

当某项功能受到限制以后，能不能被另一条协议接续？

```text
Asset_A --[Protocol]--> Function_B
```

不设计新系统。问现实市场已经有哪些 translation-like mechanisms，以及中介是否值得存在。

---

## 1. 什么算转译

一项金融 claim 通过制度或市场协议，获得它原本并不直接具备的金融功能。

算：UST → repo → USD liquidity。  
不算：普通 USD → RMB 换汇。

换汇只替换余额身份。转译改变这项 claim 能做什么：证券变成融资，离岸余额变成在岸入口，本地货币余额经货币局变成美元可兑换性。

原稿用“信用转译器”“制度 NAT 网关”“信用路由器”指同一类现象。比喻可以留在解释里。论证必须落到协议、成本、haircut、准入和法律约束。任何核心比喻若无法映射到机制或 observable，不得承担关键论证。

---

## 2. 已有机制

```text
Repo
Collateral transformation
FX swap / cross-currency swap
Cross-currency repo
Clearing arrangement
Liquidity facility
Connect
Offshore CNH market
Correspondent network
```

香港出现在其中若干条上，是经验填写，不是默认值。

对每条机制要能回答：输入哪种 identity，输出哪种 function，cost / haircut / liquidity / access / legal constraints，失败时功能停在哪一层。

港币是转译的清晰例子：HKD 身份不是美元，货币局协议把它接到美元可兑换和美元锚。CNH 是另一例：人民币身份，离岸协议形成另一套定价、融资和套保功能，不等于在岸 CNY。Connect 是市场准入转译，不是换汇。

---

## 3. 中介不是前提

不预设市场必然产生中介层，也不预设香港必然是中介。

```text
仅当 C_direct > C_intermediation + R_intermediation
中介才有经济理由。
```

三种结果都开着：

1. 香港持续完成某些替代成本更高的转译  
2. 香港能做，其他通道也能做，只是成本不同  
3. 摩擦上升后功能改道，香港被绕开

第 3 种是第 6 章的证伪方向。

原稿“全球资本无法拒绝的诱惑”“只要一个市场陷落，剩下的就会向中国靠拢”“只要中国接得住一个锚，全球资本就不会溃散”，都把 A 写成必然的 C。补上中间节点之后，它们最多是条件假说：

```text
若直接美元融资或清算摩擦上升
且香港/CNH 等路径仍有流动性、法律可达性和退出能力
则部分资金会重新评估这些中介路径。
资金是否迁移，用 flow、funding cost、市场深度验证。
```

谁吸收变化：在港银行、dealer、清算行、Connect 中介的资产负债表。答不出承担者，传导链还没走完。

---

### Research status

```text
Current conclusion:
转译是既有协议给 claim 接上新功能。香港是否中介层，不能从定义推出。

Evidence:
UST repo、FX swap、货币局、CNH、Connect 都是已存在的 translation-like mechanisms。

Counterevidence:
若这些机制在数据上与普通换汇或普通跨境投资无法区分，转译概念多余。

Market implication:
看转译是否还在工作：repo haircut、FX basis、Connect 流量、CNH 流动性。有接口 ≠ 接口被用。

Watch:
C_direct 与中介成本/风险的相对变化；其他清算和离岸中心是否吸收流量。

Falsifier:
功能受限后，市场直接完成原功能，香港协议既无溢价也无使用。

Last updated: 2026-09-05
```
