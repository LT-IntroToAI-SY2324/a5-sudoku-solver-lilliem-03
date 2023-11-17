# Assignment 5 Write up

Assignment 5 can be broken up into the following parts:
1. Import the Necessary Modules:
- `copy`: For creating deep copies of objects
- `Stack` and `Queue`: Custom implementations for DFS and BFS operations
2. Utility Functions: 
- `remove_if_exists`: Removes a specified element from a list if it exists, which is used to remove the possibilites from a cell
3. Board Class:
- Represents the Sudoku board
- Consists of functions that will find the most constrained cell, and update the board, which eliminates possible solutions
4. DFS & BFS Functions:
- `DFS`: Uses depth-first search to solve the Sudoku puzzle. It works by trying to fill the most constrained cell with potential values until a solution is found or backtracks if a mistake is made
- `BFS`: Uses breadth-first search to solve the Sudoku puzzle in a similar fashion to DFS but explores nodes level by level
5. Main Execution:
- Defines two different sets of initial moves for Sudoku puzzles
- Uses both DFS and BFS to solve each puzzle and prints the results


After completing the assignment, answer the following reflection questions:

## Reflection Questions

1. How do the performance and efficiency of the Depth-First Search (DFS) and Breadth-First Search (BFS) algorithms compare when solving Sudoku puzzles? In what scenarios might one approach be preferable over the other?
To my understanding of both of them the BFS will go through every possible option and although it may not be efficient it will make sure the correct answer is found and as for DFS it will pick a route and go through each option wich I think might sae time it may not be as efficent in some puzzles. 

2. How did the choice of data structures (like the Stack for DFS and Queue for BFS) impact the implementation and functionality of the algorithms? Are there alternative data structures or design patterns that could have been used to achieve the same objectives?
    I think the codes for stack and queue are fundamental to the algorithims and mkae tem functional by having different methods of completing the sudoku in wich one can be faster than the other. The alternatives to DFS could be lists or arrays and the alternative to BFS could be something called a linked list which can be used to implement a queue.

3. Considering the current implementation, how might the Sudoku solver be adapted or extended for larger puzzles or different types of grid-based logic games? How can the lessons learned from this assignment be applied to real-world problem-solving or optimization challenges?
    I am not really sure how it could be extended for larger puzzles, I think it may be extended by adding more to fit the parameters of something that may be harder. This can be applied to real-world problem-solving or optimization challenges by using the methods of DFS nad BFS and applying them to how people solve problems wit a multitude of options in everyday life.

