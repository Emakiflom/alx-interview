# 0x08. Making Change

## Overview

This project involves solving the classic coin change problem, a common challenge in algorithm design. The goal is to determine the fewest number of coins needed to make a specific amount using a given set of coin denominations. This problem is fundamental in understanding both greedy algorithms and dynamic programming.

## Learning Objectives

By completing this project, you will:

- Understand and implement greedy algorithms.
- Learn the basics of dynamic programming.
- Analyze the time and space complexity of different solutions.
- Enhance problem-solving skills by breaking down a complex problem into manageable sub-problems.
- Apply Python programming skills to solve an optimization problem efficiently.

## Requirements

- **Allowed editors:** vi, vim, emacs
- **Operating system:** Ubuntu 20.04 LTS
- **Python version:** 3.4.3
- **PEP 8 style:** Your code should conform to PEP 8 style guidelines (version 1.7.x)
- **README:** A `README.md` file at the root of the project is mandatory.
- **Executable:** All files must be executable.
- **First line:** The first line of all your files should be `#!/usr/bin/python3`.
  
## Project Task

### Task 0: Change comes from within

**Objective:** Given a pile of coins of different values, determine the fewest number of coins needed to meet a given amount total.

**Prototype:** 
```python
def makeChange(coins, total):

