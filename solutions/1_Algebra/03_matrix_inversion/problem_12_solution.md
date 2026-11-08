## Question

It is known that:

A^(-1) =

    [  2  -1 ]
    [ -3   2 ]

Without finding A, compute:

1. (3A)^(-1)
2. (A^T)^(-1)
3. (A^2)^(-1)

Justify each result using the appropriate property.

## Solution

We are given the inverse of matrix A:

    A^(-1) = [  2  -1 ]
             [ -3   2 ]

We can calculate the required expressions directly using the properties of inverse matrices without finding A itself.

**Step 1: Calculate (3A)^(-1)**

For an invertible matrix A and a non-zero scalar k, the following property holds:

    (kA)^(-1) = (1/k)A^(-1)

In this exercise, k = 3.

Therefore:

    (3A)^(-1) = (1/3)A^(-1)

Substituting the given inverse:

    (3A)^(-1) = (1/3) * [  2  -1 ]
                           [ -3   2 ]

Multiplying each entry by 1/3:

    (3A)^(-1) = [  2/3  -1/3 ]
                [ -1     2/3 ]

**Step 2: Calculate (A^T)^(-1)**

The inverse of a transpose satisfies the property:

    (A^T)^(-1) = (A^(-1))^T

This means that we take the transpose of the given inverse matrix.

Starting with:

    A^(-1) = [  2  -1 ]
             [ -3   2 ]

Transposing rows and columns gives:

    (A^(-1))^T = [  2  -3 ]
                 [ -1   2 ]

Therefore:

    (A^T)^(-1) = [  2  -3 ]
                 [ -1   2 ]

**Step 3: Calculate (A^2)^(-1)**

The inverse of a product satisfies the property:

    (AB)^(-1) = B^(-1)A^(-1)

Since A^2 = AA, we have:

    (A^2)^(-1) = (AA)^(-1)

Applying the inverse-of-a-product property:

    (A^2)^(-1) = A^(-1)A^(-1)

Therefore:

    (A^2)^(-1) = (A^(-1))^2

Substituting the given matrix:

    (A^2)^(-1) = [  2  -1 ]   [  2  -1 ]
                 [ -3   2 ] × [ -3   2 ]

Calculating each entry:

    (A^2)^(-1) = [ 2(2) + (-1)(-3)    2(-1) + (-1)(2) ]
                 [ (-3)(2) + 2(-3)   (-3)(-1) + 2(2) ]

Simplifying:

    (A^2)^(-1) = [ 4 + 3    -2 - 2 ]
                 [ -6 - 6    3 + 4 ]

Therefore:

    (A^2)^(-1) = [  7  -4 ]
                 [ -12   7 ]

**Conclusion**

Using the properties of inverse matrices, we obtain:

1. (3A)^(-1) =

       [  2/3  -1/3 ]
       [ -1     2/3 ]

2. (A^T)^(-1) =

       [  2  -3 ]
       [ -1   2 ]

3. (A^2)^(-1) =

       [  7  -4 ]
       [ -12   7 ]

All three expressions were calculated directly from the given inverse matrix without finding A.