Exercise 11 – Solution

Given:

A = [ 1  2  3 ]
[ 1  3  4 ]
[ 1  4  6 ]

We need to calculate the determinant using row operations.

Step 1: Perform the First Row Operations

R2 <- R2 - R1

R3 <- R3 - R1

These operations do not change the determinant.

The new matrix is:

A = [ 1  2  3 ]
[ 0  1  1 ]
[ 0  2  3 ]

Step 2: Create More Zeros

Perform:

R3 <- R3 - 2R2

This operation also does not change the determinant.

The new matrix is:

A = [ 1  2  3 ]
[ 0  1  1 ]
[ 0  0  1 ]

Step 3: Calculate the Determinant

The resulting matrix is an upper triangular matrix.

The determinant is the product of the diagonal entries.

det(A) = 1 * 1 * 1

det(A) = 1

Step 4: Explain the Row Operations

We used three row operations:

1. R2 <- R2 - R1
2. R3 <- R3 - R1
3. R3 <- R3 - 2R2

Adding or subtracting a multiple of one row to another row does not change the determinant.

Therefore, the determinant remains unchanged throughout the calculation.

Final Answer

det(A) = 1

All row operations preserved the determinant, and the final triangular matrix made the calculation easier.