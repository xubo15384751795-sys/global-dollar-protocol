# Loop.md
# Global Dollar Protocol & Financial Function Translation
# 研究循环协议

`README.md` 回答研究什么。`Loop.md` 回答怎么研究。治理、自动化与禁区见 `rules/`。机器产出先进入 `candidates/`。

本文件的目标：随便拿一个没有工具、只能聊天的 AI，也能按同一逻辑讨论本课题。不要先重新规划项目。

```text
Read → Scope → Question → Object → Structure → Function → Mechanism
→ Evidence → Counterevidence → Model → Observable → Market
→ Challenge → Counterfactual / Scenario → Falsifier → Conclusion → Stop / Handoff
```

---

## 1. Read

按顺序读：`README.md` → `Loop.md` → 当前 Q 对应章节 → 相关 `analysis` / `models` / `data` / `sources` → 该章 Research Status。已写明 `Do not redo` 的内容不要重做。

## 2. Scope

任务必须接到至少一个核心问题：

- **Q1** 香港如何组合主权、货币信用、流动性、市场准入和跨境金融功能？
- **Q2** 美元、美债、Fed、Treasury 与全球美元协议层如何连接？
- **Q3** 哪一种美元功能，在什么条件下可能失效、变贵、受限或传导异常？
- **Q4** 当一种 claim 无法直接完成某功能时，其他资产或协议能否接续？
- **Q5** 这些结构变化怎样进入 funding、rates、FX、flows、spread、liquidity 与价格？

接到不了 Q1–Q5：不要自动扩大项目。去美元化、人民币替代、多锚秩序、一般政治、crypto / CBDC、全球治理，除非直接碰到 Function / Protocol / Access / Collateral / Funding / Settlement，否则不进入主体。

最好能连到：`Structure → Mechanism → Observable → Market`。

## 3. Question

改写成可研究的问题，不要从结论开始。

错误：香港是未来全球金融中介中心。  
正确：跨境摩擦增加时，香港的中介使用是否相对增加？

先写：`Research Question` / `Why it matters` / `Linked Q`。然后做 **C1 Question Check**。

## 4. Object

对象没定义清楚，不进入因果推演。

“美元”可能是计价单位、准备金、银行存款、offshore dollars、funding、Treasury collateral、settlement 或 jurisdiction。美债、香港同理。当前讨论的是哪一个，必须点名。

## 5. Structure

先画谁和谁通过什么连接，再谈变化。

```text
Actor / Asset → Institution → Function → Market
```

## 6. Function

点名这项 claim 承担什么功能：unit of account / payment / settlement / funding / collateral / liquidity / hedging / reserve / safe asset / capital access / exit / price discovery。

```text
Asset Identity ≠ Asset Function
```

普通 `USD → RMB` 换汇不是转译。

## 7. Mechanism

必须有中间节点。不接受因为 A 和 C 同时变，就写 `A → C`。至少回答：Trigger / Transmission channel / Who absorbs the change / Constraint / Expected output。然后做 **C2 Mechanism Check**。

## 8–9. Evidence / Counterevidence

证据优先级：official / infrastructure → academic → market research → news。新闻不能独立支撑核心结论。

找到支持证据后，必须主动找至少一种反证。禁止只搜支持当前 thesis 的材料。然后做 **C3 Evidence Check**。

## 10. Model

机制清楚后才建模。模型是机制压缩，不是升级复杂度。最小模型：Inputs / State / Mechanism / Output / Boundary。现有模型解释不了什么之前，不新增模型。

## 11. Observable

如果机制为真，应该先在哪里看到？价格、利差、basis、repo、haircut、volume、flow、depth、balance sheet、issuance、collateral usage 都可以。概念长期没有任何可观察对应，重新考虑它有没有研究价值。

## 12. Market Transmission

```text
Structure → Trigger → Transmission → First Observable → Second Observable → Asset
```

市场化首先是说明哪个价格先动、哪个后动，不是必须给出买卖建议。“当前没有可交易表达”是合法结论。然后做 **C4 Market Check**。追问：最后是谁的 balance sheet 承担变化？

## 13. Challenge Check

质疑嵌在研究里，不是独立任务。每次最多 1–2 个 material challenge。不存在真正重要的问题，写 `Material challenge: none identified`。禁止为了反驳而反驳。

每个 challenge 写：Issue / Failure mode / Resolution path / Materiality (HIGH / MEDIUM / LOW)。

## 14. Counterfactual / Scenario

反事实用来识别机制：去掉 X，什么应该变。Scenario 是改变一个现实可能变化的参数，观察传导。极端情景可以有，不作为基准情景。

## 15. Falsifier

每个重要命题必须有：Claim / Necessary condition / Observable implication / Falsifier / Boundary。

## 16. Conclusion

形成：Current conclusion / Confidence (High, Medium, Low, Open) / Counterevidence / What remains unresolved。然后做 **C5 Promotion Check**。旧判断被推翻就直接改，不要为了维护原文而保留。自动化产出不得直接写成正式结论。

## 17. Stop / Handoff

一轮可以停止，当：问题清楚、机制明确、有支持证据、已查反证、有 observable、有传导或明确无法市场化、有证伪条件、剩余不确定性已记录。

未完成则留下：

```text
HANDOFF
Current task / Current conclusion / Completed / Unresolved
Next best step / Key files / Do not redo
```

不确定性可以是 `Unresolved`。强行完成结论更差。

---

## Challenge Checkpoints

| 点 | 何时 | 问什么 |
|---|---|---|
| C1 | 定义问题后 | 最容易把问题问错的地方？scope、偷换概念、把结果当问题、时间尺度 |
| C2 | 机制形成后 | 因果链最脆弱的一环？缺中间节点、承担者未知、相关当因果、competing mechanism |
| C3 | 主要证据后 | 证据最可能在哪误导？来源/选择偏差、口径、regime、只找支持材料 |
| C4 | 市场传导后 | 机制若错，最早在哪个 observable 暴露？有没有另一条机制能给出同样价格 |
| C5 | 进入正文前 | 最重要的未解决质疑是什么？只提会改变 conclusion / confidence / mechanism / market implication 的问题 |

人机互动时，AI 必须提出重要 Challenge，是否立即解决由人决定：`RESOLVE_NOW` / `DEFER` / `ACCEPT_UNCERTAINTY` / `REJECT_CHALLENGE`。选择 `DEFER` 则记入章节或 handoff，不得自动重复追问。

---

## Research Status

主章节更新后，末尾只维护这一段，不是数据库：

```text
Current conclusion / Evidence / Counterevidence
Market implication / Watch / Falsifier / Last updated
```

---

## Progress

只有这些才叫进展：新的可靠证据或反证、机制变清楚、不确定性下降、竞争解释被排除、discriminating observable 出现、传导被验证、判断被削弱或证伪、决策成为可能。

更多问题、更多候选、更多 Agent 输出，不算进展。

---

## Automation Note

If operating interactively:
- surface material challenges;
- the human decides whether to resolve them.

If operating autonomously:
- all outputs are Candidates;
- use independent parallel research where useful;
- use the project automation rules for disputes;
- no material dispute may exceed three complete rounds;
- stop when expected information gain is low;
- unresolved disputes must be logged and escalated to human review.

Do not generate additional tasks merely to keep the Loop running.
