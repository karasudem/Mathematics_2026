## Question

Given the matrices:

A =

    [ 1  1 ]
    [ 0  1 ]

B =

    [ 2  0 ]
    [ 0  3 ]

Compute (AB)^(-1) and B^(-1)A^(-1).

Check that the results are the same and explain the meaning of the reversed order.

## Solution

The inverse of a product of two invertible matrices is equal to the product of their inverses in reverse order.

The property is:

    (AB)^(-1) = B^(-1)A^(-1)

First, we calculate (AB)^(-1) directly. Then, we calculate B^(-1)A^(-1) and compare the results.

**Step 1: Calculate AB**

The given matrices are:

    A = [ 1  1 ]
        [ 0  1 ]

    B = [ 2  0 ]
        [ 0  3 ]

Multiplying A by B:

    AB = [ 1  1 ]   [ 2  0 ]
         [ 0  1 ] × [ 0  3 ]

    AB = [ 1(2) + 1(0)    1(0) + 1(3) ]
         [ 0(2) + 1(0)    0(0) + 1(3) ]

Therefore:

    AB = [ 2  3 ]
         [ 0  3 ]

**Step 2: Calculate (AB)^(-1)**

Using the inverse formula for a 2x2 matrix:

    M^(-1) = 1/(ad - bc) * [  d  -b ]
                               [ -c   a ]

For the matrix AB:

    AB = [ 2  3 ]
         [ 0  3 ]

Its determinant is:

    det(AB) = (2 * 3) - (3 * 0)

    det(AB) = 6

Since the determinant is non-zero, the inverse exists.

Applying the formula:

    (AB)^(-1) = 1/6 * [  3  -3 ]
                       [  0   2 ]

Therefore:

    (AB)^(-1) = [ 1/2  -1/2 ]
                [  0    1/3 ]

**Step 3: Calculate A^(-1)**

The matrix A is:

    A = [ 1  1 ]
        [ 0  1 ]

Its determinant is:

    det(A) = (1 * 1) - (1 * 0)

    det(A) = 1

Applying the inverse formula:

    A^(-1) = 1/1 * [  1  -1 ]
                     [  0   1 ]

Therefore:

    A^(-1) = [ 1  -1 ]
             [ 0   1 ]

**Step 4: Calculate B^(-1)**

The matrix B is:

    B = [ 2  0 ]
        [ 0  3 ]

Its determinant is:

    det(B) = (2 * 3) - (0 * 0)

    det(B) = 6

Applying the inverse formula:

    B^(-1) = 1/6 * [ 3   0 ]
                      [ 0   2 ]

Therefore:

    B^(-1) = [ 1/2   0   ]
             [  0    1/3 ]

**Step 5: Calculate B^(-1)A^(-1)**

We multiply the two inverse matrices in the reversed order:

    B^(-1)A^(-1) = [ 1/2   0   ]   [ 1  -1 ]
                   [  0    1/3 ] × [ 0   1 ]

Calculating each entry:

    B^(-1)A^(-1) = [ (1/2)(1) + 0(0)    (1/2)(-1) + 0(1) ]
                   [ 0(1) + (1/3)(0)   0(-1) + (1/3)(1) ]

Therefore:

    B^(-1)A^(-1) = [ 1/2  -1/2 ]
                   [  0    1/3 ]

**Step 6: Compare the results**

We obtained:

    (AB)^(-1) = [ 1/2  -1/2 ]
                [  0    1/3 ]

and:

    B^(-1)A^(-1) = [ 1/2  -1/2 ]
                   [  0    1/3 ]

Both matrices are equal.

Therefore:

    (AB)^(-1) = B^(-1)A^(-1)

**Step 7: Explain the reversed order**

The order is reversed because matrix multiplication is not generally commutative.

When we multiply A by B, the operation represented by B is applied first to a vector, followed by the operation represented by A.

To undo the combined operation, we must first undo the operation represented by A and then undo the operation represented by B.

Therefore, the inverse matrices must appear in reverse order:

    (AB)^(-1) = B^(-1)A^(-1)

**Conclusion**

The direct calculation of (AB)^(-1) and the calculation of B^(-1)A^(-1) give the same result.

Thus, the inverse of a product is obtained by reversing the order of the inverse matrices:

    (AB)^(-1) = B^(-1)A^(-1)