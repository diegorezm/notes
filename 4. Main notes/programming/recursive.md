---
title: recursive
date: 17-05-2024
tags:
  - algorithm
  - completed
index: "[[algorithm]]"
---

# Recursive
## Divide and conquer
A recursive algorithm, also known as  divide-and-conquer algorithm, is a powerful problem-solving technique that works by breaking down a complex problem into smaller, **similar subproblems**. It's like tackling a large mountain by breaking the climb into smaller, manageable hills. Once the problem **is divided into the smallest possible subproblems (the base case)** the algorithm enters the "conquer" phase, these **base cases are usually trivial to solve**. Once the base case is solved the algorithm **works its way back up combining the solution** of the small problems to solve the larger ones.
## Example
```python
def sum(a: int, b: int) -> int:
	if b == 0:
		return a
	return sum(a + 1, b - 1)
```
This code defines a function `sum(a, b)` that calculates the sum `` a + b`` using recursion.

- **Base Case:** Stops when `b` reaches zero, returning `a` (the final sum).

- **Recursive Step:** If `b` isn't zero, it adds 1 to `a`, subtracts 1 from `b`, and calls itself with these updated values. This breaks down the problem into smaller sums until reaching the base case.
# References