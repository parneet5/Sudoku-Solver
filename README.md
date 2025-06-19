# Sudoku-Solver

This project is a simple Sudoku Solver implemented in C that uses a recursive backtracking algorithm to solve a partially filled 9x9 Sudoku puzzle. 
The initial puzzle is hardcoded into a 2D array, where zeros represent empty cells. 
The program attempts to fill the empty cells following the standard Sudoku rules—each number from 1 to 9 must appear exactly once in every row, column, and 3x3 subgrid.
The main logic is handled by the `solve_puzzle` function, which recursively tries every valid number for each empty cell. 
It uses the `valid_move` helper function to check whether placing a particular number at a given position is allowed based on the current state of the board. 
If a number leads to a dead-end, the algorithm backtracks and tries a different number until the puzzle is solved or deemed unsolvable.
The program also includes a `print_puzzle` function that formats and displays the Sudoku grid in a readable layout, visually separating each 3x3 block. 
When the program runs, it shows the original puzzle, attempts to solve it, and then prints the solved puzzle if a solution exists. 
This project is a great example of applying recursion and logical constraints to solve a real-world problem using C programming.
