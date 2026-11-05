Exercise 14 – Solution

Given:

A = [ 1  2 ]
[ k  4 ]

We need to find the values of k for which the system Ax = b has exactly one solution for every b.

Step 1: Calculate the Determinant

det(A) = (1 * 4) - (2 * k)

det(A) = 4 - 2k

Step 2: Find When the System Has Exactly One Solution

A system has exactly one solution for every b when the determinant is not zero.

Therefore:

4 - 2k != 0

2k != 4

k != 2

So, the system has exactly one solution for every b when k is not equal to 2.

Step 3: Consider the Remaining Value

When k = 2, the matrix becomes:

A = [ 1  2 ]
[ 2  4 ]

The second row is twice the first row.

Therefore, the rows are linearly dependent, and the determinant is zero.

The system becomes:

x + 2y = b1

2x + 4y = b2

Step 4: Example with Infinitely Many Solutions

Choose:

b = [ 1 ]
[ 2 ]

The system becomes:

x + 2y = 1

2x + 4y = 2

The second equation is twice the first equation.

Therefore, there are infinitely many solutions.

For example, x = 1 and y = 0 is one solution.

Step 5: Example with No Solution

Choose:

b = [ 1 ]
[ 0 ]

The system becomes:

x + 2y = 1

2x + 4y = 0

The second equation contradicts the first equation because its left side is twice the first equation, but its right side is not.

Therefore, the system has no solution.

Final Answer

* If k != 2, the system has exactly one solution for every b.
* If k = 2, the system may have infinitely many solutions or no solution, depending on b.

Example with infinitely many solutions: b = [1, 2].

Example with no solution: b = [1, 0].