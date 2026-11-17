# tiny-chess-01

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/HenryGits/tiny-chess-01/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/HenryGits/tiny-chess-01/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A deterministic chess engine in a single `main.py` (4,096 bytes max). 0x88 board, negamax with PVS, null-move pruning, LMR, transposition table, killer moves and quiescence search, under a fixed node budget per move (no clock, no randomness, no model calls). Eval: material, formula piece-square tables with tapered king values, bishop pair, pawn structure (passed / isolated / doubled) and king pawn shield.

`main.py` is the kit's `makefun compress` packing of `source.py` (the readable source, not committed).

## Run it

```sh
python3 main.py
```

The engine plays through the contest env at `MAKEFUN_ENV_URL`.

---

<sub>Entered on [make.fun](https://make.fun/?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards</sub>
