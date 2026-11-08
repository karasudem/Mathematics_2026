## Question

Consider the following system of linear equations:

x + 2y = 3

2x + 4y = 7

Determine whether the system has a solution. If it does, find the solution. If it does not, explain why.

Use Gaussian elimination to show the contradiction in the augmented matrix and interpret the result.

**Why this exercise:** Understand how Gaussian elimination can identify an inconsistent system of linear equations.

## Solution

**Step 1: Write the augmented matrix**

The system is:

x + 2y = 3

2x + 4y = 7

The augmented matrix is:

[1   2  |  3]
[2   4  |  7]

**Step 2: Apply Gaussian elimination**

Our goal is to eliminate the x coefficient in the second row.

Apply:

R2 <- R2 - 2R1

Calculate the new second row:

[2   4  |  7]
- 2[1   2  |  3]
= [0   0  |  1]

The resulting matrix is:

[1   2  |  3]
[0   0  |  1]

**Step 3: Interpret the resulting matrix**

The second row represents the equation:

0x + 0y = 1

Therefore:

0 = 1

This is a contradiction because zero cannot equal one.

**Step 4: Explain why the system has no solution**

The first equation is:

x + 2y = 3

If we multiply this equation by 2, we get:

2x + 4y = 6

However, the second equation states:

2x + 4y = 7

The left-hand sides are identical, but the right-hand sides are different.

Therefore, both equations cannot be true at the same time.

**Final Answer:**

The system has no solution.

It is an inconsistent system because Gaussian elimination produces the contradiction:

0 = 1

There is no pair of values (x, y) that satisfies both equations simultaneously.