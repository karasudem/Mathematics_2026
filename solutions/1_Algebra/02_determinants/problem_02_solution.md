Exercise 2 – Solution

Given:

A = [ 1   2  -1 ]
[ 0   3   4 ]
[ 2   1   5 ]

We need to calculate the determinant using Sarrus’ rule and check the result using a determinant property.

Step 1: Apply Sarrus’ Rule

For a 3x3 matrix, multiply the diagonals from top-left to bottom-right:

Positive diagonals:

(1 * 3 * 5) + (2 * 4 * 2) + (-1 * 0 * 1)

= 15 + 16 + 0

= 31

Negative diagonals:

(-1 * 3 * 2) + (2 * 0 * 5) + (1 * 4 * 1)

= -6 + 0 + 4

= -2

Step 2: Calculate the Determinant

det(A) = Positive diagonals - Negative diagonals

det(A) = 31 - (-2)

det(A) = 33

Step 3: Check Using a Row Operation

We can use the property that adding a multiple of one row to another row does not change the determinant.

Perform:

R3 <- R3 - 2R1

The new matrix is:

A = [ 1   2  -1 ]
[ 0   3   4 ]
[ 0  -3   7 ]

Expanding along the first column:

det(A) = 1 * (3 * 7 - 4 * (-3))

det(A) = 21 + 12

det(A) = 33

The result is the same.

Final Answer

det(A) = 33

Both methods give the same result, so our calculation is correct.