# Island Perimeter

## Description

This function calculates the perimeter of the island described in a given grid.

- `grid` is a list of list of integers:
  - 0 represents water
  - 1 represents land
  - Each cell is square, with a side length of 1
  - Cells are connected horizontally/vertically (not diagonally)
  - Grid is rectangular, with its width and height not exceeding 100
  - The grid is completely surrounded by water
  - There is only one island (or nothing)
  - The island doesn’t have “lakes” (water inside that isn’t connected to the water surrounding the island)

## Function Signature

```python
def island_perimeter(grid):
    """
    Returns the perimeter of the island described in the grid.

    Args:
        grid (List[List[int]]): A list of list of integers representing the grid.

    Returns:
        int: The perimeter of the island.
    """
```

## Example

```python
grid = [
    [0, 0, 0, 0, 0, 0],
    [0, 1, 0, 0, 0, 0],
    [0, 1, 0, 0, 0, 0],
    [0, 1, 1, 1, 0, 0],
    [0, 0, 0, 0, 0, 0]
]
print(island_perimeter(grid))  # Output: 12
```

## Repository Structure

- **Directory:** 0x09-island_perimeter
- **Files:**
  - `0-island_perimeter.py`: Contains the implementation of the `island_perimeter` function.
  - `0-main.py`: Test script to verify the functionality of the `island_perimeter` function.

## Usage

1. Clone the repository:
   ```
   git clone https://github.com/your-username/alx-interview.git
   ```

2. Navigate to the `0x09-island_perimeter` directory:
   ```
   cd alx-interview/0x09-island_perimeter
   ```

3. Run the test script to verify the function:
   ```
   ./0-main.py
   ```

4. Feel free to modify and use the `island_perimeter` function in your projects.

## Author
- Name: Ginika Elizabeth Nna.
- Email: elizabethginika9@gmail.com

This `README.md` provides a clear description of the function, its arguments, and its return value. It also includes an example of usage and instructions on how to run the test script. Adjust the content as needed for your specific requirements.
