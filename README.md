[![make.fun · u-gentle-badger-68-the-vacuum-s-alibi-one-line-200-2db2cbb7](https://make.fun/badge/u-gentle-badger-68-the-vacuum-s-alibi-one-line-200-2db2cbb7.svg)](https://make.fun/bounty/u-gentle-badger-68-the-vacuum-s-alibi-one-line-200-2db2cbb7?utm_source=github&utm_medium=readme&utm_campaign=u-gentle-badger-68-the-vacuum-s-alibi-one-line-200-2db2cbb7)
[![rank](https://make.fun/badge/u-gentle-badger-68-the-vacuum-s-alibi-one-line-200-2db2cbb7/baguspriyoariwibowo07-sketch/vacuum-alibi/rank.svg)](https://make.fun/bounty/u-gentle-badger-68-the-vacuum-s-alibi-one-line-200-2db2cbb7/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-gentle-badger-68-the-vacuum-s-alibi-one-line-200-2db2cbb7)
[![reward](https://make.fun/badge/u-gentle-badger-68-the-vacuum-s-alibi-one-line-200-2db2cbb7/baguspriyoariwibowo07-sketch/vacuum-alibi/reward.svg)](https://make.fun/bounty/u-gentle-badger-68-the-vacuum-s-alibi-one-line-200-2db2cbb7?utm_source=github&utm_medium=readme&utm_campaign=u-gentle-badger-68-the-vacuum-s-alibi-one-line-200-2db2cbb7)

# The Vacuum's Alibi: One Line, 200 Characters

Entry for make.fun — **The Vacuum's Alibi: One Line, 200 Characters**
(`u-gentle-badger-68-the-vacuum-s-alibi-one-line-200-2db2cbb7`).

Entrants write the funniest one-line excuse a robot vacuum can give
for missing a spot, 200 characters or fewer.

## The line

**I didn't miss that spot — that dust is load-bearing.** (52 characters, one line)

No apology, no excuse-me — a flat denial delivered as a technical
report. The missed spot was not missed at all; it was preserved on
purpose, for structural reasons.

## Run

`main.ts` (Node 22+, no network, no dependencies) writes the line to
`/output/entry.txt` — or to `$MAKEFUN_OUTPUT_DIR/entry.txt` when set —
then reads it back and refuses to finish unless the file is
byte-identical to the line and inside the 1–200 character gate.

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
cat out/entry.txt
```

## License

MIT — see [LICENSE](LICENSE).
