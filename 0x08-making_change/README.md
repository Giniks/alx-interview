# Making Change

## Overview

This program is designed to solve the "making change" problem, which involves determining the fewest number of coins needed to meet a given total amount using a pile of coins of different values.

## Problem Statement

Given a list of coins with different values and a total amount, the program calculates the fewest number of coins needed to meet the total amount. If the total is 0 or less, the program returns 0. If the total cannot be met by any combination of coins, the program returns -1.

## Prototype

```
def makeChange(coins, total)
```

## Input

- `coins`: A list of the values of the coins in your possession.
- `total`: The total amount to be achieved.

## Output

The program returns the fewest number of coins needed to meet the total amount.

## Assumptions

- The value of a coin will always be an integer greater than 0.
- You can assume you have an infinite number of each denomination of coin in the list.

## How to Use

1. Clone this repository to your local machine.
2. Run the program, passing in the list of coins and the total amount as arguments to the `makeChange()` function.
3. View the output, which will display the fewest number of coins needed to meet the total amount.

## Example Usage

```
print(makeChange([1, 2, 25], 37))  # Output: 7
print(makeChange([1256, 54, 48, 16, 102], 1453))  # Output: -1
```

## Runtime Evaluation

The program's runtime will be evaluated based on its efficiency in solving the problem.

## Acknowlegement.

All thanks to ALX

## Authour

Ginika Elizabeth
elizabethginika9@gmail.com
