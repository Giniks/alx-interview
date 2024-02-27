## Log Parsing Script

This script reads log lines from standard input (stdin) and computes metrics based on the input format specified below.

## Input Format

The input lines should have the following format:
```
<IP Address> - [<date>] "GET /projects/260 HTTP/1.1" <status code> <file size>
```
If a line does not match this format, it will be skipped.

## Metrics Computed

After every 10 lines and/or a keyboard interruption (CTRL + C), the script prints the following statistics from the beginning:

1. **Total file size**: 
   - This is the sum of all previous file sizes encountered.

2. **Number of lines by status code**:
   - Possible status codes: 200, 301, 400, 401, 403, 404, 405, and 500.
   - The script counts the number of occurrences of each status code and prints them in ascending order.

## Example Usage

To generate log lines and feed them to the script for computation, you can use the provided `0-generator.py` script. Here's an example of how to use it with the log parsing script:

```bash
./0-generator.py | ./0-stats.py
```

## Example Output

Here's an example of the output produced by the script during execution:

```
File size: 5213
200: 2
401: 1
403: 2
404: 1
405: 1
500: 3
```

## Implementation

The script is implemented in Python and handles KeyboardInterrupt to print the final statistics when interrupted.

## Repository Contents

- `0-generator.py`: Script to generate random log lines.
- `0-stats.py`: Main log parsing script.

## Author

- Name: Ginika Elizabeth
- Email: elizabethginika9@gmail.com
