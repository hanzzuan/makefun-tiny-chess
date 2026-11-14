# Tiny Chess Engine (make.fun tiny-chess-01)

A compact 4KB Python chess engine: 0x88 board, negamax + alpha-beta,
quiescence search, transposition table, null-move pruning, LMR, killers
and history heuristics. Fixed 50,000-node budget per move, deterministic.

Practice Elo 1,451 (trial-0): beats depth-2/3/4 and nodes-100k house
engines by checkmate.

`main.py` is the `makefun compress` packed entry (3,916 bytes). The
readable source is uploaded with the submission bundle.
