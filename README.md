# Sudoku Solver using Backtracking

This project implements a **Sudoku Solver** in Python using the **backtracking algorithm**.  
It can solve any valid Sudoku puzzle efficiently while maintaining Sudoku rules.

## Features
- Solves Sudoku puzzles of standard 9x9 size.
- Ensures each number appears only once in rows, columns, and 3×3 subgrids.
- Uses recursion and backtracking for guaranteed correctness.
- Prints both the original puzzle and the solved puzzle neatly.

## Algorithm
The backtracking approach works as follows:
1. Find an empty cell (represented by `0`).
2. Attempt to place digits **1–9** in the cell.
3. Check if the placement is valid based on Sudoku rules.
4. If valid, place the number and recursively attempt to solve the rest.
5. If no valid number fits, backtrack and try a different number.
6. Continue until the puzzle is fully solved.

## Example
| 5 | 3 | . | . | 7 | . | . | . | . |
|---|---|---|---|---|---|---|---|---|
| 6 | . | . | 1 | 9 | 5 | . | . | . |
| . | 9 | 8 | . | . | . | . | 6 | . |
| 8 | . | . | . | 6 | . | . | . | 3 |
| 4 | . | . | 8 | . | 3 | . | . | 1 |
| 7 | . | . | . | 2 | . | . | . | 6 |
| . | 6 | . | . | . | . | 2 | 8 | . |
| . | . | . | 4 | 1 | 9 | . | . | 5 |
| . | . | . | . | 8 | . | . | 7 | 9 |


### Solved Puzzle
| 5 | 3 | 4 | 6 | 7 | 8 | 9 | 1 | 2 |
|---|---|---|---|---|---|---|---|---|
| 6 | 7 | 2 | 1 | 9 | 5 | 3 | 4 | 8 |
| 1 | 9 | 8 | 3 | 4 | 2 | 5 | 6 | 7 |
| 8 | 5 | 9 | 7 | 6 | 1 | 4 | 2 | 3 |
| 4 | 2 | 6 | 8 | 5 | 3 | 7 | 9 | 1 |
| 7 | 1 | 3 | 9 | 2 | 4 | 8 | 5 | 6 |
| 9 | 6 | 1 | 5 | 3 | 7 | 2 | 8 | 4 |
| 2 | 8 | 7 | 4 | 1 | 9 | 6 | 3 | 5 |
| 3 | 4 | 5 | 2 | 8 | 6 | 1 | 7 | 9 |


### Input Puzzle
