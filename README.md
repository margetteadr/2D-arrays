# Grid Analyzer
A Java program using only 2d arrays.

# Project Title
2D Array Analysis System

# Student Name
Margette, 11G3

# Description of System
This program performs various operations on a 2D array (grid). It allows the user to interact with the system through a menu and execute different functions such as displaying the grid, calculating row and column sums, finding maximum and minimum values, detecting patterns, validating inputs, and performing transformations like transpose and subgrid analysis. The program continues running until the user chooses to exit.

# Explanation of Algorithms
The program uses nested loops to process the 2D array. Row and column sums are calculated by iterating through each element. The maximum and minimum values are found by comparing elements while traversing the grid. Frequency counting is done by checking how often values appear. Pattern detection uses conditional statements to identify specific arrangements. Validation ensures correct input. Transformations such as transpose swap rows and columns. Subgrid analysis uses selected indices to calculate values within a portion of the grid.

# Sample Output
MENU:
1. Display Grid
2. Row & Column Sums
3. Max & Min
4. Frequency
5. Pattern Detection
6. Boundary & Diagonals
7. Validation
8. Transformations
9. Subgrid
10. Exit

Enter your choice: 1

1 2 3
4 5 6
7 8 9

Enter your choice: 8

Transposed Grid:
1 4 7
2 5 8
3 6 9

Enter your choice: 9

Enter start row: 1
Enter end row: 2
Enter start column: 1
Enter end column: 2

Subgrid sum: 28
Subgrid max: 9

# Challenges Faced
- Understanding how to use 2D arrays and loops
- Solving logical errors in algorithms
- Dealing with user input correctly
- Managing multiple methods within one program
- Implementing transformations and subgrid operations
- Ensuring the menu system runs smoothly without errors
