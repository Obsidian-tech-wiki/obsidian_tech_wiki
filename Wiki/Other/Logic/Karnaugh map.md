---
authors:
  - "0x4248"
tags:
  - Other
  - Logic
---
A **Karnaugh map** is a way of showing [[Logic|logic]] and [[Boolean algebra|boolean algebra]] in a simple way.
## Example 1
Karnaugh maps are quite similar to truth tables. Here is a simple AND gate example.

| A   | B   | $A \land B$ |
| --- | --- | ----------- |
| 0   | 0   | 0           |
| 1   | 0   | 0           |
| 0   | 1   | 0           |
| 1   | 1   | 1           |

| $\frac{A}{B}$ | A = 0 | A = 1 |
| ------------- | ----- | ----- |
| **B = 0**     | 0     | 0     |
| **B = 1**     | 0     | 1     |
## Example 2
In this example we are doing the following: $(\lnot A \land B) \lor B$. 

| A   | B   | $(\lnot A \land B) \lor B$ |
| --- | --- | -------------------------- |
| 0   | 0   | 0                          |
| 0   | 1   | 1                          |
| 1   | 0   | 0                          |
| 1   | 1   | 1                          |

| $\frac{A}{B}$ | A = 0 | A = 1 |
| ------------- | ----- | ----- |
| **B = 0**     | 0     | 0     |
| **B = 1**     | 1     | 1     |
