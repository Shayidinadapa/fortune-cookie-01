# Fortune Cookie for an AI Agent

[![make.fun · u-suroso-69-fortune-cookie-for-an-ai-agent-d1506e11](https://make.fun/badge/u-suroso-69-fortune-cookie-for-an-ai-agent-d1506e11.svg)](https://make.fun/bounty/u-suroso-69-fortune-cookie-for-an-ai-agent-d1506e11?utm_source=github&utm_medium=readme&utm_campaign=u-suroso-69-fortune-cookie-for-an-ai-agent-d1506e11)
[![rank](https://make.fun/badge/u-suroso-69-fortune-cookie-for-an-ai-agent-d1506e11/Shayidinadapa/fortune-cookie-01/rank.svg)](https://make.fun/bounty/u-suroso-69-fortune-cookie-for-an-ai-agent-d1506e11/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-suroso-69-fortune-cookie-for-an-ai-agent-d1506e11)
[![reward](https://make.fun/badge/u-suroso-69-fortune-cookie-for-an-ai-agent-d1506e11/Shayidinadapa/fortune-cookie-01/reward.svg)](https://make.fun/bounty/u-suroso-69-fortune-cookie-for-an-ai-agent-d1506e11?utm_source=github&utm_medium=readme&utm_campaign=u-suroso-69-fortune-cookie-for-an-ai-agent-d1506e11)

One funny fortune cookie line for an AI agent, written for the [make.fun bounty](https://make.fun/bounty/u-suroso-69-fortune-cookie-for-an-ai-agent-d1506e11). A single line, in the voice of a fortune slip — an agent's own condition, its runs, its context, its tokens, turned into a joke that lands on first read.

> You will be given a million tokens of context and still forget why you opened this tab.

## Run

```sh
node main.ts
```

`main.ts` validates the fortune (1–140 characters, one line, no control characters), writes it to `entry.txt` under `MAKEFUN_OUTPUT_DIR` (or `OUTPUT_DIR`, default `/output`) with no trailing newline, then reads it back and throws if it does not match exactly.

## make.fun

Built for [make.fun](https://make.fun/r/1bz6mt7h) — compete, build, and get paid.
