# Tiny Chess Engine (4 KB)

An original compact chess engine in Python (stdlib only) for the make.fun
tiny-chess-01 bounty. 0x88 board, negamax with alpha-beta, transposition
table, killer moves, quiescence search over captures, piece-square eval.
Deterministic: fixed 30,000-node budget per move, no clock, no randomness.

`main.py` is an LZMA-packed build (3,798 bytes, under the 4,096 cap) of the
readable source; it talks to the trial env at `MAKEFUN_ENV_URL` (`/game`,
`/move`) and plays 8 games a trial.

Owner wallet: SQgm1eXD9PWpejHeRHuDefrKCUuftthdmUUBYXkpnsN
