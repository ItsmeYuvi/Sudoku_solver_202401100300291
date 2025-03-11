## Sudoku_solver_202401100300291
## Sudoku Solver

## Problem Statement
Sudoku is a popular number puzzle game played on a 9x9 grid, divided into 3x3 subgrids. The goal is to fill in the grid such that:
- Each row contains the digits 1-9 without repetition.
- Each column contains the digits 1-9 without repetition.
- Each 3x3 subgrid contains the digits 1-9 without repetition.

Given a partially filled Sudoku board, the objective is to find a solution that satisfies these constraints.

## Solution Approach
This project implements a **Sudoku Solver** using the **Backtracking Algorithm**:
1. Find an empty cell in the Sudoku grid.
2. Try placing numbers 1 to 9 and check if they are valid according to Sudoku rules.
3. If a number is valid, place it and recursively attempt to solve the rest of the board.
4. If a dead-end is reached, backtrack by removing the last placed number and trying the next possibility.
5. Repeat the process until the board is completely and correctly filled.

## Features
- Uses a recursive backtracking algorithm to efficiently solve the Sudoku puzzle.
- Checks for valid placements using row, column, and subgrid constraints.
- Prints the initial and solved Sudoku board in a readable format.

## Technologies Used
Programming Language: Python
Algorithm: Backtracking

## Author
Yuvraj Singh

## License
This project is open-source and available under the MIT License.

