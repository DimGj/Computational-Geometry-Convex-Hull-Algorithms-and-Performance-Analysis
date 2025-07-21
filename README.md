# Computational Geometry Algorithms: Convex Hulls, Delaunay Triangulation & Voronoi Diagrams

## Overview

This repository demonstrates and analyzes key algorithms in computational geometry, focusing on convex hull computation, Delaunay triangulation, Voronoi diagrams, and linear programming for feasible regions. The project is implemented in Python using Jupyter Notebook, with visualizations and benchmarking for algorithmic performance.

## Features

- **Convex Hull Algorithms**:  
  - Incremental (Graham's Scan)
  - Gift Wrapping (Jarvis March)
  - Divide & Conquer
  - QuickHull
  - 3D Convex Hull using `scipy.spatial.ConvexHull`

- **Delaunay Triangulation & Voronoi Diagrams**:  
  - Visualization and demonstration of duality using `scipy.spatial.Delaunay` and `scipy.spatial.Voronoi`

- **Linear Programming**:  
  - Feasible region plotting and optimal solution using `scipy.optimize.linprog`

- **Benchmarking**:  
  - Runtime analysis for convex hull algorithms and geometric constructions

## Getting Started

1. **Requirements**:
    - Python 3.x
    - Jupyter Notebook
    - numpy
    - matplotlib
    - scipy

2. **Usage**:
    - Open `Convex_Hull_Analysis_Visualization.ipynb` in Jupyter Notebook.
    - Run the cells to generate random points, compute convex hulls, visualize results, and benchmark performance.

## Visualizations

- 2D and 3D convex hulls
- Delaunay triangulation and Voronoi diagrams
- Feasible region for linear programming problems

## Applications

- Computational geometry research
- Interview preparation for algorithmic roles
- Educational demonstrations

## License

This project is open source and available under the MIT License.

---