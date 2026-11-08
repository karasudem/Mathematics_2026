## Question

Given the matrix:

A =

    [ 3  2 ]
    [ 5  4 ]

Find the inverse of A using the formula for a 2x2 matrix.

At the end, check the result by computing one product with A.

## Solution

To find the inverse of a 2x2 matrix, we use the following formula:

For a matrix

    A = [ a  b ]
        [ c  d ]

its inverse is:

    A^(-1) = 1/(ad - bc) * [  d  -b ]
                              [ -c   a ]

The inverse exists only if the determinant is not equal to zero.

**Step 1: Calculate the determinant**

The given matrix is:

    A = [ 3  2 ]
        [ 5  4 ]

The determinant of A is:

    det(A) = (3 * 4) - (2 * 5)

    det(A) = 12 - 10

    det(A) = 2

Since det(A) = 2 and 2 is not equal to zero, the inverse of A exists.

**Step 2: Apply the inverse formula**

Using the formula:

    A^(-1) = 1/(ad - bc) * [  d  -b ]
                              [ -c   a ]

We substitute the values:

    a = 3
    b = 2
    c = 5
    d = 4

Therefore:

    A^(-1) = 1/2 * [  4  -2 ]
                    [ -5   3 ]

Multiplying each entry by 1/2:

    A^(-1) = [  2    -1   ]
             [ -5/2   3/2 ]

**Step 3: Verify the result by multiplication**

To check whether the calculated inverse is correct, we multiply A by A^(-1).

If the result is the identity matrix, the inverse is correct.

    AA^(-1) = [ 3  2 ]   [  2    -1   ]
              [ 5  4 ] × [ -5/2   3/2 ]

Calculating each entry:

    AA^(-1) = [ 3(2) + 2(-5/2)       3(-1) + 2(3/2) ]
              [ 5(2) + 4(-5/2)       5(-1) + 4(3/2) ]

Simplifying:

    AA^(-1) = [ 6 - 5    -3 + 3 ]
              [ 10 - 10  -5 + 6 ]

Therefore:

    AA^(-1) = [ 1  0 ]
              [ 0  1 ]

Thus:

    AA^(-1) = I

**Conclusion**

The product of A and its calculated inverse is the identity matrix.

Therefore, the inverse of A is:

    A^(-1) = [  2    -1   ]
             [ -5/2   3/2 ]

The result is verified and the inverse matrix is correct.