# 03 Dollar Functional Risk

## 问题

什么才叫美元风险？

不要：

$$
\text{Dollar Risk} = \text{Dollar Collapse}
$$

也不要：

$$
\text{Dollar Risk} = \text{Dollar Shortage}
$$

而是：

> **Dollar Functional Risk：美元或美元相关资产在特定状态下无法继续完成原本承担的某项金融功能。**

---

## 拆开

```text
Fiscal risk

Monetary / liquidity risk

Funding risk

Collateral risk

Settlement risk

Jurisdiction / access risk

Balance-sheet / intermediation risk

Layer mismatch
```

每一项对应一种“原本能做、现在做不了或成本变得不可接受”的功能损失。身份可以还在。DXY 可以不崩。

- Fiscal risk：UST 作为主权负债 / 安全资产的身份或供给条件变化
- Monetary / liquidity risk：Fed 提供基础流动性的条件变化
- Funding risk：期限匹配的美元融资变得昂贵或不可得
- Collateral risk：可接受抵押品减少、haircut 上升、资格收窄
- Settlement risk：清算、交割、时点失败
- Jurisdiction / access risk：合规、制裁、账户准入、清算行退出
- Balance-sheet / intermediation risk：dealer / 银行没有能力继续做市或转译
- Layer mismatch：上述各层方向不一致

---

## 真正值得重点写的是层间错配

$$
R_{\text{interaction}}
$$

例 1：

```text
Treasury supply ↑
        ↓
dealer capacity 不足
        ↓
repo / liquidity pressure
```

财政层在供给，协议层吸收不了，货币层未必同步放松。结果是 UST 身份还在，美元融资功能受损。

例 2：

```text
Fed policy appropriate for US
        ↓
global dollar borrowers experience stress
```

货币层对美国合适，协议层对全球借款人不合适。这是美元作为全球协议货币的特有风险，不是普通主权货币的国内过热/过冷。

---

## 美元荒放在哪里

美元荒是极端 funding stress scenario。它属于 Functional Risk 的一种实现，不是全文根因。

主叙事优先写：哪一项功能、在哪一层、因何种错配而受损。只有当 funding access 全面收紧、替代协议也接不上时，才升格为美元荒。

---

### Research status

```text
Current conclusion:
美元风险应定义为功能受损，而不是崩溃或短缺。当前最值得追的是层间错配，而不是单一冲击。

Evidence:
2019 年 repo、疫情初期 UST 抛售、全球 FX basis 压力，都更接近功能/接口失灵，而不是美元身份消失。

Counterevidence:
若历史上所有美元压力都可以被单一“美元短缺”指标充分概括，则分类过细。

Market implication:
先判断受损的是 funding、collateral、settlement 还是 access，再决定看 repo、basis、UST depth 还是离岸利差。

Watch:
dealer capacity vs Treasury supply；FX basis；SRF / FIMA / swap line 使用；haircut 与抵押品资格变化。

Falsifier:
出现所谓“美元风险”时，上述功能指标均无压力，只有叙事或 DXY 波动。
```
