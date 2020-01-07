# Grid Navigation

This repository was an exercise to implement the A* algorithm from scratch to navigate around a two-dimensional grid with obstacles. The goal is to produce the shortest path between a provided pair of points, taking care to maneuver around the obstacles as needed. Path length is measured in Euclidean distance. Valid directions of movement include up, down, left, right, up-left, up-right, down-left, and down-right.

Please take in account that this code was written in a few days without any professional review/standard as an exercice.

## Getting Started

The file ["grid.py"](grid.py) contains all the code and A* algorithm to solve our navigation problem.

The file ["grid_gui.py"](grid_gui.py) contains a gui in order to interface with the A* algorithm and load arbitrary grids from text files as well and choose our start and goal locations.

We have 3 premade grids:

- [scene_barrier.txt](scene_barrier.txt)
- [scene_simple.txt](scene_simple.txt)
- [scene_random.txt](scene_random.txt)

We use the following format for textual scene representation: "." characters correspond to empty spaces, and "X" characters correspond to obstacles.

### Prerequisites

- [tkinter](https://docs.python.org/3/library/tkinter.html)

## Running the grid gui

You can run the gui with the following:

```[python]
python3 grid_gui.py scene_path
```

The argument scene_path is a path to a scene file storing the layout of the target grid and obstacles.

You can then use the right and left click of the mouse to choose your start and goal location.

## Authors

- **Raphael Van Hoffelen** - [github](https://github.com/dskart) - [website](https://www.raphaelvanhoffelen.com/)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.
