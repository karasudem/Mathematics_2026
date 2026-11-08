## Question

Given the matrix:

S =

    [ 2    0   ]
    [ 0   1/2  ]

The matrix S describes a scaling of the plane.

Find S^(-1) and explain geometrically what the inverse transformation does.

Check the action of the pair S and S^(-1) on one simple vector.

## Solution

The given matrix represents a scaling transformation in the plane.

It multiplies the x-coordinate by 2 and the y-coordinate by 1/2.

The inverse transformation must undo these scaling operations.

**Step 1: Find the inverse matrix**

The given matrix is:

    S = [ 2    0   ]
        [ 0   1/2  ]

Since S is a diagonal matrix with non-zero diagonal entries, its inverse is obtained by taking the reciprocal of each diagonal entry.

Therefore:

    S^(-1) = [ 1/2   0 ]
             [  0    2 ]

**Step 2: Explain the inverse transformation geometrically**

The original transformation S changes the coordinates of a vector as follows:

- The x-coordinate is multiplied by 2.
- The y-coordinate is multiplied by 1/2.

The inverse transformation reverses these operations:

- The x-coordinate is multiplied by 1/2.
- The y-coordinate is multiplied by 2.

Geometrically, S stretches the plane horizontally by a factor of 2 and compresses it vertically by a factor of 1/2.

The inverse transformation S^(-1) reverses these changes by compressing the plane horizontally by a factor of 1/2 and stretching it vertically by a factor of 2.

Applying S^(-1) after S restores every original vector to its initial position.

**Step 3: Check the result using a simple vector**

Choose the vector:

    v = [ 2 ]
        [ 2 ]

First, apply the transformation S:

    Sv = [ 2    0   ]   [ 2 ]
         [ 0   1/2  ] × [ 2 ]

Calculating:

    Sv = [ 2(2) + 0(2) ]
         [ 0(2) + (1/2)(2) ]

Therefore:

    Sv = [ 4 ]
         [ 1 ]

Now, apply the inverse transformation S^(-1) to the resulting vector:

    S^(-1)(Sv) = [ 1/2   0 ]   [ 4 ]
                 [  0    2 ] × [ 1 ]

Calculating:

    S^(-1)(Sv) = [ (1/2)(4) + 0(1) ]
                 [ 0(4) + 2(1) ]

Therefore:

    S^(-1)(Sv) = [ 2 ]
                 [ 2 ]

We obtain the original vector:

    S^(-1)(Sv) = v

**Step 4: Verify the inverse using matrix multiplication**

We can also verify the result by multiplying S by S^(-1):

    SS^(-1) = [ 2    0   ]   [ 1/2   0 ]
              [ 0   1/2  ] × [  0    2 ]

Calculating:

    SS^(-1) = [ 2(1/2) + 0(0)    2(0) + 0(2) ]
              [ 0(1/2) + (1/2)(0)  0(0) + (1/2)(2) ]

Therefore:

    SS^(-1) = [ 1  0 ]
              [ 0  1 ]

Thus:

    SS^(-1) = I

**Conclusion**

The inverse of the scaling matrix is:

    S^(-1) = [ 1/2   0 ]
             [  0    2 ]

The original transformation stretches the plane horizontally and compresses it vertically. The inverse transformation reverses these changes.

Applying S^(-1) after S restores the original vector, and their product is the identity matrix.

Therefore, the calculated inverse is correct.