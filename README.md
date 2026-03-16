# Sudoku Solver Project

## Project Description

This project implements a Sudoku solver using two different algorithms: **Backtracking** and **Minimum Remaining Values (MRV)**. The goal of the project is to demonstrate how different solving strategies affect performance and efficiency when solving Sudoku puzzles.

## Features

* Solves Sudoku puzzles of different difficulty levels (Easy, Medium, Hard)
* Uses the **Backtracking algorithm**
* Uses the **MRV heuristic**
* Displays the Sudoku board in a readable format
* Compares solving times of both algorithms
* Visualizes results using a bar chart

## Algorithms Used

### Backtracking

Backtracking is a recursive algorithm that solves Sudoku by filling empty cells with numbers from 1 to 9 and checking whether the placement is valid. If a conflict occurs, the algorithm goes back and tries a different number until the puzzle is solved.

### MRV (Minimum Remaining Values)

MRV is a heuristic technique that improves solving efficiency. Instead of choosing any empty cell, it selects the cell with the **fewest possible valid numbers**, which reduces the search space and helps the solver reach the solution faster for more complex puzzles.

## Project Structure

The notebook includes the following components:

1. Sudoku board representation
2. Function for printing the Sudoku board
3. Backtracking solving algorithm
4. MRV solving algorithm
5. Execution time comparison between algorithms
6. Visualization of results using a bar chart

## Requirements

The project uses the following Python libraries:

* time
* copy
* matplotlib

## How to Run

1. Open the Jupyter Notebook file (`Sudoku.ipynb`).
2. Run all cells in order.
3. The program will:

   * Display Sudoku puzzles
   * Solve them using both algorithms
   * Measure the solving time
   * Show a comparison graph of the results

## Conclusion

This project demonstrates how different algorithms can be used to solve Sudoku puzzles. The comparison shows that **Backtracking works very efficiently for easier puzzles**, while **MRV can be more effective for harder puzzles because it reduces unnecessary guesses**. The results illustrate how heuristic techniques can improve performance in constraint satisfaction problems.

## References

* https://en.wikipedia.org/wiki/Sudoku_solving_algorithms
* https://norvig.com/sudoku.html
* https://www.geeksforgeeks.org/sudoku-backtracking-7/

## Author

Slavena Georgieva
