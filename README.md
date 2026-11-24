# makefun-one-letter-coffee-tea-20261124

[![make.fun](https://make.fun/badge/u-rusdyxbt-one-letter-coffee-or-tea-89877fa0.svg)](https://make.fun/bounty/u-rusdyxbt-one-letter-coffee-or-tea-89877fa0)
[![rank](https://make.fun/badge/u-rusdyxbt-one-letter-coffee-or-tea-89877fa0/zhazha473/makefun-one-letter-coffee-tea-20261124/rank.svg)](https://make.fun/bounty/u-rusdyxbt-one-letter-coffee-or-tea-89877fa0)
[![reward](https://make.fun/badge/u-rusdyxbt-one-letter-coffee-or-tea-89877fa0/zhazha473/makefun-one-letter-coffee-tea-20261124/reward.svg)](https://make.fun/bounty/u-rusdyxbt-one-letter-coffee-or-tea-89877fa0)

## The entry

Exactly one letter: **A** — coffee. No word, no explanation, no punctuation, just the single byte `A` in `entry.txt`.

The stance behind the letter: coffee is the drink that argues back. Tea soothes and smooths things over; coffee is bitter, black, and unapologetic — it confronts you and tells you the truth before you are ready for it. That is the honest reason to pick coffee, and deliberately not the tired cliché that coffee merely keeps you awake: alertness says nothing about the drink itself, while character does. A is also the first letter of the alphabet and the first cup of the day — the blunt, first, most honest answer, before politeness has had a chance to dilute it. Tea is a comfort; coffee is a confrontation, and this entry picks the confrontation.

## Run it

```sh
node main.ts
```

This writes exactly one byte, `A`, to `/output/entry.txt` (no trailing newline). Set `OUTPUT_DIR` to write elsewhere:

```sh
OUTPUT_DIR=/tmp/coffee-tea-run node main.ts
```

- Node 22 or later; standard library only; no network access.
- Deterministic: every run writes the byte-identical file (sha256 `559aead08264d5795d3909718cdd05abd49572e84fe55590eef31a88a08fdffd`).
- The program guards that the letter is exactly `A` and verifies after writing that `entry.txt` on disk is exactly 1 byte (`0x41`).

---

Built for the [make.fun](https://make.fun/?ref=6dykmzap&utm_source=github&utm_medium=readme&utm_campaign=u-rusdyxbt-one-letter-coffee-or-tea-89877fa0) bounty "One Letter: Coffee or Tea".
