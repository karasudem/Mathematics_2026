## Question

Given the matrix:

A =

    [ 1  1  0 ]
    [ 0  1  1 ]
    [ 1  0  1 ]

Use Gauss–Jordan elimination to find the inverse of A.

Check the result by multiplication.

## Solution

The Gauss–Jordan method finds the inverse of a square matrix by transforming the left side of an augmented matrix into the identity matrix using elementary row operations.

We begin by constructing the augmented matrix [A | I], where I is the 3x3 identity matrix.

**Step 1: Construct the augmented matrix**

The given matrix is:

    A = [ 1  1  0 ]
        [ 0  1  1 ]
        [ 1  0  1 ]

The identity matrix is:

    I = [ 1  0  0 ]
        [ 0  1  0 ]
        [ 0  0  1 ]

Therefore, the augmented matrix is:

    [A | I] = [ 1  1  0 | 1  0  0 ]
              [ 0  1  1 | 0  1  0 ]
              [ 1  0  1 | 0  0  1 ]

**Step 2: Eliminate the first entry in the third row**

Apply the row operation:

    R3 -> R3 - R1

The resulting matrix is:

    [ 1  1  0 |  1   0  0 ]
    [ 0  1  1 |  0   1  0 ]
    [ 0 -1  1 | -1   0  1 ]

**Step 3: Eliminate the second entry in the third row**

Apply the row operation:

    R3 -> R3 + R2

The resulting matrix is:

    [ 1  1  0 |  1   0  0 ]
    [ 0  1  1 |  0   1  0 ]
    [ 0  0  2 | -1   1  1 ]

**Step 4: Make the third pivot equal to 1**

Apply the row operation:

    R3 -> (1/2)R3

The resulting matrix is:

    [ 1  1  0 |  1     0     0   ]
    [ 0  1  1 |  0     1     0   ]
    [ 0  0  1 | -1/2  1/2   1/2 ]

**Step 5: Eliminate the third entry in the second row**

Apply the row operation:

    R2 -> R2 - R3

The resulting matrix is:

    [ 1  1  0 |  1     0     0   ]
    [ 0  1  0 |  1/2  1/2  -1/2 ]
    [ 0  0  1 | -1/2  1/2   1/2 ]

**Step 6: Eliminate the second entry in the first row**

Apply the row operation:

    R1 -> R1 - R2

The resulting matrix is:

    [ 1  0  0 |  1/2  -1/2   1/2 ]
    [ 0  1  0 |  1/2   1/2  -1/2 ]
    [ 0  0  1 | -1/2   1/2   1/2 ]

The left side is now the identity matrix.

**Step 7: Identify the inverse matrix**

We have obtained:

    [ I | A^(-1) ] = [ 1  0  0 |  1/2  -1/2   1/2 ]
                     [ 0  1  0 |  1/2   1/2  -1/2 ]
                     [ 0  0  1 | -1/2   1/2   1/2 ]

Therefore, the inverse matrix is:

    A^(-1) = [  1/2  -1/2   1/2 ]
             [  1/2   1/2  -1/2 ]
             [ -1/2   1/2   1/2 ]

**Step 8: Verify the result by multiplication**

To check the calculated inverse, multiply A by A^(-1).

    AA^(-1) = [ 1  1  0 ]   [  1/2  -1/2   1/2 ]
              [ 0  1  1 ] × [  1/2   1/2  -1/2 ]
              [ 1  0  1 ]   [ -1/2   1/2   1/2 ]

Calculating each entry:

    AA^(-1) = [ 1/2 + 1/2 + 0       -1/2 + 1/2 + 0       1/2 - 1/2 + 0 ]
              [ 0 + 1/2 - 1/2        0 + 1/2 + 1/2        0 - 1/2 + 1/2 ]
              [ 1/2 + 0 - 1/2       -1/2 + 0 + 1/2       1/2 + 0 + 1/2 ]

Simplifying:

    AA^(-1) = [ 1  0  0 ]
              [ 0  1  0 ]
              [ 0  0  1 ]

Thus:

    AA^(-1) = I

Since the product is the identity matrix, the calculated inverse is correct.

**Conclusion**

Using Gauss–Jordan elimination, the left side of the augmented matrix was transformed into the identity matrix. The right side became the inverse of A.

The final result is:

    A^(-1) = [  1/2  -1/2   1/2 ]
             [  1/2   1/2  -1/2 ]
             [ -1/2   1/2   1/2 ]

The result has been verified by multiplication.