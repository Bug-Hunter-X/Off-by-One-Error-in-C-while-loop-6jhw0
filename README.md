# Off-by-One Error in C While Loop

This repository demonstrates a common off-by-one error in C programming, specifically within a `while` loop.  The provided code attempts to print numbers from 1 to 10, but due to the increment operation's placement, it might not behave as expected. The solution shows how to fix this error.

## Bug Description
The `while` loop condition `i <= 10` might lead to an extra iteration, causing an unintended number to be printed.

## How to Reproduce
1. Compile the code in `bug.c`.
2. Run the executable.
3. Observe the output; it may include an unexpected extra number.

## Solution
The solution demonstrates a corrected loop condition to accurately print numbers 1 through 10.