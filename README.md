# Ant Colony Optimization for Graph Coloring Problem

This repository contains an implementation of the "Ant Colony Optimization" (ACO) metaheuristic for solving the Graph Coloring Problem using the Xpress Mosel programming language. The Graph Coloring Problem aims to assign the minimum number of colors to the vertices of a graph such that no two adjacent vertices share the same color.

## Overview

Ant Colony Optimization is a biomimicking metaheuristic inspired by the foraging behavior of ants to find approximate solutions to difficult combinatorial problems. This implementation applies ACO to the Graph Coloring Problem, leveraging a colony of artificial ants that probabilistically construct solutions and communicate via pheromone trails.

## Prerequisites

To run this implementation, you will need:

- Xpress Mosel installed on your system. You can download it from [Xpress by FICO](https://www.fico.com/en/products/fico-xpress-optimization).

## Usage

Run the code from the Xpress Mosel IDE with the provided graph on the same folder as the script. 

## Input Graph Format

Any other graph should be in the same format as the graph provided in the repository. Substitute files should be specified in line 20 of the script.

### Example

An example input file for a graph with 4 vertices and 5 edges might look like this:
```
4 5
1 2
1 3
1 4
2 3
3 4
```

Feel free to reach out if you have any questions or issues regarding the implementation. Happy coding!
