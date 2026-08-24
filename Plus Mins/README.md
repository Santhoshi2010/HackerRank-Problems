# Plus Minus

**HackerRank Topic:** Problem Solving
**Category:** Algorithms

## Problem

Given an array of integers, find the proportion of elements that are:

* Positive
* Negative
* Zero

Print each proportion with 6 digits after the decimal point.

## Example

**Input:**

```text
[-4, 3, -9, 0, 4, 1]
```

There are:

* 3 positive numbers
* 2 negative numbers
* 1 zero
* 6 total numbers

## Calculation

**Positive ratio:**

```text
3 / 6 = 0.500000
```

**Negative ratio:**

```text
2 / 6 = 0.333333
```

**Zero ratio:**

```text
1 / 6 = 0.166667
```

## Output

```text
0.500000
0.333333
0.166667
```

## Approach

1. Create three counters for positive, negative, and zero values.
2. Traverse the array using a `for` loop.
3. If the number is greater than `0`, increment the positive counter.
4. If the number is less than `0`, increment the negative counter.
5. Otherwise, increment the zero counter.
6. Divide each count by the total number of elements.
7. Print each ratio with 6 decimal places.

## Python Solution

See [`Plus-Minus.py`](Plus-Minus.py).

## Concepts Used

* Lists
* `for` loop
* `if-elif-else`
* Counters
* `len()`
* Arithmetic operations
* Floating-point formatting
* Problem Solving

## Complexity

**Time Complexity:** `O(n)`

**Space Complexity:** `O(1)`
