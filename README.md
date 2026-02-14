Nen Grid Pathfinder 🔮

A simple CLI tool to find valid paths through a Nen energy grid (inspired by Hunter x Hunter).
Rules

    Start at top-left [0][0]

    Reach bottom-right [rows-1][cols-1]

    Move only → right or ↓ down

    Each step must go to a cell with HIGHER energy than current

Quick Start
bash

python nen_grid.py

Example
text

╔════════════════╗
║  NEN GRID      ║
╚════════════════╝

  [1][2][3]
  [4][5][6]
  [7][8][9]

--------------------
✅ PATH FOUND!

Path:
  (0,0)=1 → (0,1)=2 → (0,2)=3 → (1,2)=6 → (2,2)=9

How it works

    Prints the grid

    Tries to find a valid path (greedy: right first, then down)

    Backtracks if stuck

    Shows result

