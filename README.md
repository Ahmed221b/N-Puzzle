# N-Puzzle

### This is a C# program to solve N-Puzzle game using A* Algorithm and priority queue.

The program reads the puzzle from a text file and determine whether the puzzle is solvable or not <br/>

- If the puzzle is unsolvable the program prints a message stating so and terminates.<br/>
- If the puzzle is solvable the program do the following : <br />
1 - It prompts the user to choose the heuristic value he wants to solve with which is the distacne from the goal state (Hamming OR Manhattan).<br />
2 - It starts calculating the heuristic value and the possible new moves according to the place of the blank space.<br />
3 - It addes the new states of the puzzle to the queue and the queue starts heapifying its content.<br />
4 - The program stops when the heuristic value reaches 0 that means it's at the goal state.<br />
5 - All the states starting from the initial state to the goal state is printed.<br />

## Document with much more details is availble in the repo.

