## Question

Given the matrices:

S =

    [ 2  0 ]
    [ 0  1 ]

H =

    [ 1  1 ]
    [ 0  1 ]

The matrices describe nonuniform scaling and shear.

For T = HS, find T^(-1) in two ways:

1. First compute T, then its inverse.
2. Use (HS)^(-1) = S^(-1)H^(-1).

Compare the results.

Additionally, compute H^(-1)S^(-1) and verify that the incorrect order gives a different matrix.

Explain the rule: "when undoing a composition of operations, we undo them from the end."

## Solution

We are given two matrices representing geometric transformations:

    S = [ 2  0 ]
        [ 0  1 ]

    H = [ 1  1 ]
        [ 0  1 ]

The combined transformation is:

    T = HS

We will find its inverse using two different methods and compare the results.

**Step 1: Calculate T = HS**

Multiply H by S:

    T = HS

    T = [ 1  1 ]   [ 2  0 ]
        [ 0  1 ] × [ 0  1 ]

Calculating each entry:

    T = [ 1(2) + 1(0)    1(0) + 1(1) ]
        [ 0(2) + 1(0)    0(0) + 1(1) ]

Therefore:

    T = [ 2  1 ]
        [ 0  1 ]

**Step 2: Find T^(-1) directly**

Using the inverse formula for a 2x2 matrix:

    A^(-1) = 1/(ad - bc) * [  d  -b ]
                              [ -c   a ]

For matrix T:

    T = [ 2  1 ]
        [ 0  1 ]

Calculate the determinant:

    det(T) = (2 * 1) - (1 * 0)

    det(T) = 2

Since the determinant is non-zero, the inverse exists.

Applying the formula:

    T^(-1) = 1/2 * [ 1  -1 ]
                    [ 0   2 ]

Therefore:

    T^(-1) = [ 1/2  -1/2 ]
             [  0     1  ]

**Step 3: Calculate S^(-1) and H^(-1)**

First, calculate the inverse of S:

    S = [ 2  0 ]
        [ 0  1 ]

Its determinant is:

    det(S) = 2 * 1 = 2

Therefore:

    S^(-1) = [ 1/2  0 ]
             [  0   1 ]

Now calculate the inverse of H:

    H = [ 1  1 ]
        [ 0  1 ]

Its determinant is:

    det(H) = (1 * 1) - (1 * 0)

    det(H) = 1

Therefore:

    H^(-1) = [ 1  -1 ]
             [ 0   1 ]

**Step 4: Calculate the inverse using the inverse-of-a-product property**

The inverse of a product reverses the order of the matrices:

    (HS)^(-1) = S^(-1)H^(-1)

Substituting the inverse matrices:

    S^(-1)H^(-1) = [ 1/2  0 ]   [ 1  -1 ]
                   [  0   1 ] × [ 0   1 ]

Calculating each entry:

    S^(-1)H^(-1) = [ (1/2)(1) + 0(0)    (1/2)(-1) + 0(1) ]
                   [ 0(1) + 1(0)        0(-1) + 1(1) ]

Therefore:

    S^(-1)H^(-1) = [ 1/2  -1/2 ]
                   [  0     1  ]

**Step 5: Compare the results**

The first method gave:

    T^(-1) = [ 1/2  -1/2 ]
             [  0     1  ]

The second method gave:

    S^(-1)H^(-1) = [ 1/2  -1/2 ]
                   [  0     1  ]

Both methods give the same result.

Therefore:

    (HS)^(-1) = S^(-1)H^(-1)

**Step 6: Calculate H^(-1)S^(-1) and compare**

Now calculate the product in the incorrect order:

    H^(-1)S^(-1) = [ 1  -1 ]   [ 1/2  0 ]
                   [ 0   1 ] × [  0   1 ]

Calculating each entry:

    H^(-1)S^(-1) = [ 1(1/2) + (-1)(0)    1(0) + (-1)(1) ]
                   [ 0(1/2) + 1(0)      0(0) + 1(1) ]

Therefore:

    H^(-1)S^(-1) = [ 1/2  -1 ]
                   [  0    1 ]

This is different from the correct inverse:

    S^(-1)H^(-1) = [ 1/2  -1/2 ]
                   [  0     1  ]

Thus:

    H^(-1)S^(-1) != S^(-1)H^(-1)

The order of multiplication matters.

**Step 7: Explain the meaning of the reversed order**

The original transformation is:

    T = HS

When a vector is multiplied by HS, the scaling transformation S is applied first, followed by the shear transformation H.

To undo this combined transformation, we must reverse the order:

1. First undo the shear transformation using H^(-1).
2. Then undo the scaling transformation using S^(-1).

Therefore, the inverse is:

    T^(-1) = S^(-1)H^(-1)

This illustrates the rule:

"When undoing a composition of operations, we undo them from the end."

**Conclusion**

Both methods give the same inverse matrix:

    T^(-1) = [ 1/2  -1/2 ]
             [  0     1  ]

The inverse-of-a-product property requires reversing the order of the inverse matrices.

Calculating H^(-1)S^(-1) gives a different result, confirming that matrix multiplication order is important.