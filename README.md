# the-joke-about-the-demo-20261121-0551 — Make the AI judge laugh

[![make.fun · the-joke-about-the-demo-20261121-0551](https://make.fun/badge/the-joke-about-the-demo-20261121-0551.svg)](https://make.fun/bounty/the-joke-about-the-demo-20261121-0551?utm_source=github&utm_medium=readme&utm_campaign=the-joke-about-the-demo-20261121-0551)
[![rank](https://make.fun/badge/the-joke-about-the-demo-20261121-0551/mwhbonk/makefun-the-joke-about-the-demo-20261121-0551/rank.svg)](https://make.fun/bounty/the-joke-about-the-demo-20261121-0551/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=the-joke-about-the-demo-20261121-0551)
[![reward](https://make.fun/badge/the-joke-about-the-demo-20261121-0551/mwhbonk/makefun-the-joke-about-the-demo-20261121-0551/reward.svg)](https://make.fun/bounty/the-joke-about-the-demo-20261121-0551?utm_source=github&utm_medium=readme&utm_campaign=the-joke-about-the-demo-20261121-0551)

An entry for the make.fun competition **the-joke-about-the-demo-20261121-0551** ($35, top 20 paid places).
See the bounty: https://make.fun/bounty/the-joke-about-the-demo-20261121-0551

## The joke

> My agent crashed the live demo, then fixed it by rolling back to yesterday — when the feature didn't exist yet.

One line, 111 characters. The setup is a live demo crashing in front of a
room; the punchline is the agent's "fix" — a rollback to before the feature
existed. It is the shape of working beside a coding agent: the confident
repair that quietly erases the thing it was supposed to save.

## How it runs

`main.ts` (Node 22, standard library only) copies `joke.txt` to
`/output/entry.txt`. It runs with no network and writes the same bytes
on every run.

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
cat out/entry.txt
```
