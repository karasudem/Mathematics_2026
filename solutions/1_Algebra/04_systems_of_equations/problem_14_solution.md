## Question

Consider the following system of linear equations:

**Original system:**

x + y = 2

2x - y = 1

3x = 3

Now consider a modified system in which only the right-hand side of the third equation changes:

x + y = 2

2x - y = 1

3x = 3.1

Check whether each system is consistent.

Explain why a small change in the right-hand side can change the type of the system.

**Why this exercise:** Understand how a small change in the right-hand side can affect the consistency of a system of linear equations.

## Solution

**Step 1: Write the augmented matrix of the original system**

The original system is:

x + y = 2

2x - y = 1

3x = 3

The augmented matrix is:

[1   1  |  2]
[2  -1  |  1]
[3   0  |  3]

**Step 2: Apply Gaussian elimination to the original system**

Eliminate the x coefficient in Row 2.

Apply:

R2 <- R2 - 2R1

Eliminate the x coefficient in Row 3.

Apply:

R3 <- R3 - 3R1

The matrix becomes:

[1   1  |  2]
[0  -3  | -3]
[0  -3  | -3]

Now eliminate the y coefficient in Row 3.

Apply:

R3 <- R3 - R2

The resulting matrix is:

[1   1  |  2]
[0  -3  | -3]
[0   0  |  0]

**Step 3: Solve the original system**

The second row represents:

-3y = -3

Therefore:

y = 1

Substitute y = 1 into the first equation:

x + y = 2

x + 1 = 2

x = 1

The solution is:

x = 1

y = 1

**Step 4: Verify the original system**

First equation:

x + y = 2

1 + 1 = 2

2 = 2

Second equation:

2x - y = 1

2(1) - 1 = 1

1 = 1

Third equation:

3x = 3

3(1) = 3

3 = 3

All three equations are satisfied.

Therefore, the original system is consistent and has exactly one solution.

**Step 5: Write the augmented matrix of the modified system**

The modified system is:

x + y = 2

2x - y = 1

3x = 3.1

Its augmented matrix is:

[1   1  |  2]
[2  -1  |  1]
[3   0  |  3.1]

**Step 6: Apply Gaussian elimination to the modified system**

Eliminate the x coefficient in Row 2.

Apply:

R2 <- R2 - 2R1

Eliminate the x coefficient in Row 3.

Apply:

R3 <- R3 - 3R1

The matrix becomes:

[1   1  |  2]
[0  -3  | -3]
[0  -3  | -2.9]

Now eliminate the y coefficient in Row 3.

Apply:

R3 <- R3 - R2

The resulting matrix is:

[1   1  |  2]
[0  -3  | -3]
[0   0  |  0.1]

**Step 7: Interpret the modified system**

The third row represents:

0x + 0y = 0.1

Therefore:

0 = 0.1

This is a contradiction.

Consequently, the modified system has no solution.

**Step 8: Explain why the small change matters**

The first two equations determine a unique solution:

x = 1

y = 1

These values require:

3x = 3

However, the modified third equation requires:

3x = 3.1

The same value of x cannot satisfy both conditions.

Even though the change from 3 to 3.1 is small, it makes the system inconsistent.

**Final Answer:**

Original system:

x = 1, y = 1

The system is consistent and has exactly one solution.

Modified system:

The system has no solution because Gaussian elimination produces the contradiction:

0 = 0.1

A small change in the right-hand side can make a system inconsistent when it contradicts the conditions imposed by the other equations.