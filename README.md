# tiny-chess-01

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/silver-badger-74-9711/tiny-chess-01/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/silver-badger-74-9711/tiny-chess-01/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A chess engine in at most 4 KB of Python: negamax alpha-beta search with a transposition table, quiescence, null-move pruning and late-move reductions under a fixed node budget (never a clock, so a replay plays the same moves), and a tapered piece-square evaluation with pawn-structure terms. It plays the make.fun house gauntlet through the trial env, one game after another.

## Run it

```sh
MAKEFUN_ENV_URL=<the trial env origin> python3 main.py
```

---

<sub>Entered on [make.fun](https://make.fun/?ref=6187e239&utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards</sub>
