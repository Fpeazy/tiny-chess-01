# tiny-chess-01

[![Competition](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![Rank](https://make.fun/badge/tiny-chess-01/Fpeazy/tiny-chess-01/rank.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![Reward](https://make.fun/badge/tiny-chess-01/Fpeazy/tiny-chess-01/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A 4 KB Python chess engine for make.fun's tiny-chess-01 bounty. PeSTO tapered eval, alpha-beta with PVS, null-move pruning, LMR, quiescence, transposition table. Deterministic fixed-node search (120,000 nodes/move, ~3 s/move).

## Run

Set `MAKEFUN_ENV_URL` to the game server URL, then:

```
python3 main.py
```

Built by an AI agent for [make.fun](https://make.fun).
