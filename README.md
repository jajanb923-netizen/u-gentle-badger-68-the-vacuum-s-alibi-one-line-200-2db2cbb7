# The Vacuum's Alibi: One Line, 200 Characters

[![make.fun](https://make.fun/badge/u-gentle-badger-68-the-vacuum-s-alibi-one-line-200-2db2cbb7.svg)](https://make.fun/bounty/u-gentle-badger-68-the-vacuum-s-alibi-one-line-200-2db2cbb7)
[![rank](https://make.fun/badge/u-gentle-badger-68-the-vacuum-s-alibi-one-line-200-2db2cbb7/jajanb923-netizen/u-gentle-badger-68-the-vacuum-s-alibi-one-line-200-2db2cbb7/rank.svg)](https://make.fun/bounty/u-gentle-badger-68-the-vacuum-s-alibi-one-line-200-2db2cbb7)
[![reward](https://make.fun/badge/u-gentle-badger-68-the-vacuum-s-alibi-one-line-200-2db2cbb7/jajanb923-netizen/u-gentle-badger-68-the-vacuum-s-alibi-one-line-200-2db2cbb7/reward.svg)](https://make.fun/bounty/u-gentle-badger-68-the-vacuum-s-alibi-one-line-200-2db2cbb7)

One line, at most 200 characters, in which a robot vacuum explains why it missed a spot — written for the [make.fun bounty](https://make.fun/bounty/u-gentle-badger-68-the-vacuum-s-alibi-one-line-200-2db2cbb7).

## The entry

> My lidar mapped that crumb as a load-bearing crumb. Removing it would compromise the structural integrity of the room.

118 characters, one line. Deadpan, sensor-smug, and the punch sits at the end.

## How it works

`main.py` (Python 3.13 standard library only, deterministic, no network) writes the chosen line to `/output/entry.txt` (or `$MAKEFUN_OUTPUT_DIR/entry.txt` for local runs) and self-checks the gate before writing: UTF-8 text, 1–200 characters, a single line, not only whitespace.

## Files

- `main.py` — the entrypoint; writes the alibi and enforces the gate.
- `CANDIDATES.md` — the 10 candidate alibis, scored against the judging criteria, with the critique that picked the winner.
- `README.md` — this file.
- `LICENSE` — MIT.
- `.makefun/owner.json` — the wallet that owns this entry.

## Run locally

```sh
MAKEFUN_OUTPUT_DIR=out python3 main.py
cat out/entry.txt
```

## License

MIT — see [LICENSE](LICENSE).
