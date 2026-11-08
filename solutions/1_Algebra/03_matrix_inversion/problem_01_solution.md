## Question

Given the matrices:

A =

    [ 2  1 ]
    [ 1  1 ]

B =

    [  1  -1 ]
    [ -1   2 ]

Check, without using a formula, whether B = A^(-1). Compute AB and BA and relate the result to the definition of the inverse.

## Solution

According to the definition, a matrix B is the inverse of a square matrix A if both products AB and BA are equal to the identity matrix I.

For a 2x2 matrix, the identity matrix is:

    I = [ 1  0 ]
        [ 0  1 ]

**Step 1: Calculate AB**

First, multiply matrix A by matrix B:

    AB = [ 2  1 ]   [  1  -1 ]
         [ 1  1 ] × [ -1   2 ]

Multiply each row of A by each column of B:

    AB = [ 2(1) + 1(-1)    2(-1) + 1(2) ]
         [ 1(1) + 1(-1)    1(-1) + 1(2) ]

Simplifying:

    AB = [ 2 - 1    -2 + 2 ]
         [ 1 - 1    -1 + 2 ]

Therefore:

    AB = [ 1  0 ]
         [ 0  1 ]

Thus, AB = I.

**Step 2: Calculate BA**

Now, multiply matrix B by matrix A:

    BA = [  1  -1 ]   [ 2  1 ]
         [ -1   2 ] × [ 1  1 ]

Multiply each row of B by each column of A:

    BA = [ 1(2) + (-1)(1)    1(1) + (-1)(1) ]
         [ (-1)(2) + 2(1)    (-1)(1) + 2(1) ]

Simplifying:

    BA = [ 2 - 1    1 - 1 ]
         [ -2 + 2   -1 + 2 ]

Therefore:

    BA = [ 1  0 ]
         [ 0  1 ]

Thus, BA = I.

**Step 3: Relate the Results to the Definition**

By definition, B is the inverse of A if both conditions are satisfied:

    AB = I

and

    BA = I

In this exercise, both products give the identity matrix:

    AB = BA = I

Therefore, B satisfies the definition of the inverse of A.

The final result is:

    B = A^(-1)

Hence, the given matrix B is indeed the inverse of matrix A.