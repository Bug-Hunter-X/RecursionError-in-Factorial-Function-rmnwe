# RecursionError in Factorial Function

This repository demonstrates a common error in recursive functions: the lack of a proper base case for negative inputs. The factorial function is not defined for negative numbers, leading to infinite recursion and a `RecursionError`.

The `bug.py` file contains the buggy code, while `bugSolution.py` provides the corrected version.

## How to Reproduce

1. Clone this repository.
2. Run `bug.py`. Observe the `RecursionError` when providing a negative input. 
3. Run `bugSolution.py` to see the corrected implementation.