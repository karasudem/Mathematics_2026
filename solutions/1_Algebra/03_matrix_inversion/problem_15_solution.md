## Question

Given the matrices:

A =

    [ 2  1 ]
    [ 1  3 ]

and

b =

    [ 7 ]
    [ 8 ]

Solve Ax = b in two ways:

1. Using A^(-1)b.
2. Using Gaussian elimination.

Compare both solutions, the number of essential steps, and state which method was simpler in this example.

## Solution

We are given the linear system:

    Ax = b

where:

    A = [ 2  1 ]
        [ 1  3 ]

    b = [ 7 ]
        [ 8 ]

We will solve this system using two different methods and compare the results.

**Method 1: Solving Using the Inverse Matrix**

**Step 1: Calculate the determinant of A**

The determinant of a 2x2 matrix is:

    det(A) = ad - bc

Substituting the values:

    det(A) = (2 * 3) - (1 * 1)

    det(A) = 6 - 1

    det(A) = 5

Since the determinant is non-zero, the inverse of A exists.

**Step 2: Calculate A^(-1)**

Using the inverse formula:

    A^(-1) = 1/(ad - bc) * [  d  -b ]
                              [ -c   a ]

Substituting the values:

    A^(-1) = 1/5 * [  3  -1 ]
                    [ -1   2 ]

Therefore:

    A^(-1) = [  3/5  -1/5 ]
             [ -1/5   2/5 ]

**Step 3: Calculate x = A^(-1)b**

We use the formula:

    x = A^(-1)b

Substituting the matrices:

    x = [  3/5  -1/5 ]   [ 7 ]
        [ -1/5   2/5 ] × [ 8 ]

Calculating each entry:

    x = [ (3/5)(7) + (-1/5)(8) ]
        [ (-1/5)(7) + (2/5)(8) ]

Simplifying:

    x = [ 21/5 - 8/5 ]
        [ -7/5 + 16/5 ]

Therefore:

    x = [ 13/5 ]
        [  9/5 ]

The solution using the inverse matrix method is:

    x1 = 13/5
    x2 = 9/5

**Method 2: Solving Using Gaussian Elimination**

We start with the augmented matrix [A | b]:

    [A | b] = [ 2  1 | 7 ]
              [ 1  3 | 8 ]

**Step 1: Exchange the rows**

To obtain a leading 1 in the first row, exchange R1 and R2:

    R1 <-> R2

The resulting matrix is:

    [ 1  3 | 8 ]
    [ 2  1 | 7 ]

**Step 2: Eliminate the first entry in the second row**

Apply the row operation:

    R2 -> R2 - 2R1

The resulting matrix is:

    [ 1  3 |  8  ]
    [ 0 -5 | -9  ]

**Step 3: Solve for x2**

The second row represents:

    -5x2 = -9

Therefore:

    x2 = 9/5

**Step 4: Solve for x1**

The first row represents:

    x1 + 3x2 = 8

Substituting x2 = 9/5:

    x1 + 3(9/5) = 8

    x1 + 27/5 = 40/5

    x1 = 40/5 - 27/5

Therefore:

    x1 = 13/5

The solution using Gaussian elimination is:

    x1 = 13/5
    x2 = 9/5

**Step 5: Compare the two methods**

The inverse matrix method gives:

    x = [ 13/5 ]
        [  9/5 ]

Gaussian elimination gives:

    x = [ 13/5 ]
        [  9/5 ]

Both methods produce exactly the same solution.

The inverse matrix method requires calculating the determinant, finding the inverse matrix, and multiplying it by b.

Gaussian elimination requires constructing an augmented matrix, performing row operations, and solving the resulting equations.

For this particular 2x2 system, Gaussian elimination is simpler because it requires fewer calculations and avoids finding the entire inverse matrix.

However, the inverse matrix method is useful for understanding the relationship between inverse matrices and linear systems.

**Conclusion**

Both methods give the same solution:

    x = [ 13/5 ]
        [  9/5 ]

Therefore:

    x1 = 13/5
    x2 = 9/5

For this example, Gaussian elimination is the simpler method because it involves fewer essential calculations than finding the inverse matrix.