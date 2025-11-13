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

1. What are some things that you learned through this assignment? Think about the concepts of backtracking, constraint satisfaction, and search algorithms. Were there any particular challenges you faced while implementing the Board class methods or the DFS/BFS functions? How did you overcome them?
What I learned through this assignment is a more understanding of if and for loops and statements. Throughout this program we had to repeat the use of these for and if statements and loops which helps me understand the format and what more to do with them. Some challenges that I faced with the DFS/BFS functions is not knowing where ot start. I fully understand what to do and how these functions work but I don't know how to fully code yet because I don't know the python language. I used ai to help with the outline of the BFS then I slowly started to fill it in with a little help from the already done DFS.


2. How can you apply what you learned in this assignment to future programs or projects? Consider other types of problems that involve searching through possibilities, making decisions, and backtracking when those decisions don't work out. Can you think of real-world scenarios where DFS or BFS might be useful? What about other constraint satisfaction problems?
I can apply what I learned in this assignment to future programs or projects by using the same search algorithms or similar ones for other game projects like solitaire. Some types of problems that involve searching through possibilities and making decisions is any games or projects that contains certain requiremnts for something to function. If not all of the requirement are met, the program will not work. This is similar in the questions that Mr.Berg gave us before this project in the questions asking which floor a certain person belongs on, given vague instructions.


3. Explain how the Stack and Queue classes work and why they are important for DFS and BFS algorithms. Describe the difference between LIFO (Last In First Out) and FIFO (First In First Out) data structures. How does using a Stack versus a Queue change the way the search algorithm explores possible solutions? Why is one data structure better suited for depth-first search and the other for breadth-first search?
The queue class works by putting the sudokua cells in a waitig list, looking for which numbers do and don't work in order to update the possibilities of each cell and the board. It doesn't go deep into each cell. The stack class works by going very in depth in each cell looking for the correct solution. The difference between the last in first out structure is like a stack. If you stack papers on each other, the last one in the stack will be the first one seen on top and the first one to be grabbed. The First in First out structure is like a virtual stack. Its like if the stack wasn't physically real and you can grab any piece of paper in a stack from any spot. Its like grabbing the stack of papers and flipping it upside down so that it will be in order from first to last to enter the stack. Using a stack verse a Queue changes the way the search algorithm explores possible solutions is that the stack goes in very in depth and looks for the solution directly versus the queue which only finds the things that don't work and shrinking all of the possible numbers of the entire grid for all of the cells. One data structure is better suited for depth-first search and the other for breadth-first search because one takes their time in order to find the exact solution of a cell while the other goes through all of the cells and just narrows down what the solution could be.