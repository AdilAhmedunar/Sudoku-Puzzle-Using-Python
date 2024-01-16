# Sudoku-Puzzle-Using-Python
Constraint Satisfaction Problem - Heuristic Algorithms

# Report On project

1. Functions:

•	print_board(board):

    	Purpose: Prints the Sudoku board in a user-friendly format. 
    	Parameters: Takes a 2D list (board) representing the Sudoku puzzle.
    	Implementation: Iterates through each row and prints the values separated by spaces.


•	is_valid (board, row, col, value):

    	Purpose: Checks if placing a given value at a specified position (row, col) in the Sudoku board is valid.
    	Parameters: Takes the Sudoku board, and the row, col, and value to be placed.
    	Implementation: Checks if the value is not present in the same row, column, or 3x3 subgrid.

•	find_empty_location(board):

    	Purpose: Finds the next empty cell (with value 0) in the Sudoku board.
    	Parameters: Takes the Sudoku board.
    	Implementation: Iterates through the board to find the first empty cell and returns its position.

•	solve_sudoku(board):

    	Purpose: Recursive backtracking function to solve the Sudoku puzzle.
    	Parameters: Takes the Sudoku board.
    	Implementation: Uses backtracking to try different values for empty cells until a solution is found.
    
2.	Global Variable:
   
•	false_probes:

    	Purpose: Counter for false probes during the Sudoku solving process.
    	Implementation: Incremented each time a wrong value is tried during the backtracking process.

3.	Example Sudoku Puzzle:
   
•	sudoku_board:

    	Purpose: An example Sudoku puzzle represented as a 2D list.
    	Implementation: 9x9 grid with initial values and empty cells (0).

4.	Sudoku Solving:
   
•	start_time and end_time:

    	Purpose: Measure the runtime duration of the Sudoku solving process.
    	Implementation: Uses the time module to record the start and end times.

•	solve_sudoku(sudoku_board):

    	Purpose: Solves the Sudoku puzzle using the solve_sudoku function.

•	Prints the Solution or No Solution:

    	Purpose: Prints whether a solution was found or not.
    	Implementation: Uses print_board to display the solved Sudoku or a message indicating no solution.

5.	Runtime Duration:
   
•	Purpose: Displays the time taken to solve the Sudoku puzzle.

•	Implementation: Calculates the time difference between start_time and end_time.

6.	Number of False Probes:
   
•	Purpose: Displays the count of false probes during the Sudoku solving process.

•	Implementation: Prints the value of the false_probes counter.

# Thank You for visiting my repository!

