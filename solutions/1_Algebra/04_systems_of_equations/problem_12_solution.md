## Question

Consider the following homogeneous system of linear equations:

x + 2y - z = 0

2x + 4y - 2z = 0

x - y + 2z = 0

Find the parametric form of the solution.

Explain why the zero vector is always a solution of a homogeneous system.

**Why this exercise:** Understand homogeneous systems, dependent equations, and the relationship between free variables and solutions.

## Solution

**Step 1: Write the augmented matrix**

The system is:

x + 2y - z = 0

2x + 4y - 2z = 0

x - y + 2z = 0

The augmented matrix is:

[1   2  -1  |  0]
[2   4  -2  |  0]
[1  -1   2  |  0]

**Step 2: Apply Gaussian elimination**

First, eliminate the x coefficient in Row 2 and Row 3.

Apply:

R2 <- R2 - 2R1

R3 <- R3 - R1

The matrix becomes:

[1   2  -1  |  0]
[0   0   0  |  0]
[0  -3   3  |  0]

Swap Row 2 and Row 3:

R2 <-> R3

The matrix becomes:

[1   2  -1  |  0]
[0  -3   3  |  0]
[0   0   0  |  0]

**Step 3: Simplify the second row**

Divide Row 2 by -3.

Apply:

R2 <- (-1/3)R2

The matrix becomes:

[1   2  -1  |  0]
[0   1  -1  |  0]
[0   0   0  |  0]

**Step 4: Express the equations**

The resulting matrix represents:

x + 2y - z = 0

y - z = 0

The third row represents:

0 = 0

From the second equation:

y - z = 0

Therefore:

y = z

Substitute y = z into the first equation:

x + 2y - z = 0

x + 2z - z = 0

x + z = 0

Therefore:

x = -z

**Step 5: Identify the free variable**

There are three variables but only two pivot positions.

Therefore, one variable is free.

Choose z as the free variable:

z = t

where t is any real number.

Since y = z:

y = t

Since x = -z:

x = -t

**Step 6: Write the parametric solution**

The parametric form is:

x = -t

y = t

z = t

where t belongs to the real numbers.

In vector form:

[x, y, z] = [-t, t, t]

or:

[x, y, z] = t[-1, 1, 1]

**Step 7: Verify the solution**

Substitute x = -t, y = t, and z = t into all three original equations.

First equation:

x + 2y - z = 0

(-t) + 2t - t = 0

0 = 0

Second equation:

2x + 4y - 2z = 0

2(-t) + 4t - 2t = 0

-2t + 4t - 2t = 0

0 = 0

Third equation:

x - y + 2z = 0

(-t) - t + 2t = 0

0 = 0

All three equations are satisfied for every real value of t.

**Step 8: Explain why the zero vector is always a solution**

A homogeneous system has the form:

Ax = 0

If we choose the zero vector:

x = [0, 0, 0]

then every variable is zero.

Multiplying any coefficient by zero gives zero.

Therefore, every equation becomes:

0 = 0

This is always true.

Consequently, the zero vector is always a solution of a homogeneous system.

For this particular system, setting t = 0 gives:

x = 0

y = 0

z = 0

**Final Answer:**

x = -t

y = t

z = t

where t is any real number.

The system has infinitely many solutions because there is one free variable.

The zero vector is always a solution of a homogeneous system.