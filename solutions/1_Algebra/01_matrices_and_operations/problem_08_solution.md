Exercise 8. Row Operations and Their Reversibility

Given Matrix

A =

[  1   2  -1 ]
[  2   4   1 ]
[ -1   1   3 ]

We perform the three given row operations in the specified order.

1. First Operation: R2 <- R2 - 2R1

The first row remains unchanged.

We calculate the new second row:

R2 = (2, 4, 1) - 2(1, 2, -1)

R2 = (2, 4, 1) - (2, 4, -2)

R2 = (0, 0, 3)

The third row remains unchanged.

The resulting matrix is:

[  1   2  -1 ]
[  0   0   3 ]
[ -1   1   3 ]

Reverse operation:

To undo this operation, we use:

R2 <- R2 + 2R1

This restores the original second row.

2. Second Operation: R3 <- R3 + R1

We calculate the new third row:

R3 = (-1, 1, 3) + (1, 2, -1)

R3 = (0, 3, 2)

The first and second rows remain unchanged.

The resulting matrix is:

[ 1   2  -1 ]
[ 0   0   3 ]
[ 0   3   2 ]

Reverse operation:

To undo this operation, we use:

R3 <- R3 - R1

This restores the previous third row.

3. Third Operation: Interchange R2 and R3

We exchange the second and third rows.

The resulting matrix is:

[ 1   2  -1 ]
[ 0   3   2 ]
[ 0   0   3 ]

Reverse operation:

To undo this operation, we interchange R2 and R3 again.

Swapping the same two rows twice restores the original order.

4. Verification

Each row operation has an inverse:

* R2 <- R2 - 2R1 is reversed by R2 <- R2 + 2R1.
* R3 <- R3 + R1 is reversed by R3 <- R3 - R1.
* Interchanging R2 and R3 is reversed by interchanging them again.

These reverse operations restore the matrix from before each individual operation.

Final Answer

The final matrix is:

[ 1   2  -1 ]
[ 0   3   2 ]
[ 0   0   3 ]

All three row operations are reversible.

Elementary row operations allow us to transform a matrix while preserving the ability to return to its previous form.