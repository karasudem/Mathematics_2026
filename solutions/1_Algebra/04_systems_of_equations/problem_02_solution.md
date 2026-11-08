## Question

Solve the following system of linear equations using Gaussian elimination:

x + y + z = 6

2x - y + z = 3

x + 2y - z = 2

After finding the solution, substitute the values into all three original equations to verify that the system is consistent.

Explain why the system has exactly one solution.

**Why this exercise:** Practice solving a system of linear equations using elementary row operations and verifying the result.

## Solution

**Step 1: Write the augmented matrix**

First, write the coefficients of x, y, and z, followed by the right-hand side of each equation.

The augmented matrix is:

[1   1   1  |  6]
[2  -1   1  |  3]
[1   2  -1  |  2]

**Step 2: Apply Gaussian elimination**

Our goal is to create zeros below the main diagonal.

First, eliminate the x coefficient in Row 2 and Row 3.

Apply:

R2 <- R2 - 2R1

R3 <- R3 - R1

The matrix becomes:

[1   1   1  |   6]
[0  -3  -1  |  -9]
[0   1  -2  |  -4]

**Step 3: Swap Row 2 and Row 3**

To make the next calculation easier, swap the second and third rows.

Apply:

R2 <-> R3

The matrix becomes:

[1   1   1  |   6]
[0   1  -2  |  -4]
[0  -3  -1  |  -9]

**Step 4: Eliminate the y coefficient in Row 3**

Apply:

R3 <- R3 + 3R2

Calculate the new third row:

[0  -3  -1  |  -9]
+ 3[0   1  -2  |  -4]
= [0   0  -7  | -21]

The resulting matrix is:

[1   1   1  |   6]
[0   1  -2  |  -4]
[0   0  -7  | -21]

This is an upper triangular system.

**Step 5: Solve using back substitution**

Start with the last row:

-7z = -21

z = 3

Now use the second row:

y - 2z = -4

Substitute z = 3:

y - 2(3) = -4

y - 6 = -4

y = 2

Finally, use the first row:

x + y + z = 6

Substitute y = 2 and z = 3:

x + 2 + 3 = 6

x = 1

Therefore:

x = 1
y = 2
z = 3

**Step 6: Verify the solution**

Substitute x = 1, y = 2, and z = 3 into all three original equations.

First equation:

x + y + z = 6

1 + 2 + 3 = 6

6 = 6

Second equation:

2x - y + z = 3

2(1) - 2 + 3 = 3

2 - 2 + 3 = 3

3 = 3

Third equation:

x + 2y - z = 2

1 + 2(2) - 3 = 2

1 + 4 - 3 = 2

2 = 2

All three equations are satisfied.

**Step 7: Explain why the system has exactly one solution**

After Gaussian elimination, the matrix has three pivot positions:

[1   1   1  |   6]
[0   1  -2  |  -4]
[0   0  -7  | -21]

Each variable (x, y, and z) has a pivot.

There are no free variables and no contradictory rows.

Therefore, the system has exactly one solution.

**Final Answer:**

x = 1, y = 2, z = 3

The system is consistent and has exactly one solution.