# Wordoku-Solver
Implement an AI agent to solve the Wordoku puzzle game. The core technique to
focus is the Constraint Satisfaction Problem (CSP). Provided three solutions, one with simple backtracking ,another with constraint propogation and the third one with Min-Conflcit search.
## Problem Statement
Wordoku is an extension of Sudoku where we have alphabets in place of digits.The Wordoku puzzle has a 9x9 grid and a set of possible alphabets
with some of the positions filled with those alphabets to ensure a
solution can be reached. The goal is to find and fill remaining cells
with alphabets such that each row, column and the 3x3 square
(sub-grid) all must contain the alphabets, exactly once.

**Note**: There are exactly nine alphabets among which one of the
characters is needed to be filled in blank space.

Reference Explanation
**[Sudoku as CSP]:**

● Every empty cell is a variable

● Domain of each variable is {1,2,3,4,5,6,7,8,9}

● Constraints:

* C1: Rows should not have duplicates
* C2: Columns should not have duplicates
* C3: 3x3 sub-grid should not have duplicates

## Results
It can be seen that the solution with constraint propogation works faster for all test cases.
