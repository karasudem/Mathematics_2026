Exercise 5 – Solution

Given:

A = [  1  2  3 ]
[  2  1  0 ]
[ -1  4  2 ]

We need to calculate the determinant using row operations.

Step 1: Write the Original Matrix

A = [  1  2  3 ]
[  2  1  0 ]
[ -1  4  2 ]

Step 2: Perform the First Row Operation

R2 <- R2 - 2R1

R2 = [ 2  1  0 ] - 2[ 1  2  3 ]

R2 = [ 0  -3  -6 ]

Adding a multiple of one row to another does not change the determinant.

Step 3: Perform the Second Row Operation

R3 <- R3 + R1

R3 = [ -1  4  2 ] + [ 1  2  3 ]

R3 = [ 0  6  5 ]

This operation also does not change the determinant.

The new matrix is:

A = [ 1   2   3 ]
[ 0  -3  -6 ]
[ 0   6   5 ]

Step 4: Calculate the Determinant

We can now expand along the first column because it contains two zeros.

det(A) = 1 * ((-3 * 5) - (-6 * 6))

det(A) = -15 + 36

det(A) = 21

Step 5: Check the Row Operations

Both operations involved adding a multiple of one row to another row.

These operations do not change the determinant.

Therefore, the determinant remains equal to the original determinant.

Final Answer

det(A) = 21

Both row operations preserved the determinant, so the final result is 21.