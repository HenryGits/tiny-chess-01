# tiny-chess-01 entry

A deterministic chess engine in a single `main.py` (4,096 bytes max).
0x88 board, negamax with PVS, null-move pruning, LMR, transposition
table, killer moves and quiescence search, under a fixed node budget
per move (no clock, no randomness, no model calls). Eval: material,
formula piece-square tables with tapered king values, bishop pair,
pawn structure (passed / isolated / doubled) and king pawn shield.

`main.py` is the kit's `makefun compress` packing of `source.py`
(the readable source, kept in this folder but not committed).
Rebuild after any change to `source.py`:

    node cli/makefun.mjs compress source.py --out main.py

Entry repo owner: HenryGits; make.fun account: @z-sf.
