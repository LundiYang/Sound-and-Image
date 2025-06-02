# Sound-and-Image/Root
    ├── README.md            (Main Readme for the entire project)
    ├── /Week-01-Task
    │   ├── README.md        (Week 1 Readme with documentation)
    │   ├── Week-01-Sketch.pde
    │   └── /           (If applicable, any data files used in the sketch)
    ├── /Week-02-Task
    │   ├── README.md        (Week 2 Readme with documentation)
    │   ├── Week-02-Sketch.pde
    │   └── //Graph-Tree-Structures
               ├── README.md
               ├── graph.py
               ├── directed_graph.py
               ├── tree.py

    └── /Week-03-Task
        ├── README.md        (Week 3 Readme with documentation)
        ├── Week-03-Sketch.pde
        └── /data
week 2
# Graph and Tree Data Structures

This repository demonstrates the implementation of different types of graphs and trees. It includes:
- Simple Graph
- Multigraph
- Directed Graph
- Tree (with basic operations)

## Directory Structure

- **`graph.py`**: Implements a simple undirected graph.
- **`directed_graph.py`**: Implements a directed graph.
- **`tree.py`**: Implements a basic tree structure.

## Requirements

- Python 3.x

## Usage

### Simple Graph

```python
from graph import Graph

graph = Graph()
graph.add_edge(1, 2)
graph.add_edge(2, 3)
print(graph.adj_list)  # {1: [2], 2: [1, 3], 3: [2]}


week 3
# Initialize a Git repository
git init

# Add all files to staging
git add .

# Commit the changes
git commit -m "Initial commit with priority queue and graph implementations"

# Link your local repository to GitHub
git remote add origin https://github.com/yourusername/Graph-PriorityQueue.git

# Push to GitHub
git push -u origin master
