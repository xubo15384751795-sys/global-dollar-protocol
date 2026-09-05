# 06 Boundaries and Counterfactuals

反事实用来识别机制，不是写未来小说。Scenario 是改变一个现实可能变化的参数。极端情景可以有，不作为基准。原稿里的全球系统崩溃、IMF 2.0、全面接管，只作 tail 或 archive。

---

## 1. Counterfactual

每次只放松一条工作假设。

**如果香港没有 CNH？**  
少了一条人民币离岸定价和融资腿。香港仍可能有 HKD 和美元资金。可以识别 CNH 对接口价值的贡献是不是独立的。

**如果 HKD 不锚美元？**  
货币局转译断开。Dollar → HK 链要重画。这能识别美元锚对 HIBOR、融资和资产价格的作用。

**如果中国资本账户完全开放？**  
Connect 和离岸中介的成本优势可能下降。这是对“香港接口随摩擦而存在”的直接反事实。开放之后是否仍需要香港，看法律、清算、时区和网络，不是定义。

**如果 Treasury 不再具有当前抵押品地位？**  
UST identity 还在，repo 转译出的美元功能减弱。可以识别安全资产身份与抵押功能的分离。

**如果 USD clearing 摩擦下降，而中美制度摩擦仍在？**  
清算摩擦和制度摩擦不是同一个变量。若资金仍走香港，接口价值更可能来自法律和准入，而不是美元清算本身。

**如果把国际接口迁到深圳、香港内收？**  
这是 V0 原稿的主设计，本文只作反事实。真正的分析问题是：

> 香港的金融功能能否脱离当地法律、人才、机构和网络效应而迁移？

制度规则可以搬家。合约习惯、清算会员、人才和信任不一定同步搬家。这是经验问题，不是政策处方。原稿中的“彻底清算港英遗产”“顺从型退出”“让他们不再重要”删除，不服务 Q1–Q5。

---

## 2. Stress scenarios

只保留有研究价值的少数情景：

```text
美元融资压力
Treasury market dysfunction
jurisdiction fragmentation
China liquidity shock
HK interface deterioration
```

美元荒放在第一项的极端端。Jurisdiction fragmentation 打在 access / settlement。HK interface deterioration 直接打接口命题。

沙盒里把联邦基金利率拉到 7%、再报生存概率 80% / 60%，是设计演算，不是预测。本文不采用这些数字。有用的只是清单：funding 冲击之后，应先看到 basis/repo，再看到 HKD/CNH funding。

中日韩联合特区、沙特双锚、结构币、AI 调锚：作为“若多主权共享清算容器会怎样”的情景可以一笔带过，不进入主叙事。它们超出本文范围。

---

## 3. Falsification

**H：跨系统摩擦越高，香港接口价值越高。**

必要件：香港流动性仍够、退出仍可能、市场信任仍在。

若 friction ↑ 同时：

```text
HK flows ↓
CNH liquidity ↓
Connect usage ↓
```

且资金改道其他通道，则接口命题被削弱。允许最终是倒 U：摩擦极高时接口本身也坏掉。

其他必须可打掉的判断：

| 判断 | 证伪信号 |
|---|---|
| 美元必须分三层 | 三层观察量无法分离 |
| UST 通过协议获得美元功能 | repo/collateral 失效后 UST 仍直接等于美元流动性 |
| 转译 ≠ 换汇 | 所谓转译与普通 FX 无法区分 |
| GDP 份额下降不等于接口下降 | 接口指标与份额同比、持续塌缩 |
| 香港是有效观察窗口 | HKD / CNH / USD / China access 不再同场 |

---

### Research status

```text
Current conclusion:
最硬的证伪针对“摩擦↑ → 香港接口价值↑”。港深角色对调只保留“功能能否迁移”这一问。极端崩溃和接管方案不作为主叙事。

Evidence:
证伪依赖流量和流动性，不依赖地位叙事。

Counterevidence:
若替代通道在制度上不存在，“绕开香港”这条证伪路径本身不成立，需要另写。

Market implication:
压力期同时看香港的量和价，以及是否改道。量价同弱且改道成立，接口命题受损。

Watch:
Connect 与其他准入的相对份额；CNH 对其他离岸场所；清算摩擦与制度摩擦是否同向。

Falsifier:
列出的证伪信号出现后，正文仍把原判断写成不易证伪的结构真理。

Last updated: 2026-09-05
```
