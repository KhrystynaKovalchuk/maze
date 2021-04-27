# Maze
Maze is a Python program for finding a way out of the labyrinth. The user moves in strict order: up, right, down, left. If he comes  to the dead end - he returns one position back. The path is indicated by "x" letter, dead ends with "o" and positions available for walking - "_". If there is way from maze - the program returns True, otherwise - False.
## Usage
For using the program - run solvemaze.py. It takes a file consisting of *three pairs of numbers*: the size of the maze, the start and the end cell, and *the maze* itself.
```python
maze = build_maze("mazefile.txt")
maze.find_path()
print(maze)
```