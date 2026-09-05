# USD/HKD vs Convertibility Undertaking band

Linked Q: Q1 / Q5. First observable on Dollar → HK, not a peg-break story.

## Source

Yahoo Finance daily close `HKD=X` / `CNY=X`, 2014-09-07 至 2026-09-05，n=3122。  
不是 HKMA 官方定盘。CU 区间 7.75–7.85 自 2005 年起适用。系列写入 `data/indicators/fx_daily.csv`。

HIBOR、Aggregate Balance：2026-09-05 对 HKMA 三 endpoint 做了一次诊断补救（最小 GET、直连/代理、IPv4、urllib），均为 502 或超时。见 `logs/automation/2026-09-05_hkma-api-diagnostic.md`。不估算。

CNH–CNY、Connect：Yahoo 无 CNH 历史；HKEX 无直接 CSV。未编造。

## Observation

| | n | share |
|---|---|---|
| inside 7.75–7.85 | 3004 | 96.2% |
| strong side < 7.75 | 107 | 3.4% |
| weak side > 7.85 | 11 | 0.4% |

最近报价约 7.841，靠近弱方。2015–2016 更靠近强方；2018–2019、2022–2023 更靠近弱方。

## Interpretation

联系汇率在样本里几乎一直停在兑换保证区间内。有信息的不是“锚断了没有”，而是汇率贴在哪一侧：贴近 7.75 更像美元流入/港元需求；贴近 7.85 更像港元流动性偏紧。这与第 5 章“先看 USD/HKD 和 HIBOR，再看港股”一致。

## What this does not prove

不能单独证明接口价值，也不能代替 HIBOR / Aggregate Balance。CNH–CNY 本轮没有历史序列，China → HK 链仍缺第一观察。
