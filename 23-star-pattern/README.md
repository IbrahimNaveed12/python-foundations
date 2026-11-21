# Star Pattern

Read an integer and print a growing triangle of stars, preceded by a blank line.

## Problem Summary
Display an empty line, then one star, two stars, and continue until the input
number is reached.

## Logic & Approach
The program iterates from `0` through the input number and prints a string
containing that many stars on each line. The first iteration prints an empty
line.

## Time & Space Complexity
| Measure | Complexity |
|---|---:|
| Time | O(n^2) |
| Space | O(n) |

## Example Input & Output
```text
Enter a Number : 4

*
**
***
****
```

## Program Flow
```mermaid
flowchart TD
    A([Start]) --> B["Read integer a"]
    B --> C["Set i to 0"]
    C --> D{"Is i at most a?"}
    D -->|Yes| E["Print i stars and a newline"]
    E --> F["Increment i"]
    F --> D
    D -->|No| G([End])
```

## Run
Run with Python 3:
```bash
python stars.py
```
