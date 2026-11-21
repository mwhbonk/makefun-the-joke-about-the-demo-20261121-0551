# the-joke-about-the-demo-20261121-0551 — Make the AI judge laugh

An entry for the make.fun competition **the-joke-about-the-demo-20261121-0551** ($35, top 20 paid places).

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
