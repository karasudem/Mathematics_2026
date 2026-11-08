## Question

Consider the following system of linear equations:

x + y + z = 2

2x + 2y + 2z = 4

x - y + z = 0

Determine whether the system has one solution, infinitely many solutions, or no solution.

Find the parametric form of the solution. Identify the free variable, choose a parameter, and verify that the parametric solution satisfies the original equations.

**Why this exercise:** Understand how dependent equations and free variables lead to infinitely many solutions.

## Solution

**Step 1: Write the augmented matrix**

The system is:

x + y + z = 2

2x + 2y + 2z = 4

x - y + z = 0

The augmented matrix is:

[1   1   1  |  2]
[2   2   2  |  4]
[1  -1   1  |  0]

**Step 2: Apply Gaussian elimination**

First, eliminate the x coefficient in Row 2 and Row 3.

Apply:

R2 <- R2 - 2R1

R3 <- R3 - R1

The matrix becomes:

[1   1   1  |  2]
[0   0   0  |  0]
[0  -2   0  | -2]

Swap Row 2 and Row 3:

R2 <-> R3

The matrix becomes:

[1   1   1  |  2]
[0  -2   0  | -2]
[0   0   0  |  0]

**Step 3: Simplify the second row**

Divide Row 2 by -2.

Apply:

R2 <- (-1/2)R2

The matrix becomes:

[1   1   1  |  2]
[0   1   0  |  1]
[0   0   0  |  0]

**Step 4: Express the equations**

The resulting matrix represents:

x + y + z = 2

y = 1

The third row represents:

0 = 0

This is always true and gives no additional restriction.

Substitute y = 1 into the first equation:

x + 1 + z = 2

Therefore:

x + z = 1

**Step 5: Identify the free variable**

There are three variables but only two pivot positions.

Therefore, one variable is free.

Choose z as the free variable and let:

z = t

where t is any real number.

From x + z = 1:

x = 1 - t

We already know:

y = 1

**Step 6: Write the parametric solution**

The parametric form is:

x = 1 - t

y = 1

z = t

where t belongs to the real numbers.

In vector form:

[x, y, z] = [1 - t, 1, t]

**Step 7: Verify the solution**

Substitute x = 1 - t, y = 1, and z = t into all three original equations.

First equation:

x + y + z = 2

(1 - t) + 1 + t = 2

2 = 2

Second equation:

2x + 2y + 2z = 4

2(1 - t) + 2(1) + 2t = 4

2 - 2t + 2 + 2t = 4

4 = 4

Third equation:

x - y + z = 0

(1 - t) - 1 + t = 0

0 = 0

All three equations are satisfied for every real value of t.

**Step 8: Explain why the system has infinitely many solutions**

The system has three variables but only two pivot positions.

Therefore, one variable is free.

Since t can be any real number, there are infinitely many possible solutions.

There is no contradictory row, so the system is consistent.

**Final Answer:**

x = 1 - t

y = 1

z = t

where t is any real number.

The system has infinitely many solutions.