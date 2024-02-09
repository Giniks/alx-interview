# Pascal's Triangle

This Python function generates Pascal's triangle up to the nth row and returns it as a list of lists of integers. It returns an empty list if n is less than or equal to 0.                                          
## Table of Contents
1. [Introduction](#introduction)
2. [Functionality](#functionality)                                     3. [Usage](#usage)                                                     4. [Acknowledgment](#acknowledgment)
5. [Author](#author)
                                                                       ## Introduction
Pascal's triangle is a mathematical concept that represents a triangular array of binomial coefficients. Each number in the triangle is the sum of the two numbers directly above it.

## Functionality                                                       The `pascal_triangle` function takes an integer `n` as input and returns a list of lists representing Pascal's triangle up to the nth row.
                                                                       ## Usage                                                               To use the `pascal_triangle` function, import it into your Python script and call it with the desired value of `n`.

```python                                                              from pascal_triangle import pascal_triangle

# Example usage:                                                       triangle = pascal_triangle(5)
print(triangle)

## Acknowledgment
This implementation was inspired by the algorithm for generating Pascal's triangle.All thanks to ALX community.

## Author
Created by Ginika Elizabeth Nna - elizabethginika9@gmail.com
