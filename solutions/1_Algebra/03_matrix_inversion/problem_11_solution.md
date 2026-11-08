## Question

Given the matrix:

A(t) =

    [ 1  t ]
    [ t  1 ]

Find all values of t for which the matrix is invertible, and then give a formula for A(t)^(-1).

Explain what happens to this formula at the excluded values.

## Solution

A square matrix is invertible if and only if its determinant is not equal to zero.

To determine for which values of t the matrix is invertible, we first calculate its determinant.

**Step 1: Calculate the determinant**

The given matrix is:

    A(t) = [ 1  t ]
           [ t  1 ]

For a 2x2 matrix, the determinant is:

    det(A(t)) = ad - bc

Substituting the entries:

    det(A(t)) = (1 * 1) - (t * t)

Therefore:

    det(A(t)) = 1 - t^2

**Step 2: Determine the values of t for which the inverse exists**

The inverse exists when the determinant is non-zero:

    1 - t^2 != 0

Rearranging:

    t^2 != 1

Therefore:

    t != 1 and t != -1

The matrix is invertible for all real values of t except t = 1 and t = -1.

**Step 3: Find the inverse formula**

The inverse formula for a 2x2 matrix is:

    A^(-1) = 1/(ad - bc) * [  d  -b ]
                              [ -c   a ]

Applying this formula to A(t):

    A(t)^(-1) = 1/(1 - t^2) * [ 1  -t ]
                                  [ -t  1 ]

Therefore:

    A(t)^(-1) = [  1/(1 - t^2)   -t/(1 - t^2) ]
                [ -t/(1 - t^2)    1/(1 - t^2) ]

This formula is valid only when t is different from 1 and -1.

**Step 4: Explain what happens at the excluded values**

When t = 1:

    A(1) = [ 1  1 ]
           [ 1  1 ]

Its determinant is:

    det(A(1)) = 1 - 1^2 = 0

The two rows are identical, so the matrix is singular and has no inverse.

When t = -1:

    A(-1) = [ 1  -1 ]
            [ -1  1 ]

Its determinant is:

    det(A(-1)) = 1 - (-1)^2 = 0

The second row is the negative of the first row, so the rows are linearly dependent. Therefore, the matrix is singular and has no inverse.

At both excluded values, the denominator 1 - t^2 in the inverse formula becomes zero. Division by zero is undefined, so the inverse does not exist.

**Conclusion**

The determinant of A(t) is:

    det(A(t)) = 1 - t^2

The matrix is invertible for:

    t != 1 and t != -1

Its inverse is:

    A(t)^(-1) = 1/(1 - t^2) * [ 1  -t ]
                                  [ -t  1 ]

At t = 1 and t = -1, the determinant is zero, so the inverse does not exist.