Exercise 13 – Solution

Given:

F = [ 1  1 ]
[ 1  0 ]

We need to calculate F^2, F^3, F^4, and F^5, compare the results with the Fibonacci sequence, and explain how matrix multiplication performs one recurrence step.

Step 1: Calculate F^2

F^2 = F * F

F^2 = [ 1  1 ] * [ 1  1 ]
[ 1  0 ]   [ 1  0 ]

F^2 = [ 2  1 ]
[ 1  1 ]

Step 2: Calculate F^3

F^3 = F^2 * F

F^3 = [ 2  1 ] * [ 1  1 ]
[ 1  1 ]   [ 1  0 ]

F^3 = [ 3  2 ]
[ 2  1 ]

Step 3: Calculate F^4

F^4 = F^3 * F

F^4 = [ 3  2 ] * [ 1  1 ]
[ 2  1 ]   [ 1  0 ]

F^4 = [ 5  3 ]
[ 3  2 ]

Step 4: Calculate F^5

F^5 = F^4 * F

F^5 = [ 5  3 ] * [ 1  1 ]
[ 3  2 ]   [ 1  0 ]

F^5 = [ 8  5 ]
[ 5  3 ]

Step 5: Compare with the Fibonacci Sequence

The Fibonacci sequence is:

0, 1, 1, 2, 3, 5, 8, 13, …

The matrix powers contain consecutive Fibonacci numbers:

F^2 = [ 2  1 ]
[ 1  1 ]

F^3 = [ 3  2 ]
[ 2  1 ]

F^4 = [ 5  3 ]
[ 3  2 ]

F^5 = [ 8  5 ]
[ 5  3 ]

We can observe that each matrix contains four consecutive Fibonacci numbers.

The top-left number gives the next Fibonacci number, while the other entries contain the previous numbers.

Step 6: Multiply F by a Vector

Let the vector be:

x = [ a ]
[ b ]

Then:

F * x = [ 1  1 ] * [ a ]
[ 1  0 ]   [ b ]

F * x = [ a + b ]
[ a     ]

This means that the new first value is the sum of the two previous values, and the second value becomes the previous first value.

This is exactly one step of the Fibonacci recurrence.

Final Answer

The matrix powers are:

F^2 = [ 2  1 ]
[ 1  1 ]

F^3 = [ 3  2 ]
[ 2  1 ]

F^4 = [ 5  3 ]
[ 3  2 ]

F^5 = [ 8  5 ]
[ 5  3 ]

Matrix multiplication generates consecutive Fibonacci numbers.

The multiplication F * [a, b] produces [a + b, a], which represents one step of the Fibonacci recurrence.