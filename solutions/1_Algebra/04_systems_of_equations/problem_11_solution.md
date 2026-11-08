## Question

Consider the following system of linear equations:

x + y + z = 1

x + ty + z = 2

x + y + tz = 3

Analyze the number of solutions depending on the parameter t.

Use Gaussian elimination and separately analyze the values of t for which a standard elimination step becomes invalid.

**Why this exercise:** Understand how a parameter affects the rank of a coefficient matrix and the number of solutions.

## Solution

**Step 1: Write the augmented matrix**

The system is:

x + y + z = 1

x + ty + z = 2

x + y + tz = 3

The augmented matrix is:

[1   1   1  |  1]
[1   t   1  |  2]
[1   1   t  |  3]

**Step 2: Apply Gaussian elimination**

Eliminate the x coefficient in Row 2 and Row 3.

Apply:

R2 <- R2 - R1

R3 <- R3 - R1

The matrix becomes:

[1   1       1  |  1]
[0   t - 1   0  |  1]
[0   0       t - 1  |  2]

The resulting equations are:

x + y + z = 1

(t - 1)y = 1

(t - 1)z = 2

**Step 3: Analyze the case t != 1**

If t is not equal to 1, then:

t - 1 != 0

We can divide the second and third equations by t - 1.

From the second equation:

(t - 1)y = 1

y = 1 / (t - 1)

From the third equation:

(t - 1)z = 2

z = 2 / (t - 1)

Now substitute these values into the first equation:

x + y + z = 1

x + 1/(t - 1) + 2/(t - 1) = 1

x + 3/(t - 1) = 1

Therefore:

x = 1 - 3/(t - 1)

Combining the terms:

x = (t - 4)/(t - 1)

The unique solution is:

x = (t - 4)/(t - 1)

y = 1/(t - 1)

z = 2/(t - 1)

Therefore, when t != 1, the system has exactly one solution.

**Step 4: Analyze the special case t = 1**

When t = 1, the augmented matrix becomes:

[1   1   1  |  1]
[0   0   0  |  1]
[0   0   0  |  2]

The second row represents:

0 = 1

The third row represents:

0 = 2

Both equations are contradictions.

Therefore, the system has no solution when t = 1.

We cannot divide by t - 1 in this case because t - 1 equals zero.

**Step 5: Determine whether infinitely many solutions are possible**

For t != 1, all three variables have pivot positions, so there is exactly one solution.

For t = 1, the elimination produces contradictory equations.

Therefore, there is no value of t that gives infinitely many solutions.

**Step 6: Summarize all cases**

Case 1: t != 1

The system has exactly one solution:

x = (t - 4)/(t - 1)

y = 1/(t - 1)

z = 2/(t - 1)

Case 2: t = 1

The system has no solution because elimination produces contradictions.

Case 3: Infinitely many solutions

This case is impossible because the only special value, t = 1, produces an inconsistent system.

**Final Answer:**

- Exactly one solution: t != 1.
- Infinitely many solutions: No value of t.
- No solution: t = 1.

The system has a unique solution for every real value of t except t = 1.