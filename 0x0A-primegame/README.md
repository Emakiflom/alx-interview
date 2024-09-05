# 0x0A. Prime Game

## Overview

This project focuses on solving a competitive game scenario involving prime numbers. Maria and Ben are playing a game in which they take turns choosing a prime number from a set of consecutive integers and removing the prime and its multiples from the set. The game ends when one player cannot make a valid move. The objective of the project is to determine the winner of multiple rounds of the game based on optimal play.

## Concepts Needed

### Prime Numbers
- Understanding what prime numbers are.
- Efficient algorithms to find prime numbers in a range.

### Sieve of Eratosthenes
- An efficient algorithm for finding all prime numbers up to a given limit.

### Game Theory
- Basic principles of turn-based games.
- Strategy optimization to win the game.

### Dynamic Programming / Memoization
- Reusing previous computations to optimize future calculations.

### Python Programming
- Implementing loops, conditional logic, and algorithms to manage the game state.

## Learning Objectives

By the end of this project, you should be able to:
- Implement an efficient algorithm to find prime numbers.
- Apply game theory concepts to develop an optimal strategy.
- Write Python functions to simulate the game and determine the winner.
- Utilize dynamic programming or memoization techniques to improve the efficiency of your solution.

## Requirements

- **Language:** Python 3 (version 3.4.3)
- **OS:** Ubuntu 20.04 LTS
- **Code style:** PEP 8 (version 1.7.x)
- **Execution:** All files must be executable.
- **Project structure:**
  - A `README.md` file at the root of the project folder is mandatory.
  - The first line of all Python scripts should be `#!/usr/bin/python3`.
  - You cannot import any external packages.

## Problem Description

Maria and Ben take turns choosing prime numbers from a set of consecutive integers, starting from 1 to `n`. Each time a prime number is chosen, that prime and its multiples are removed from the set. The player who cannot make a valid move loses the game.

The game is played for `x` rounds, with each round having a different value of `n`.

### Function Prototype

```python
def isWinner(x, nums)

