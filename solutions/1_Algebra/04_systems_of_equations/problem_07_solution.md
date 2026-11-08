## Question

Consider the following three situations and choose an appropriate method for solving each one.

**Situation 1:**

A triangular system is given:

2x - y = 3

4y = 8

Solve the system completely.

**Situation 2:**

Three systems have the same invertible coefficient matrix A, but different right-hand sides:

Ax = b1

Ax = b2

Ax = b3

The inverse matrix A^-1 is already known.

Describe an efficient solution plan and explain which parts of the work can be reused.

**Situation 3:**

A single 3x3 system is given. Its inverse matrix is not provided, and only one solution vector is required.

Describe an appropriate method and explain which unnecessary calculations should be avoided.

For each situation, justify the choice of method based on the structure of the system and the number of right-hand sides.

**Why this exercise:** Learn to choose an efficient solution method instead of applying the same method to every linear system.

## Solution

**Step 1: Solve Situation 1 using back substitution**

The system is:

2x - y = 3

4y = 8

The second equation contains only y.

First, solve for y:

4y = 8

y = 8 / 4

y = 2

Now substitute y = 2 into the first equation:

2x - y = 3

2x - 2 = 3

2x = 5

x = 5 / 2

Therefore:

x = 5/2

y = 2

**Verification:**

First equation:

2(5/2) - 2 = 3

5 - 2 = 3

3 = 3

Second equation:

4(2) = 8

8 = 8

Both equations are satisfied.

**Conclusion:**

Back substitution is the most efficient method because the system is already triangular. There is no need to perform additional Gaussian elimination.

**Step 2: Choose a method for Situation 2**

We are given three systems:

Ax = b1

Ax = b2

Ax = b3

The coefficient matrix A is the same in all three systems, and A^-1 is already known.

Since A is invertible, the solution of each system is:

x1 = A^-1 b1

x2 = A^-1 b2

x3 = A^-1 b3

The efficient plan is:

1. Use the already known inverse matrix A^-1.
2. Multiply A^-1 by b1 to obtain x1.
3. Multiply A^-1 by b2 to obtain x2.
4. Multiply A^-1 by b3 to obtain x3.

The matrix A^-1 does not need to be calculated again.

The common part of the work is the inverse matrix A^-1. Only the multiplication with each different right-hand side needs to be performed separately.

**Conclusion:**

Using the inverse matrix is efficient in this situation because the same invertible coefficient matrix is used for multiple right-hand sides, and its inverse is already available.

**Step 3: Choose a method for Situation 3**

We are given one 3x3 system:

Ax = b

The inverse matrix A^-1 is not provided, and only one solution vector is required.

The recommended method is Gaussian elimination.

The plan is:

1. Write the augmented matrix [A | b].
2. Apply elementary row operations to obtain row echelon form.
3. Continue until the system is in upper triangular form.
4. Use back substitution to find the values of the unknown variables.
5. Substitute the solution into the original equations to verify the result.

There is no need to calculate the entire inverse matrix A^-1.

Calculating the inverse would require additional work that is unnecessary when only one solution vector is needed.

**Conclusion:**

Gaussian elimination followed by back substitution is an efficient method for solving one system when the inverse matrix is not given.

**Step 4: Compare the three situations**

Situation 1:

Method: Back substitution.

Reason: The system is already triangular, so it can be solved directly.

Situation 2:

Method: Matrix multiplication using A^-1.

Reason: The inverse is already known and the same coefficient matrix is used for three different right-hand sides.

Situation 3:

Method: Gaussian elimination followed by back substitution.

Reason: Only one solution vector is needed, so calculating the entire inverse matrix would be unnecessary.

**Final Answer:**

- Situation 1: Use back substitution.
- Situation 2: Use the known inverse matrix A^-1 for each right-hand side.
- Situation 3: Use Gaussian elimination and back substitution.

The most efficient method depends on the structure of the system, the available information, and the number of right-hand sides.