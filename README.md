What is Sudoku?

Sudoku is a mental puzzle game commonly found in newspapers and has found its way into books and websites purely based on the puzzles themselves. In Sudoku your objective is to fill in a 9x9 grid this grid is divided into 9 3x3 grids, each 3x3 box must contain every number from 1-9, while every row and column must also have every number from 1-9 as well. 

In order to solve Sudoku with a computer, we shall be using a backtracking algorithm.

Backtracking Algorithm

In order to solve Sudoku in a systematic way, such that a computer can follow, we need to use a backtracking algorithm. In a simple way demonstrated in the diagram. What a backtracking algorithm does is it incrementally goes through a set of solutions until the solution is considered "incorrect" once incorrect the algorithm goes back one increment and checks the next options if also incorrect it continues to go back and if it is valid it goes forward incrementally again, this goes on into a solution appears. 

How Backtracking Solves Sudoku

What the algorithm essentially will do when solving Soduku we set the solutions that are invalid as repeated numbers in the 3x3 box, row, and column. We will have the algorithm go through each answer starting with 1 and incrementally increasing until there is an overlap in this case the backtracking will occur until a solution is found. 
