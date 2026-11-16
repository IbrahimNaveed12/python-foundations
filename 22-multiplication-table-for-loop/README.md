# Multiplication Table with a For Loop

Read an integer and print its multiplication table from 1 through 10.

## Problem Summary
Display the first ten multiples of a user-entered number.

## Logic & Approach
The program iterates over `range(1, 11)` and prints the number multiplied by
each value in that range.

## Time & Space Complexity
| Measure | Complexity |
|---|---:|
| Time | O(1) |
| Space | O(1) |

## Example Input & Output
```text
Enter the Number of Which you Want to find table : 3
3 x 1 = 3
3 x 2 = 6
...
3 x 10 = 30
```

## Program Flow
```mermaid
flowchart TD
    A([Start]) --> B["Read integer a"]
    B --> C["Iterate from 1 through 10"]
    C --> D["Print a multiplied by each value"]
    D --> E([End])
```

## Run
Run with Python 3:
```bash
python table_of_any_number.py
```
