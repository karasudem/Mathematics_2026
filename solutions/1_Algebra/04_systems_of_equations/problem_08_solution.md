## Question

Consider the following two systems of linear equations.

**System 1:**

2x + y = 5

x - y = 1

**System 2:**

2x + y = 1

x - y = 4

Solve both systems using Gaussian elimination.

Compare the elimination steps and explain which parts of the calculations are common and which parts are different.

**Why this exercise:** Understand how systems with the same coefficient matrix can be solved efficiently by reusing common elimination steps.

## Solution

**Step 1: Write the augmented matrices**

Both systems have the same coefficients for x and y.

The coefficient matrix is:

A = [2   1]
    [1  -1]

For System 1, the augmented matrix is:

[2   1  |  5]
[1  -1  |  1]

For System 2, the augmented matrix is:

[2   1  |  1]
[1  -1  |  4]

**Step 2: Solve System 1 using Gaussian elimination**

Start with:

[2   1  |  5]
[1  -1  |  1]

Swap the two rows:

R1 <-> R2

The matrix becomes:

[1  -1  |  1]
[2   1  |  5]

Eliminate the x coefficient in Row 2:

R2 <- R2 - 2R1

The matrix becomes:

[1  -1  |  1]
[0   3  |  3]

The second row represents:

3y = 3

Therefore:

y = 1

Substitute y = 1 into the first row:

x - y = 1

x - 1 = 1

x = 2

The solution of System 1 is:

x = 2

y = 1

**Step 3: Verify System 1**

First equation:

2x + y = 5

2(2) + 1 = 5

5 = 5

Second equation:

x - y = 1

2 - 1 = 1

1 = 1

Both equations are satisfied.

**Step 4: Solve System 2 using Gaussian elimination**

Start with:

[2   1  |  1]
[1  -1  |  4]

Swap the two rows:

R1 <-> R2

The matrix becomes:

[1  -1  |  4]
[2   1  |  1]

Eliminate the x coefficient in Row 2:

R2 <- R2 - 2R1

The matrix becomes:

[1  -1  |  4]
[0   3  | -7]

The second row represents:

3y = -7

Therefore:

y = -7/3

Substitute y = -7/3 into the first row:

x - y = 4

x - (-7/3) = 4

x + 7/3 = 4

x = 4 - 7/3

x = 12/3 - 7/3

x = 5/3

The solution of System 2 is:

x = 5/3

y = -7/3

**Step 5: Verify System 2**

First equation:

2x + y = 1

2(5/3) + (-7/3) = 1

10/3 - 7/3 = 1

3/3 = 1

1 = 1

Second equation:

x - y = 4

5/3 - (-7/3) = 4

5/3 + 7/3 = 4

12/3 = 4

4 = 4

Both equations are satisfied.

**Step 6: Compare the elimination steps**

Both systems have the same coefficient matrix:

A = [2   1]
    [1  -1]

Therefore, the row operations on the coefficient part are identical.

In both systems, we:

1. Swap Row 1 and Row 2.
2. Apply R2 <- R2 - 2R1.

The resulting coefficient matrix is the same:

[1  -1]
[0   3]

However, the right-hand sides are different.

For System 1, the resulting right-hand side is:

[1]
[3]

For System 2, the resulting right-hand side is:

[ 4]
[-7]

Therefore, the final values of x and y are different.

**Final Answer:**

System 1:

x = 2, y = 1

System 2:

x = 5/3, y = -7/3

Both systems have exactly one solution.

The elimination steps on the coefficient matrix can be reused because both systems have the same coefficient matrix. Only the right-hand side calculations and final solutions are different.