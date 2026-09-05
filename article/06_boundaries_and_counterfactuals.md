# 06 Boundaries and Counterfactuals

反事实、压力情景和证伪边界集中在这一章。不另开文件。

目的只有一个：判断真正起作用的变量是什么，以及什么出现意味着我们错了。

---

## 1. Counterfactual

> 如果香港没有 CNH？

> 如果 HKD 不锚美元？

> 如果中国资本账户完全开放，还需要香港吗？

> 如果 Treasury 不再具有当前抵押品地位？

> 如果 USD clearing 摩擦下降，而中美制度摩擦仍然存在？

这五问分别打在：CNH 腿、美元锚、资本账户摩擦、UST 的协议功能、清算摩擦 vs 制度摩擦。

写法：每次只放松 `assumptions.md` 里的一条，看第 1 章的结构图和第 5 章的市场链哪一段会断。不要一次改所有条件。

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

美元荒放在第一项的极端端。Treasury dysfunction 放在财政层与协议层错配。Jurisdiction fragmentation 打在 access / settlement。China shock 打在 CNH 和 Connect。HK interface deterioration 直接打接口命题。

原稿里的“全球系统崩溃”只作 tail case，一笔带过，不作为主叙事。

推演模板见 `models/scenarios.md`。输出仍是“哪些功能受损、观察量应如何动”，不是价格点位。

---

## 3. Falsification

必须写清：什么出现，说明我们错了。

**H：跨系统摩擦越高，香港接口价值越高。**

这条不能永远正确。

如果：

```text
friction ↑
```

同时：

```text
HK flows ↓
CNH liquidity ↓
Connect usage ↓
```

而资金直接去了其他通道，那么：

> 香港 interface thesis 被削弱。

其他需要保持可打掉的判断：

| 判断 | 证伪信号 |
|---|---|
| 美元必须分三层 | 三层观察量无法分离 |
| UST 通过协议获得美元功能 | repo / collateral 渠道失效后，UST 仍直接等于美元流动性 |
| 转译 ≠ 换汇 | 所谓转译在数据上与普通 FX 无法区分 |
| 香港是观察功能分层的有效窗口 | HKD / CNH / USD / China access 不再同场 |

---

### Research status

```text
Current conclusion:
本章是刹车。目前最硬的证伪针对“摩擦↑ → 香港接口价值↑”。极端崩溃叙事降为 tail。

Evidence:
证伪设计依赖于流量和流动性观察量，而不是地位叙事。

Counterevidence:
若替代通道在制度上不存在，则“绕开香港”这条证伪路径本身不成立，需要另写。

Market implication:
压力期同时看香港的量和价，以及是否出现改道。量价同弱且改道成立，才是接口命题受损。

Watch:
Connect 与其他准入的相对份额；CNH 对其他离岸场所；USD clearing 摩擦与中美制度摩擦是否同向。

Falsifier:
本章列出的证伪信号出现后，正文仍把原判断写成不易证伪的结构真理。
```
