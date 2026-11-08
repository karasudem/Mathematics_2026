## Question

Given the matrices:

A =

    [ 1  2 ]
    [ 0  1 ]

B =

    [ 3  1 ]
    [ 2  4 ]

Solve the matrix equation AX = B for X.

Before calculating, decide on which side of the equation A^(-1) must be used.

Then check the result by computing AX.

## Solution

We are given the matrix equation:

    AX = B

Our goal is to isolate X.

Since A is multiplied by X on the left, we must multiply both sides of the equation by A^(-1) from the left.

**Step 1: Determine where to use A^(-1)**

Starting with:

    AX = B

Multiply both sides from the left by A^(-1):

    A^(-1)AX = A^(-1)B

Since:

    A^(-1)A = I

and:

    IX = X

we obtain:

    X = A^(-1)B

Therefore, A^(-1) must be used on the left side of both sides of the equation.

**Step 2: Calculate A^(-1)**

The given matrix is:

    A = [ 1  2 ]
        [ 0  1 ]

Using the inverse formula for a 2x2 matrix:

    A^(-1) = 1/(ad - bc) * [  d  -b ]
                              [ -c   a ]

First, calculate the determinant:

    det(A) = (1 * 1) - (2 * 0)

    det(A) = 1

Since the determinant is non-zero, A is invertible.

Applying the formula:

    A^(-1) = 1/1 * [ 1  -2 ]
                    [ 0   1 ]

Therefore:

    A^(-1) = [ 1  -2 ]
             [ 0   1 ]

**Step 3: Calculate X = A^(-1)B**

We know that:

    B = [ 3  1 ]
        [ 2  4 ]

Using:

    X = A^(-1)B

we obtain:

    X = [ 1  -2 ]   [ 3  1 ]
        [ 0   1 ] × [ 2  4 ]

Calculating each entry:

    X = [ 1(3) + (-2)(2)    1(1) + (-2)(4) ]
        [ 0(3) + 1(2)       0(1) + 1(4)    ]

Simplifying:

    X = [ 3 - 4    1 - 8 ]
        [ 0 + 2    0 + 4 ]

Therefore:

    X = [ -1  -7 ]
        [  2   4 ]

**Step 4: Verify the result by calculating AX**

To check the result, substitute the calculated matrix X into the original equation:

    AX = B

We have:

    AX = [ 1  2 ]   [ -1  -7 ]
         [ 0  1 ] × [  2   4 ]

Calculating each entry:

    AX = [ 1(-1) + 2(2)    1(-7) + 2(4) ]
         [ 0(-1) + 1(2)    0(-7) + 1(4) ]

Simplifying:

    AX = [ -1 + 4    -7 + 8 ]
         [  0 + 2     0 + 4 ]

Therefore:

    AX = [ 3  1 ]
         [ 2  4 ]

This is exactly equal to the given matrix B.

Thus:

    AX = B

**Conclusion**

To solve AX = B, we multiply both sides from the left by A^(-1), because A is on the left side of X.

The solution is:

    X = [ -1  -7 ]
        [  2   4 ]

Substituting this matrix into the original equation gives AX = B.

Therefore, the solution is correct.