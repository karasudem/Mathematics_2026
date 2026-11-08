## Question

Given the matrices:

D =

    [ 2   0   0 ]
    [ 0  -3   0 ]
    [ 0   0   5 ]

and

E =

    [ 2  0  0 ]
    [ 0  0  0 ]
    [ 0  0  5 ]

Without using Gauss–Jordan elimination, decide which matrix is invertible.

For the invertible matrix, give the inverse and check the result by multiplication.

## Solution

A diagonal matrix is invertible if and only if all its diagonal entries are non-zero.

If a diagonal matrix is invertible, its inverse is obtained by taking the reciprocal of each diagonal entry.

**Step 1: Determine whether D is invertible**

The given matrix is:

    D = [ 2   0   0 ]
        [ 0  -3   0 ]
        [ 0   0   5 ]

The diagonal entries are:

    2, -3, 5

All three diagonal entries are non-zero.

Therefore, D is invertible.

We can also verify this using its determinant:

    det(D) = 2 * (-3) * 5

    det(D) = -30

Since the determinant is not equal to zero, D is invertible.

**Step 2: Find D^(-1)**

To find the inverse of a diagonal matrix, take the reciprocal of each diagonal entry.

The reciprocals are:

    1/2, -1/3, 1/5

Therefore:

    D^(-1) = [ 1/2    0     0   ]
             [  0   -1/3   0   ]
             [  0     0    1/5 ]

**Step 3: Determine whether E is invertible**

The given matrix is:

    E = [ 2  0  0 ]
        [ 0  0  0 ]
        [ 0  0  5 ]

Its diagonal entries are:

    2, 0, 5

The second diagonal entry is zero.

Therefore, the determinant is:

    det(E) = 2 * 0 * 5

    det(E) = 0

A square matrix is invertible only if its determinant is non-zero.

Since det(E) = 0, E is not invertible.

Thus, E^(-1) does not exist.

**Step 4: Verify D^(-1) by multiplication**

To check the calculated inverse, multiply D by D^(-1):

    DD^(-1) = [ 2   0   0 ]   [ 1/2    0     0   ]
              [ 0  -3   0 ] × [  0   -1/3   0   ]
              [ 0   0   5 ]   [  0     0    1/5 ]

Calculating:

    DD^(-1) = [ 2(1/2)    0         0       ]
              [ 0        (-3)(-1/3) 0       ]
              [ 0         0        5(1/5)   ]

Therefore:

    DD^(-1) = [ 1  0  0 ]
              [ 0  1  0 ]
              [ 0  0  1 ]

Thus:

    DD^(-1) = I

Since the product is the identity matrix, the calculated inverse is correct.

**Conclusion**

Matrix D is invertible because all its diagonal entries are non-zero.

Its inverse is:

    D^(-1) = [ 1/2    0     0   ]
             [  0   -1/3   0   ]
             [  0     0    1/5 ]

Matrix E is not invertible because one of its diagonal entries is zero, making its determinant equal to zero.

Therefore, D has an inverse, while E does not.