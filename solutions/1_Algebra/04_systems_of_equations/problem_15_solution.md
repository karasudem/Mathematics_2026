## Question

Classify the following three systems of linear equations.

**System 1:**

x + y = 2

x - y = 0

**System 2:**

x + y = 2

2x + 2y = 4

**System 3:**

x + y = 2

2x + 2y = 5

For each system:

- Use Gaussian elimination with as few row operations as possible.
- Determine whether the system has exactly one solution, infinitely many solutions, or no solution.
- Explain the reason for each classification.

**Why this exercise:** Understand how Gaussian elimination can classify linear systems based on their pivot positions, free variables, and contradictory rows.

## Solution

**Step 1: Analyze System 1**

The system is:

x + y = 2

x - y = 0

Write the augmented matrix:

[1   1  |  2]
[1  -1  |  0]

Apply:

R2 <- R2 - R1

The matrix becomes:

[1   1  |  2]
[0  -2  | -2]

The second row represents:

-2y = -2

Therefore:

y = 1

Substitute y = 1 into the first equation:

x + y = 2

x + 1 = 2

x = 1

**Verification:**

First equation:

1 + 1 = 2

Second equation:

1 - 1 = 0

Both equations are satisfied.

There is a pivot in both variable columns, so there are no free variables.

**Conclusion for System 1:**

The system has exactly one solution:

x = 1

y = 1

**Step 2: Analyze System 2**

The system is:

x + y = 2

2x + 2y = 4

Write the augmented matrix:

[1   1  |  2]
[2   2  |  4]

Apply:

R2 <- R2 - 2R1

The matrix becomes:

[1   1  |  2]
[0   0  |  0]

The second row represents:

0 = 0

This equation is always true and gives no additional restriction.

The remaining equation is:

x + y = 2

Choose y as a free variable:

y = t

Then:

x = 2 - t

where t is any real number.

**Verification:**

First equation:

(2 - t) + t = 2

2 = 2

Second equation:

2(2 - t) + 2t = 4

4 - 2t + 2t = 4

4 = 4

Both equations are satisfied for every real value of t.

There is one free variable and no contradiction.

**Conclusion for System 2:**

The system has infinitely many solutions:

x = 2 - t

y = t

where t is any real number.

**Step 3: Analyze System 3**

The system is:

x + y = 2

2x + 2y = 5

Write the augmented matrix:

[1   1  |  2]
[2   2  |  5]

Apply:

R2 <- R2 - 2R1

The matrix becomes:

[1   1  |  2]
[0   0  |  1]

The second row represents:

0 = 1

This is a contradiction.

Therefore, there are no values of x and y that satisfy both equations simultaneously.

**Conclusion for System 3:**

The system has no solution because Gaussian elimination produces the contradiction:

0 = 1

**Step 4: Compare the three systems**

System 1:

Resulting matrix:

[1   1  |  2]
[0  -2  | -2]

There is a pivot in both variable columns.

Classification: Exactly one solution.

Solution: x = 1, y = 1.

System 2:

Resulting matrix:

[1   1  |  2]
[0   0  |  0]

There is one free variable and no contradiction.

Classification: Infinitely many solutions.

Solution: x = 2 - t, y = t.

System 3:

Resulting matrix:

[1   1  |  2]
[0   0  |  1]

The matrix produces a contradiction.

Classification: No solution.

**Final Answer:**

- System 1: Exactly one solution, (x, y) = (1, 1).
- System 2: Infinitely many solutions, (x, y) = (2 - t, t), where t is any real number.
- System 3: No solution because it produces the contradiction 0 = 1.

The three systems demonstrate the three possible classifications of a linear system with two variables.