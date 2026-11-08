## Question

Consider the following system of linear equations:

x1 + x2 = 10

x2 + x3 = 8

x1 - x3 = 2

Solve the system.

Check whether all three equations are independently necessary. Show any dependency between the equations.

**Why this exercise:** Understand how redundant equations affect a system of linear equations and how to identify dependent equations.

## Solution

**Step 1: Write the augmented matrix**

The system is:

x1 + x2 = 10

x2 + x3 = 8

x1 - x3 = 2

The augmented matrix is:

[1   1   0  |  10]
[0   1   1  |   8]
[1   0  -1  |   2]

**Step 2: Apply Gaussian elimination**

Eliminate the x1 coefficient in Row 3.

Apply:

R3 <- R3 - R1

The matrix becomes:

[1   1   0  |  10]
[0   1   1  |   8]
[0  -1  -1  |  -8]

Now eliminate the x2 coefficient in Row 3.

Apply:

R3 <- R3 + R2

The matrix becomes:

[1   1   0  |  10]
[0   1   1  |   8]
[0   0   0  |   0]

**Step 3: Interpret the resulting matrix**

The third row represents:

0 = 0

This equation is always true and does not provide any new information.

Therefore, the third equation is dependent on the first two equations.

**Step 4: Solve the system**

The first two equations are:

x1 + x2 = 10

x2 + x3 = 8

Choose x2 as the free variable:

x2 = t

From the first equation:

x1 + t = 10

Therefore:

x1 = 10 - t

From the second equation:

t + x3 = 8

Therefore:

x3 = 8 - t

The parametric solution is:

x1 = 10 - t

x2 = t

x3 = 8 - t

where t is any real number.

**Step 5: Verify the third equation**

The third original equation is:

x1 - x3 = 2

Substitute the parametric expressions:

(10 - t) - (8 - t) = 2

10 - t - 8 + t = 2

2 = 2

The third equation is automatically satisfied for every real value of t.

Therefore, it does not add an independent restriction.

**Step 6: Explain the dependency between the equations**

The first equation is:

x1 + x2 = 10

The second equation is:

x2 + x3 = 8

Subtract the second equation from the first:

(x1 + x2) - (x2 + x3) = 10 - 8

Simplify:

x1 - x3 = 2

This is exactly the third equation.

Therefore, the third equation can be obtained by subtracting the second equation from the first.

All three equations are not independently necessary.

**Step 7: Determine the number of solutions**

There are three variables but only two pivot positions.

Therefore, one variable is free.

There is no contradictory row.

Consequently, the system has infinitely many solutions.

**Final Answer:**

x1 = 10 - t

x2 = t

x3 = 8 - t

where t is any real number.

The system has infinitely many solutions.

The third equation is redundant because it can be obtained by subtracting the second equation from the first.