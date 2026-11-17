# tiny-chess-01

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/ming35753-g/tiny-chess-01/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/ming35753-g/tiny-chess-01/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A 4 KB Python chess engine: 0x88 board, alpha-beta negamax with a transposition table, killer moves, MVV-LVA ordering, quiescence search, null-move pruning, late-move reductions and check extensions, and a piece-square-table evaluation with a tapered king term. Iterative deepening under a fixed 100,000-node budget per move; deterministic, Python 3.13 stdlib only. Practice Elo ~1422 across the kit's three practice gauntlets (vs the sunfish house baseline at ~1365).

## Run it

```sh
python3 main.py
```

The engine is driven by the make.fun environment server (it reads `MAKEFUN_ENV_URL`); `main.py` is the packed entrypoint and `engine.py` is the readable source it was compressed from. The piece-square tables follow the formula-based evaluation in the competition kit's house engine (MIT).

---

<sub>Entered on [make.fun](https://make.fun/?ref=z4yv0914&utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards</sub>
