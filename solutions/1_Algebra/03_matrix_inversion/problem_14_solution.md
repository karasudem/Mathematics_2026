## Question

Assume that a square matrix A satisfies:

    A^2 = I

Show that:

    A^(-1) = A

Then give an example of a 2x2 matrix different from I and -I that satisfies this condition, and verify it by multiplication.

## Solution

We are given that a square matrix A satisfies:

    A^2 = I

This means:

    AA = I

According to the definition of the inverse matrix, a matrix A^(-1) satisfies:

    AA^(-1) = I

and

    A^(-1)A = I

We will use the given condition to show that A is its own inverse.

**Step 1: Prove that A^(-1) = A**

We know that:

    A^2 = I

By the definition of matrix multiplication:

    AA = I

This means that multiplying A by itself gives the identity matrix.

Since the inverse of A is the matrix that produces the identity matrix when multiplied by A, we can conclude that:

    A^(-1) = A

Therefore, A is its own inverse.

**Step 2: Give an example of a 2x2 matrix**

Consider the following matrix:

    A = [ 0  1 ]
        [ 1  0 ]

The identity matrix is:

    I = [ 1  0 ]
        [ 0  1 ]

The negative identity matrix is:

    -I = [ -1   0 ]
         [  0  -1 ]

The chosen matrix A is different from both I and -I.

**Step 3: Verify the condition by multiplication**

We need to check whether:

    A^2 = I

Calculate A multiplied by itself:

    A^2 = [ 0  1 ]   [ 0  1 ]
          [ 1  0 ] × [ 1  0 ]

Calculating each entry:

    A^2 = [ 0(0) + 1(1)    0(1) + 1(0) ]
          [ 1(0) + 0(1)    1(1) + 0(0) ]

Simplifying:

    A^2 = [ 0 + 1    0 + 0 ]
          [ 0 + 0    1 + 0 ]

Therefore:

    A^2 = [ 1  0 ]
          [ 0  1 ]

Thus:

    A^2 = I

The condition is satisfied.

**Step 4: Verify that A is its own inverse**

Since:

    A^2 = I

we have:

    AA = I

and:

    A^(-1) = A

Therefore:

    A^(-1) = [ 0  1 ]
             [ 1  0 ]

**Conclusion**

If a square matrix satisfies A^2 = I, then multiplying the matrix by itself gives the identity matrix.

According to the definition of the inverse, this means:

    A^(-1) = A

The example:

    A = [ 0  1 ]
        [ 1  0 ]

satisfies this condition because:

    A^2 = I

It is also different from both I and -I.

Therefore, the example demonstrates that a matrix can be its own inverse.