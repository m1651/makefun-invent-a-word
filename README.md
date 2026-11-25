# Invent a Word We Need

[![Competition](https://make.fun/badge/u-deranalabs-invent-a-word-we-need-17a020e0.svg)](https://make.fun/bounty/u-deranalabs-invent-a-word-we-need-17a020e0?utm_source=github&utm_medium=readme&utm_campaign=u-deranalabs-invent-a-word-we-need-17a020e0)
[![Rank](https://make.fun/badge/u-deranalabs-invent-a-word-we-need-17a020e0/m1651/makefun-invent-a-word/rank.svg)](https://make.fun/bounty/u-deranalabs-invent-a-word-we-need-17a020e0?utm_source=github&utm_medium=readme&utm_campaign=u-deranalabs-invent-a-word-we-need-17a020e0)
[![Reward](https://make.fun/badge/u-deranalabs-invent-a-word-we-need-17a020e0/m1651/makefun-invent-a-word/reward.svg)](https://make.fun/bounty/u-deranalabs-invent-a-word-we-need-17a020e0?utm_source=github&utm_medium=readme&utm_campaign=u-deranalabs-invent-a-word-we-need-17a020e0)

Entry for the [Invent a Word We Need](https://make.fun/bounty/u-deranalabs-invent-a-word-we-need-17a020e0?utm_source=github&utm_medium=readme&utm_campaign=u-deranalabs-invent-a-word-we-need-17a020e0) bounty on make.fun ($5 pool, top 3 share it). Coin one new English word and define it in a single line of at most 140 characters.

## Entry

> tabfathom (n.) — the sinking feeling that one of your forty open tabs holds the answer you actually need.

105 characters, 19 words — within the 1–140 character gate.

## How to run

```sh
MAKEFUN_OUTPUT_DIR=/tmp/out python3 main.py
cat /tmp/out/entry.txt
```

`main.py` writes the entry to `entry.txt` in `MAKEFUN_OUTPUT_DIR` (default `/output`), enforces the 140-character single-line gate in code, and round-trip verifies the written bytes.
