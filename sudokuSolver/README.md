# SOLVE THE SUDOKU USING BACKTRACKING ALGORITHM

#### BACKTRACKING ALGORITHM
- Backtracking is an algorithmic-technique for solving problems recursively by trying to build a solution incrementally, one piece at a time, removing those solutions that fail to satisfy the constraints of the problem at any point of time.


#### PROGRAM EXPLANTION
[sudoku.py](https://github.com/manis1602/pythonChallenges/blob/master/sudokuSolver/suduko.py "sudoku.py") consists of **4 functions**.
1. **printBoard(bo)**
	>- This function is used to print the **sudoku board**. 
	>- Takes one argument which is the **board**.
2. **findEmpty(bo)**
	>- This function is used to find the **empty spot** in the sudoku board where we can input the values.
	>- Takes one argument which is **board**.
3. **valid(bo,num,pos)**
	>- This function is used to check whether the number makes **conflict or not** with the row, column or in the 3x3 box in which the number is placed.
	>- Takes three argument. one is **board**, second one is **num** which is provided by user and last one is **pos** which is tuple that tells the position in the board, where the num is inputted.
4. **solve(bo)**
	>- This is the function where the **BACKTRACKING** algorithm is used to find the solution to the sudoku.
	>- Takes one argument which is **board**.
