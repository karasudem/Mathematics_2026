## Question

Given the matrix:

A =

    [ 1  2 ]
    [ 3  5 ]

Find A^(-1) using the Gauss–Jordan method.

Show the augmented matrix [A | I] after successive operations and explain why obtaining I on the left gives the inverse on the right.

## Solution

The Gauss–Jordan method finds the inverse of a square matrix by transforming the left side of an augmented matrix into the identity matrix using elementary row operations.

We start by constructing the augmented matrix [A | I], where A is the given matrix and I is the identity matrix.

**Step 1: Construct the augmented matrix**

The given matrix is:

    A = [ 1  2 ]
        [ 3  5 ]

The identity matrix is:

    I = [ 1  0 ]
        [ 0  1 ]

Therefore, the augmented matrix is:

    [A | I] = [ 1  2 | 1  0 ]
              [ 3  5 | 0  1 ]

**Step 2: Eliminate the first entry in the second row**

Apply the row operation:

    R2 -> R2 - 3R1

This gives:

    [ 1  2 |  1   0 ]
    [ 0 -1 | -3   1 ]

**Step 3: Make the second pivot equal to 1**

Apply the row operation:

    R2 -> -R2

The resulting matrix is:

    [ 1  2 | 1   0 ]
    [ 0  1 | 3  -1 ]

**Step 4: Eliminate the second entry in the first row**

Apply the row operation:

    R1 -> R1 - 2R2

The resulting matrix is:

    [ 1  0 | -5   2 ]
    [ 0  1 |  3  -1 ]

The left side is now the identity matrix.

**Step 5: Identify the inverse matrix**

After applying the row operations, we obtain:

    [ I | A^(-1) ] = [ 1  0 | -5   2 ]
                     [ 0  1 |  3  -1 ]

Therefore, the inverse matrix is:

    A^(-1) = [ -5   2 ]
             [  3  -1 ]

**Step 6: Explain why the method works**

Every elementary row operation is equivalent to multiplying the augmented matrix on the left by an invertible elementary matrix.

If a sequence of row operations transforms A into I, then the same operations transform the identity matrix I into A^(-1).

If the combined effect of these row operations is represented by a matrix E, then:

    EA = I

Therefore:

    E = A^(-1)

Since the same row operations are applied to both sides of the augmented matrix, the right side becomes A^(-1).

**Step 7: Verify the result by multiplication**

To verify the calculated inverse, multiply A by A^(-1):

    AA^(-1) = [ 1  2 ]   [ -5   2 ]
              [ 3  5 ] × [  3  -1 ]

Calculating each entry:

    AA^(-1) = [ 1(-5) + 2(3)    1(2) + 2(-1) ]
              [ 3(-5) + 5(3)    3(2) + 5(-1) ]

Simplifying:

    AA^(-1) = [ -5 + 6     2 - 2 ]
              [ -15 + 15   6 - 5 ]

Therefore:

    AA^(-1) = [ 1  0 ]
              [ 0  1 ]

Thus:

    AA^(-1) = I

Since the product is the identity matrix, the calculated inverse is correct.

**Conclusion**

The Gauss–Jordan method transforms the left side of the augmented matrix [A | I] into the identity matrix. The right side then becomes the inverse of A.

The final result is:

    A^(-1) = [ -5   2 ]
             [  3  -1 ]

The result has been verified by multiplication.