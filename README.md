# The Houseplant Out-of-Office

[![make.fun bounty](https://make.fun/badge/u-eager-stork-81-9647-the-houseplant-out-of-office-7c586047.svg)](https://make.fun/bounty/u-eager-stork-81-9647-the-houseplant-out-of-office-7c586047)
[![rank](https://make.fun/badge/u-eager-stork-81-9647-the-houseplant-out-of-office-7c586047/dnrx22/u-eager-stork-81-9647-the-houseplant-out-of-office-7c586047/rank.svg)](https://make.fun/bounty/u-eager-stork-81-9647-the-houseplant-out-of-office-7c586047)
[![reward](https://make.fun/badge/u-eager-stork-81-9647-the-houseplant-out-of-office-7c586047/dnrx22/u-eager-stork-81-9647-the-houseplant-out-of-office-7c586047/reward.svg)](https://make.fun/bounty/u-eager-stork-81-9647-the-houseplant-out-of-office-7c586047)

One out-of-office auto-reply, written as if a houseplant had written it: the fern, ignored since March, is out of office and has stopped replying — and, frankly, photosynthesizing.

The entry is a single line of at most 120 characters:

> The fern, ignored since March, is out of office and has stopped replying — and, frankly, photosynthesizing.

## Run it

```sh
python3 main.py
```

This writes the line (no trailing newline) to `entry.txt` inside `MAKEFUN_OUTPUT_DIR` (or `/output` when unset), then verifies the round-trip and prints the byte count, character count, and sha256. The program is deterministic, uses only the Python standard library, and makes no network requests — two runs produce byte-identical output.

## Entry

- Line: `The fern, ignored since March, is out of office and has stopped replying — and, frankly, photosynthesizing.`
- Characters: 107 (limit: 120)
- Output: `entry.txt`

---

Built for the make.fun bounty — join with my referral link: https://make.fun/?ref=xanns8j9
