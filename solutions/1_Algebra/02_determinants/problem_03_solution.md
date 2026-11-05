Exercise 3 – Solution

Given:

A = [ 1  2  0 ]
[ 0  3  1 ]
[ 2  1  1 ]

We need to calculate det(A), swap the first and second rows, and calculate the determinant of the new matrix B.

Step 1: Calculate det(A)

Using expansion along the first row:

det(A) = 1 * (3 * 1 - 1 * 1) - 2 * (0 * 1 - 1 * 2)

det(A) = 1 * (3 - 1) - 2 * (0 - 2)

det(A) = 2 + 4

det(A) = 6

Step 2: Swap the First and Second Rows

The new matrix B is:

B = [ 0  3  1 ]
[ 1  2  0 ]
[ 2  1  1 ]

Step 3: Predict the New Determinant

When two rows of a matrix are swapped, the determinant changes its sign.

Therefore:

det(B) = -det(A)

det(B) = -6

Step 4: Verify by Calculation

Using expansion along the first row:

det(B) = 0 - 3 * (1 * 1 - 0 * 2) + 1 * (1 * 1 - 2 * 2)

det(B) = -3 + (1 - 4)

det(B) = -3 - 3

det(B) = -6

The result confirms our prediction.

Final Answer

det(A) = 6

det(B) = -6

Swapping two rows changes the sign of the determinant but does not change its absolute value.