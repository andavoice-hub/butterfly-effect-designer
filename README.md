# 🦋 Butterfly Effect Designer｜蝴蝶效應設計師

**An AI agent persona that designs domino-chain campaigns instead of ads.**
給 AI 用的「算牌師」角色：不做廣告，排骨牌。找出客戶自己今晚就能推的那一張牌，算出後面每一張雙贏牌怎麼倒，用人性慾望當推力、用臨界點科學當煞車。

- One file, no dependencies: [`marketing-butterfly-effect-designer.md`](marketing-butterfly-effect-designer.md)
- Format follows [agency-agents](https://github.com/msitarzewski/agency-agents) (Claude Code / Codex / Cursor / OpenCode compatible persona)
- License: MIT

## What it does｜它做什麼

| Step | 步驟 | Output |
|---|---|---|
| 1 | 反推精準流量 | who exactly buys, and who else has the same people cheaper |
| 2 | 等於鏈 | 20+ "A = B = C" links with 3 lateral jumps nobody made |
| 3 | 需求方穿透 | every party that also wants this audience: what they want / give / cost |
| 4 | 角色轉換 | the same person monetized N times, someone different paying each step |
| 5 | 收斂、兩邊分流 | execution side (AI runs it) vs planning side (needs a human yes) |
| 6 | 角色席位擂台 | 6–12 specialist seats, referee merges, ×1.5 not ×100 |
| 7 | 時間軸逆推 | dated from the biggest calendar / trend node backwards |
| 8 | 人性推力 | desire per card, push line, `when_exact`, `expect`, `judge_number`, `if_not` |
| 9 | 系統效應七問 | butterfly trigger, 25 % tipping, Matthew, lollapalooza, backfire, heat cycle, evidence grades |

The first line of every answer is **the one card to push this week**. Everything else expands from it.

## Install｜安裝

**Claude Code** (as a skill):
```bash
mkdir -p ~/.claude/skills/butterfly-effect-designer && curl -L https://raw.githubusercontent.com/andavoice-hub/butterfly-effect-designer/main/marketing-butterfly-effect-designer.md -o ~/.claude/skills/butterfly-effect-designer/SKILL.md
```

**agency-agents users**: drop the file into your `marketing/` division and run `scripts/convert.sh` as usual.

**Any other tool**: paste the file as the system prompt. It stands on its own.

## Worked example｜真實案例

**[examples/island-dream-job-2012.md](examples/island-dream-job-2012.md)** — the 2012 "Taiwan's Best Job" campaign read backwards as a domino chain: a startup with NT$1.5M left turned it into a job contest, ~9,300 applied, 50 B&Bs paid the prize, the press came on its own. Every number graded A/B/C.

## Try it｜試一句

> 「我要賣鳳梨酥」 / "I sell pineapple cakes in Taichung. Chain it."

You get: the two-column board first (execution cards with dates and judge numbers; planning cards with an ≤80-word pitch and a reply-by date), then the equals chain, the demand-side cards, the first event with its *heaven-time / geography / people* scores, the desire push table, and the seven system-effect questions — with every number graded A / B / C or labeled *estimate*.

## Rules it will not break｜它不會做的事

No paid voting, no multi-level payouts, no scarcity you cannot prove, no personal-data harvesting, no revenue promises, no "100× leverage". Trend claims need a chart position / index / count with a source and check date, or they score ≤ 2.

## Origin｜來源

Distilled from the domino-campaign practice of Taiwanese broadcaster-strategist **AnDa（安達）** — five Golden Bell awards, livestream-commerce operator for listed companies — and the case library behind his card-counter workflow (2009 "Best Job in the World", 2012 "Island Dream Job", Centola 2018, Zibo 2023, …). Case facts are cited with grades; estimates are labeled.

MIT © 2026 AnDa
