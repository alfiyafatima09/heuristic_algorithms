# Pathfinding Algorithm Comparison Visualization

This project compares different pathfinding algorithms using a grid-based system. It provides visualizations to compare the paths taken by three popular algorithms: A*, Greedy Best-First, and Hill Climbing. The project also includes performance metrics, such as nodes explored, memory usage, and execution time, allowing users to easily analyze the strengths and weaknesses of each algorithm.

## About

Pathfinding is a key problem in artificial intelligence and robotics. It involves finding the most efficient route from a starting point to a goal point while avoiding obstacles. This project visualizes the paths taken by three widely used pathfinding algorithms:

- **A\***: A search algorithm that finds the shortest path by considering both the cost to reach a node and the estimated cost to the goal.
- **Greedy Best-First**: A search algorithm that uses a heuristic to estimate the best path to the goal but does not consider the cost to reach the current node.
- **Hill Climbing**: A local search algorithm that iteratively moves toward the goal by selecting the best neighbor (next step) based on a heuristic, though it can get stuck in local minima.

This project visualizes the grid, compares the paths taken by each algorithm, and provides performance metrics for better understanding.

## Features

- **Path Visualization**: Visualizes the grid and the paths taken by each algorithm.
- **Performance Metrics**: Compares the number of nodes explored and memory usage for each algorithm.
- **Execution Time**: Compares the time taken by each algorithm to find a path.
- **Interactive**: Easy-to-understand and interactive visualizations using `matplotlib`.

## Getting Started

To get started with this project, you'll need to have Python and the necessary libraries installed. Follow the steps below to run the project locally.

### Prerequisites

- Python 3.x
- pip (Python package installer)

### Installing Dependencies

You can install the required libraries using `pip`:

```bash
pip install matplotlib numpy
