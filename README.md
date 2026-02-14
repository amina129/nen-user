Nen Grid Pathfinder

Finds a path from top-left to bottom-right in a grid moving only right or down, where each step must go to a cell with a higher value.
How it works

    Starts at [0][0]

    At each cell, tries to move right first, then down

    Only moves if next cell's value > current cell's value

    If stuck, backtracks to try other paths

    Stops when reaching bottom-right or no moves left

