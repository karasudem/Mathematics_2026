Exercise 12 – Solution

Given:

A(t) = [ 1  2  3 ]
[ 2  4  t ]
[ 0  1  1 ]

We need to find the values of t for which the matrix is not invertible.

Step 1: Perform the Row Operation

Use the given operation:

R2 <- R2 - 2R1

The new second row is:

[ 2  4  t ] - 2[ 1  2  3 ]

= [ 0  0  t-6 ]

The new matrix is:

A(t) = [ 1  2   3   ]
[ 0  0  t-6 ]
[ 0  1   1   ]

This row operation does not change the determinant.

Step 2: Calculate the Determinant

Expand along the second row:

det(A(t)) = -(t-6) * (1 * 0 - 2 * 0)

Wait: using the second row, the remaining 2x2 determinant comes from columns 1 and 2:

det(A(t)) = -(t-6) * (1 * 1 - 2 * 0)

det(A(t)) = -(t-6)

Step 3: Find the Value of t

The matrix is not invertible when its determinant is zero.

-(t-6) = 0

t - 6 = 0

t = 6

Step 4: Explain What Happens to the Rows

When t = 6, the transformed matrix becomes:

A(6) = [ 1  2  3 ]
[ 0  0  0 ]
[ 0  1  1 ]

The second row becomes a zero row.

This means the rows are linearly dependent, so the determinant is zero.

Final Answer

The matrix is not invertible when:

t = 6

For this value, the transformed matrix contains a zero row, which makes its determinant zero.