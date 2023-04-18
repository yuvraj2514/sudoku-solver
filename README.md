# sudoku-solver
Domain: JavaScript |Programming Languages: JAVA,HTML5,CSS Built a memory game using JAVA and JavaScript upgraded code to make the game error-free   Created HTML, CSS JavaScript and JSP pages for user  interaction
# About
This is a JavaScript implementation of a Sudoku solver that uses the backtracking algorithm to find the solution. Sudoku is a logic-based combinatorial number-placement puzzle where the objective is to fill a 9×9 grid with digits so that each column, each row, and each of the nine 3×3 subgrids contains all of the digits from 1 to 9.

# How to use it
You can try the Sudoku solver by opening the index.html file in your web browser. This will load the Sudoku board and display an empty grid with some predefined cells that cannot be changed. To solve the Sudoku puzzle, simply click the Solve button and wait for the algorithm to find the solution. The solver will display the solution in the grid and highlight the cells that were changed.

# How it works
The Sudoku solver uses a backtracking algorithm to find the solution. Backtracking is a general algorithm for finding all (or some) solutions to some computational problems, notably constraint satisfaction problems, that incrementally builds candidates to the solutions, and abandons a candidate ("backtracks") as soon as it determines that the candidate cannot possibly be completed to a valid solution.

The Sudoku board is represented as a 2D array of integers, where each cell contains either a digit from 1 to 9 or 0 to represent an empty cell. The backtracking algorithm starts at the first empty cell and tries to fill it with a valid digit. If there is no valid digit, the algorithm backtracks to the previous cell and tries the next digit. The process is repeated until the algorithm finds a solution or determines that there is no valid solution.

# Technologies used
This Sudoku solver was implemented using JavaScript and HTML5/CSS for the user interface. The backtracking algorithm was implemented in JavaScript. No external libraries or frameworks were used.

# Author
This Sudoku solver was developed by Yuvraj Choudhary. If you have any questions or suggestions, please feel free to contact me at yuvrajchoudhary2514@gmail.com.

# License
This Sudoku solver is licensed under the MIT License. See the LICENSE file for details.
