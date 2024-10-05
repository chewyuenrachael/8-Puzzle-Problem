# A* Search for Solving the 8-Puzzle Problem

## Overview
This repository contains an implementation of the A* search algorithm for solving the classic 8-puzzle problem. The 8-puzzle is a sliding puzzle consisting of a 3x3 grid with numbered tiles (1-8) and one empty space. The goal is to rearrange the tiles to match a given goal state by sliding them into the empty space.

This notebook provides a detailed implementation, focusing on understanding the A* search technique and the use of different heuristics to solve the problem efficiently.

## Contents
- **PuzzleNode Class**: Represents the state of the puzzle and provides methods to generate successors, evaluate costs, and determine whether the goal state has been reached.
- **Heuristics**: Two different heuristic functions are used to guide the A* search:
  1. **Misplaced Tiles Heuristic**: Counts the number of tiles that are not in their correct position.
  2. Additional heuristics may be implemented for more efficient solving.
- **A* Algorithm Implementation**: Uses the PuzzleNode class and heuristics to find the optimal solution for a given puzzle configuration.

## File Structure
- **A_star_search.ipynb**: The main Jupyter notebook containing the implementation of the A* search algorithm, explanations of heuristics, and the class definitions for the 8-puzzle.

## Requirements
To run the notebook, you will need:
- Python 3.x
- Jupyter Notebook
- Numpy

Install the required dependencies using:
```sh
pip install numpy jupyter
```

## Usage
To solve the 8-puzzle problem using this implementation:
1. Open the `A_star_search.ipynb` notebook in Jupyter.
2. Run the cells step-by-step to see how the `PuzzleNode` class is defined, and how the A* algorithm is implemented.
3. Modify the initial puzzle configuration to test different problem instances.

## Key Concepts
- **A* Search Algorithm**: A search algorithm that finds the shortest path to the goal by combining the actual cost to reach the current node and an estimated cost to the goal.
- **PuzzleNode Class**: Contains the state representation, methods to generate successors, and evaluation functions to support the A* search.
- **Heuristics**: Functions that estimate the cost to reach the goal, which are crucial for the efficiency of the A* algorithm.
