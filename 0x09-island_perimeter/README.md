# 0x09. Island Perimeter

## Overview

In this project, you will solve the "Island Perimeter" problem using a 2D grid representation. The goal is to calculate the perimeter of a single island in a grid, where the grid is represented by a 2D list of integers. The challenge involves applying your understanding of 2D arrays, iterating through matrices, and using conditional logic to determine the contribution of each land cell to the island’s perimeter.

## Learning Objectives

By completing this project, you will:

- Learn how to navigate and manipulate 2D arrays (matrices) in Python.
- Understand how to implement conditional logic to determine cell properties within a grid.
- Develop an algorithm to efficiently calculate the perimeter of an island in a 2D grid.
- Practice writing efficient Python code that adheres to the PEP 8 style guide.

## Requirements

- **Allowed editors:** vi, vim, emacs
- **Operating system:** Ubuntu 20.04 LTS
- **Python version:** 3.4.3
- **PEP 8 style:** Your code should conform to PEP 8 style guidelines (version 1.7).
- **README:** A `README.md` file at the root of the project is mandatory.
- **Executable:** All files must be executable.
- **First line:** The first line of all your files should be `#!/usr/bin/python3`.
- **Modules and Functions:** All modules and functions must be documented.

## Project Task

### Task 0: Island Perimeter

**Objective:** Create a function `def island_perimeter(grid):` that calculates the perimeter of the island described in the `grid`.

**Parameters:**

- `grid` is a list of list of integers:
  - `0` represents water.
  - `1` represents land.
  - Each cell is square with a side length of 1.
  - Cells are connected horizontally/vertically (not diagonally).
  - The grid is rectangular, with its width and height not exceeding 100.
  - The grid is completely surrounded by water.
  - There is only one island (or nothing).
  - The island does not contain "lakes" (water inside that isn't connected to the water surrounding the island).

**Return:**

- The function should return an integer representing the perimeter of the island.

**Example:**
```python
#!/usr/bin/python3
"""
0-main
"""
island_perimeter = __import__('0-island_perimeter').island_perimeter

if __name__ == "__main__":
    grid = [
        [0, 0, 0, 0, 0, 0],
        [0, 1, 0, 0, 0, 0],
        [0, 1, 0, 0, 0, 0],
        [0, 1, 1, 1, 0, 0],
        [0, 0, 0, 0, 0, 0]
    ]
    print(island_perimeter(grid))  # Output: 12

