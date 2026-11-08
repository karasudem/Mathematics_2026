## Question

Given the matrix:

A =

    [ 2  4 ]
    [ 1  2 ]

Explain in two ways why A^(-1) does not exist:

1. Using the determinant.
2. Using dependence between the rows.

## Solution

A square matrix has an inverse only if its determinant is non-zero. Another way to recognize a matrix without an inverse is to check whether its rows are linearly dependent.

**Step 1: Explain using the determinant**

The given matrix is:

    A = [ 2  4 ]
        [ 1  2 ]

For a 2x2 matrix, the determinant is calculated as:

    det(A) = ad - bc

Substituting the entries of A:

    det(A) = (2 * 2) - (4 * 1)

    det(A) = 4 - 4

    det(A) = 0

Since the determinant is equal to zero, the matrix is singular.

A square matrix is invertible only when its determinant is non-zero. Therefore, A does not have an inverse.

**Step 2: Explain using dependence between the rows**

The rows of matrix A are:

    Row 1 = [ 2  4 ]

    Row 2 = [ 1  2 ]

The second row is equal to one-half of the first row:

    Row 2 = (1/2) * Row 1

This means that the two rows are linearly dependent.

Linearly dependent rows cannot provide two independent directions. Therefore, the matrix does not have full rank.

A square matrix must have linearly independent rows to be invertible.

Since the rows of A are linearly dependent, A is not invertible.

**Conclusion**

Both methods lead to the same result:

    det(A) = 0

and the rows of A are linearly dependent.

Therefore, the matrix is singular and its inverse does not exist.

    A^(-1) does not exist.