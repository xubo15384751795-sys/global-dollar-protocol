# 01 Hong Kong Structure

## 问题

香港究竟是一种怎样的金融结构？

不是评价香港重要不重要，也不先问它是不是中介层。先把层拆开。

---

## 结构

```text
Hong Kong
│
├── Sovereign / legal layer
│
├── HKD
│   └── USD anchor
│
├── CNH
│   └── RMB sovereign origin
│
├── USD market
│
├── equity / bond market
│
├── Connect infrastructure
│
└── clearing / collateral / funding
```

核心问题有两个：

> HKD 的主权层、信用锚、流动性和市场形成为什么可以部分分离？

> CNH 为什么又构成另一种不同的组合？

---

## HKD：身份与锚可以分开

HKD 的法律身份在香港。信用锚在美元。流动性由货币局、Aggregate Balance、贴现窗和银行体系共同形成。市场定价则落在 USD/HKD、HIBOR 和本地信贷/资产价格上。

这是 P2 的第一处实例：issuer、denomination、anchor、liquidity currency 不必重合。

待写入：货币局规则、Convertibility Undertaking、HKMA 资产负债表、港元市场如何在美元锚下产生自己的利率。

---

## CNH：另一种组合

CNH 的主权信用来自中国，交易和清算主要在香港，与在岸 CNY 分隔。它不是 HKD 的镜像，也不是“离岸美元的人民币版”。它是另一组 identity / function 搭配：

- 身份：人民币
- 场所：香港离岸市场
- 功能：离岸融资、套保、贸易结算、与 Connect / 中资资产定价相连

待写入：CNH 市场结构、CNH HIBOR、CNH–CNY 分隔为何能持续。

---

## 香港制度接口

原稿已提出：香港连接国际美元清算、中国资本账户和国际金融监管/法律框架。这个直觉保留。

但把下列判断全部降级为待验证命题：

- 香港是全球唯一接口
- 香港必然是中介层
- 摩擦越高，香港价值越高

最后一条尤其不能当公理。它的证伪条件在第 6 章。

---

## 本章必须落到市场

```text
HKD
HIBOR
Aggregate Balance

CNH
CNH HIBOR
CNH-CNY spread
USD/CNH

Connect flows
HK equity
China offshore credit
```

没有这些观察量，结构描述就停在制度图。

---

### Research status

```text
Current conclusion:
香港是多层身份并存的金融结构：HKD 锚美元，CNH 源自中国主权信用，USD funding 与中国市场接口同场。是否构成中介层，尚未判定。

Evidence:
货币局、CNH 清算、Connect 和美元银行业务在制度上同时存在。

Counterevidence:
若 HKD 市场已与美元锚脱钩运行，或 CNH 的主场已不在香港，则本章结构图失效。

Market implication:
先盯 HIBOR、Aggregate Balance、CNH-CNY spread、USD/CNH 和 Connect flows，不先对港股/人民币做方向判断。

Watch:
USD/HKD 是否仍在 CU 区间；CNH 流动性是否仍集中在香港；Connect 是否仍是主要准入通道。

Falsifier:
摩擦上升的同时，HK flows、CNH liquidity、Connect usage 下降，且资金改走其他通道。
```
