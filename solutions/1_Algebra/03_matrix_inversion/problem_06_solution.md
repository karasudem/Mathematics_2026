## Question

Solve the matrix equation:

Ax = b

where

A =

    [ 2  1 ]
    [ 1  3 ]

and

b =

    [ 5 ]
    [ 7 ]

Use x = A^(-1)b to solve the system.

Then substitute the resulting vector back into the equation and check the result.

## Solution

To solve the system using the inverse matrix method, we start with:

    Ax = b

Multiplying both sides from the left by A^(-1), we obtain:

    A^(-1)Ax = A^(-1)b

Since:

    A^(-1)A = I

and:

    Ix = x

the solution is:

    x = A^(-1)b

**Step 1: Calculate the determinant of A**

The given matrix is:

    A = [ 2  1 ]
        [ 1  3 ]

For a 2x2 matrix, the determinant is:

    det(A) = ad - bc

Substituting the values:

    det(A) = (2 * 3) - (1 * 1)

    det(A) = 6 - 1

    det(A) = 5

Since the determinant is not equal to zero, the inverse of A exists.

**Step 2: Find the inverse of A**

Using the formula for the inverse of a 2x2 matrix:

    A^(-1) = 1/(ad - bc) * [  d  -b ]
                              [ -c   a ]

Substituting the values:

    A^(-1) = 1/5 * [  3  -1 ]
                    [ -1   2 ]

Therefore:

    A^(-1) = [  3/5  -1/5 ]
             [ -1/5   2/5 ]

**Step 3: Calculate x = A^(-1)b**

We know that:

    x = A^(-1)b

Substituting the inverse matrix and vector b:

    x = [  3/5  -1/5 ]   [ 5 ]
        [ -1/5   2/5 ] × [ 7 ]

Multiplying the matrices:

    x = [ (3/5)(5) + (-1/5)(7) ]
        [ (-1/5)(5) + (2/5)(7) ]

Simplifying:

    x = [ 3 - 7/5 ]
        [ -1 + 14/5 ]

Therefore:

    x = [ 8/5 ]
        [ 9/5 ]

**Step 4: Verify the result by substitution**

To check the solution, substitute the calculated vector x into the original equation:

    Ax = b

We have:

    [ 2  1 ]   [ 8/5 ]   [ 5 ]
    [ 1  3 ] × [ 9/5 ] = [ 7 ]

Calculating each entry:

    Ax = [ 2(8/5) + 1(9/5) ]
         [ 1(8/5) + 3(9/5) ]

Simplifying:

    Ax = [ 16/5 + 9/5 ]
         [  8/5 + 27/5 ]

Therefore:

    Ax = [ 25/5 ]
         [ 35/5 ]

    Ax = [ 5 ]
         [ 7 ]

This is exactly equal to the given vector b.

**Conclusion**

The inverse matrix method gives the solution:

    x = [ 8/5 ]
        [ 9/5 ]

Substituting this vector into the original equation gives Ax = b.

Therefore, the solution is correct.