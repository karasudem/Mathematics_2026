Exercise 13 – Solution

Given:

A = [ 1  2  3 ]
[ 2  5  7 ]
[ 1  0  2 ]

We need to calculate the determinant using elimination and record the effect of each row operation.

Step 1: Write the Original Matrix

A = [ 1  2  3 ]
[ 2  5  7 ]
[ 1  0  2 ]

Step 2: Perform the First Row Operation

R2 <- R2 - 2R1

The new second row is:

[ 2  5  7 ] - 2[ 1  2  3 ]

= [ 0  1  1 ]

This operation does not change the determinant.

Step 3: Perform the Second Row Operation

R3 <- R3 - R1

The new third row is:

[ 1  0  2 ] - [ 1  2  3 ]

= [ 0  -2  -1 ]

This operation also does not change the determinant.

The new matrix is:

A = [ 1   2   3 ]
[ 0   1   1 ]
[ 0  -2  -1 ]

Step 4: Create Another Zero

Perform:

R3 <- R3 + 2R2

The new third row is:

[ 0  -2  -1 ] + 2[ 0  1  1 ]

= [ 0  0  1 ]

This operation does not change the determinant.

The resulting matrix is:

A = [ 1  2  3 ]
[ 0  1  1 ]
[ 0  0  1 ]

Step 5: Calculate the Determinant

The resulting matrix is an upper triangular matrix.

The determinant is the product of the diagonal entries.

det(A) = 1 * 1 * 1

det(A) = 1

Step 6: Explain the Row Operations

We used three row operations:

1. R2 <- R2 - 2R1
2. R3 <- R3 - R1
3. R3 <- R3 + 2R2

Adding or subtracting a multiple of one row to another row does not change the determinant.

Therefore, the determinant remains unchanged.

Final Answer

det(A) = 1

All three row operations preserved the determinant, and the final triangular matrix made the calculation easier.