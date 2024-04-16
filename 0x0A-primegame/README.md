# Prime Game

## Table of Contents

- [Introduction](#introduction)
- [Concepts Needed](#concepts-needed)
- [Resources](#resources)
- [Additional Resources](#additional-resources)
- [Requirements](#requirements)
- [Tasks](#tasks)
- [Example](#example)
- [Repository](#repository)
- [Copyright](#copyright)

## Introduction

This project involves solving a competitive game scenario where two players strategically remove prime numbers and their multiples from a set of consecutive integers. The challenge is to determine the winner of each game based on optimal play.

## Concepts Needed

- Prime Numbers:
  - Understanding prime numbers.
  - Efficient algorithms for identifying prime numbers within a range.
- Sieve of Eratosthenes:
  - An efficient algorithm for finding all prime numbers up to a given limit.
- Game Theory:
  - Basic principles of competitive games and optimal play strategies.
- Dynamic Programming/Memoization:
  - Using previous results to speed up future calculations.
- Python Programming:
  - Loops, conditional statements, arrays, and lists.

## Resources

- [Khan Academy: Prime Numbers](https://www.khanacademy.org/computing/computer-science/cryptography/comp-number-theory/v/prime-numbers-introduction)
- [Sieve of Eratosthenes in Python](https://www.geeksforgeeks.org/sieve-of-eratosthenes/)
- [Game Theory Introduction](https://www.investopedia.com/terms/g/game-theory.asp)
- [Dynamic Programming with Python Examples](https://realpython.com/python-dynamic-programming/)
- [Python Lists](https://docs.python.org/3/tutorial/datastructures.html)

## Additional Resources

- Mock Technical Interview

## Requirements

### General

- Allowed editors: vi, vim, emacs
- All files interpreted/compiled on Ubuntu 20.04 LTS using python3 (version 3.4.3)
- All files should end with a new line
- The first line of all files should be exactly `#!/usr/bin/python3`
- A `README.md` file at the root of the project folder is mandatory
- Code should use PEP 8 style (version 1.7.x)
- All files must be executable

## Tasks

- Prime Game: Implement a function to determine the winner of a prime number removal game.

## Example

```python
x = 3
nums = [4, 5, 1]
print("Winner: {}".format(isWinner(x, nums)))
```

Output:
```
Winner: Ben
```

## Repository

- GitHub repository: [alx-interview](https://github.com/Giniks/alx-interview)
- Directory: `0x0A-primegame`
- File: `0-prime_game.py`
