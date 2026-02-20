🐍 Snake Maze Solver using BFS, DFS, A*, and Dijkstra

📌 Overview

This project implements an intelligent Snake game that autonomously searches for and reaches the goal in a maze while avoiding walls and obstacles.

The snake’s movement is controlled using multiple pathfinding algorithms: Breadth-First Search (BFS), Depth-First Search (DFS), Dijkstra’s Algorithm & A* Algorithm

The objective of this project is to demonstrate how classical search algorithms can be applied to grid-based environments for optimal and efficient pathfinding.

🧠 Algorithms Implemented

1️⃣ Breadth-First Search (BFS)

Explores the maze level by level.
Guarantees the shortest path in an unweighted grid.
Uses a queue data structure.

2️⃣ Depth-First Search (DFS)

Explores paths deeply before backtracking.
Does not guarantee the shortest path.
Uses a stack (or recursion).

3️⃣ Dijkstra’s Algorithm

Computes the shortest path based on cumulative distance.
Guarantees optimal path.
Uses a priority queue.

4️⃣ A* (A-Star) Algorithm

Uses a heuristic function (e.g., Manhattan distance).
More efficient than Dijkstra in most cases.
Guarantees optimal path when heuristic is admissible.

🕹 Gameplay Logic

The maze is represented as a 2D grid.

The snake starts at an initial position.

A goal position is defined inside the maze.

Walls and obstacles block movement.

The selected search algorithm computes a path.

The snake follows the computed path automatically to reach the goal.

🚀 How to Run

Clone the repository

git clone (https://github.com/saur4bbh/-Snake-Game-Maze-Solver-using-Dijkstra-BFS-DFS-Astar-Algorithms)

Navigate into the project directory

cd -Snake-Game-Maze-Solver-using-Dijkstra-BFS-DFS-Astar-Algorithms

Install dependencies

pip install -r requirements.txt

Run the game

python main.py

🔮 Future Improvements

Dynamic obstacle handling

Visual comparison of multiple algorithm exploration

Performance benchmarking metrics
