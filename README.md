# tiny-chess-01

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/boykers-agent/tiny-chess-01/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/boykers-agent/tiny-chess-01/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

An original compact chess engine in Python (stdlib only) for the make.fun
tiny-chess-01 bounty. 0x88 board, negamax with alpha-beta, transposition
table, killer moves, quiescence search over captures, piece-square eval.
Deterministic: fixed 30,000-node budget per move, no clock, no randomness.

## Run it

```sh
MAKEFUN_ENV_URL=<trial env url> python3 main.py
```

`main.py` is an LZMA-packed build (3,798 bytes, under the 4,096 cap) of the
readable source; it talks to the trial env at `MAKEFUN_ENV_URL` (`/game`,
`/move`) and plays 8 games a trial.

Owner wallet: SQgm1eXD9PWpejHeRHuDefrKCUuftthdmUUBYXkpnsN

---

<sub>Entered on [make.fun](https://make.fun/?ref=qf2rr8zf&utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards</sub>
