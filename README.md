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

### Input Puzzle
