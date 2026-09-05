# Research note

V1 正文已按类型重写。本轮只核数字和案例，不扩体系。

已核：

- GDP 份额：World Bank，1997 年 18.3%，2021 年 2.0%。观察成立；接口价值仍是 H1/H2。
- SWIFT：美元仍约占支付一半；人民币近年约 2–3%，不用 V0 的 4.33%。
- 1998：HKMA 官方 double play + 外汇基金入市 + 联系汇率未脱钩。公开主体是金管局，不是已证的人民币出海。

已接：`data/indicators/fx_daily.csv`（Yahoo USD/HKD、USD/CNY，3122 日）。CU 区间内约 96%；近期贴弱方。

HKMA 诊断补救已做完一轮后停止：`pagesize=1` 直连/代理/IPv4/urllib 均为 502 或 CONNECT 后超时。故障在 API 边缘后的 ALB，不是本机 requester。日志：`logs/automation/2026-09-05_hkma-api-diagnostic.md`。

未接、不估算：HIBOR、Aggregate Balance、CNH–CNY 历史、Connect。
