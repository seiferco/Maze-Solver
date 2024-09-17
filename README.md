# Maze Solver
This project implements a Maze Solver using Breadth-First Search (BFS) to find the shortest path from a starting position to a destination in a maze. The maze is represented as a 2D grid, where open paths are marked with '-' and walls or barriers are marked with '#'.

## Problem Description
Given a maze represented as a 2D grid, and specified starting and ending positions, the goal is to find the shortest path from the start to the destination. The path should avoid walls and should be the minimum number of steps.

#### Example
For the input maze:
[    ['-', '-', '-', '-'],
    ['-', '-', '#', '-'],
    ['-', '#', '-', '-'],
    ['-', '-', '-', '-'],
    ['-', '#', '-', '-']
]

Starting at position (0, 0) and aiming to reach (4, 3), the output would be the list of positions representing the shortest path.

## How to Run
To run the script, simply execute the following into your terminal: python puzzle.py 

## License
This project is licensed under the MIT License.
