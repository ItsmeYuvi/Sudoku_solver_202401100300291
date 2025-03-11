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

## Example Input
The program includes a predefined Sudoku puzzle:

5 3 0 | 0 7 0 | 0 0 0
6 0 0 | 1 9 5 | 0 0 0
0 9 8 | 0 0 0 | 0 6 0
---------------------
8 0 0 | 0 6 0 | 0 0 3
4 0 0 | 8 0 3 | 0 0 1
7 0 0 | 0 2 0 | 0 0 6
---------------------
0 6 0 | 0 0 0 | 2 8 0
0 0 0 | 4 1 9 | 0 0 5
0 0 0 | 0 8 0 | 0 7 9


## Example Output (Solved Sudoku)

5 3 4 | 6 7 8 | 9 1 2
6 7 2 | 1 9 5 | 3 4 8
1 9 8 | 3 4 2 | 5 6 7
---------------------
8 5 9 | 7 6 1 | 4 2 3
4 2 6 | 8 5 3 | 7 9 1
7 1 3 | 9 2 4 | 8 5 6
---------------------
9 6 1 | 5 3 7 | 2 8 4
2 8 7 | 4 1 9 | 6 3 5
3 4 5 | 2 8 6 | 1 7 9


## Technologies Used
Programming Language: Python
Algorithm: Backtracking

## Author
Yuvraj Singh

## License
This project is open-source and available under the MIT License.

