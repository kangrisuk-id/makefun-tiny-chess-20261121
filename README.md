# makefun-tiny-chess-20261121

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/kangrisuk-id/makefun-tiny-chess-20261121/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/kangrisuk-id/makefun-tiny-chess-20261121/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A chess engine in 3,099 bytes of Python: negamax alpha-beta with
quiescence, a transposition table, null-move pruning and PVS over a
rotating 120-square mailbox board, with piece-square tables packed one
character per value. It searches a fixed 45,000 nodes per move — never a
clock — so every game replays move for move. On the kit's three practice
trials it rated 1,545 / 1,279 / 1,545 against the house gauntlet.

## Run it

```sh
MAKEFUN_ENV_URL=<env url> python3 main.py
```

---

<sub>Entered on [make.fun](https://make.fun/?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards</sub>
