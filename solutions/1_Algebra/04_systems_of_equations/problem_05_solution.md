## Question

Consider the following augmented matrix in row echelon form:

[1   2  -1  |  3]
[0   1   2  |  1]
[0   0   0  |  0]

Determine the number of solutions.

Find the parametric form of the solution and explain which variables are free and why.

**Why this exercise:** Learn how to identify pivot variables and free variables from a matrix in row echelon form.

## Solution

**Step 1: Write the system of equations**

The augmented matrix represents the following system:

x + 2y - z = 3

y + 2z = 1

0 = 0

**Step 2: Identify the pivot variables**

A pivot is the first nonzero entry in a nonzero row.

The matrix is:

[1   2  -1  |  3]
[0   1   2  |  1]
[0   0   0  |  0]

There are two pivot positions:

- The first pivot is in the x column.
- The second pivot is in the y column.

There is no pivot in the z column.

Therefore:

- x is a pivot variable.
- y is a pivot variable.
- z is a free variable.

**Step 3: Express the pivot variables**

From the second equation:

y + 2z = 1

Solve for y:

y = 1 - 2z

Substitute this expression into the first equation:

x + 2y - z = 3

x + 2(1 - 2z) - z = 3

x + 2 - 4z - z = 3

x - 5z = 1

Therefore:

x = 1 + 5z

**Step 4: Introduce a parameter**

Since z is a free variable, choose:

z = t

where t is any real number.

Then:

x = 1 + 5t

y = 1 - 2t

z = t

**Step 5: Write the parametric solution**

The parametric form is:

x = 1 + 5t

y = 1 - 2t

z = t

where t belongs to the real numbers.

In vector form:

[x, y, z] = [1 + 5t, 1 - 2t, t]

**Step 6: Verify the solution**

Substitute the parametric expressions into the original equations.

First equation:

x + 2y - z = 3

(1 + 5t) + 2(1 - 2t) - t = 3

1 + 5t + 2 - 4t - t = 3

3 = 3

Second equation:

y + 2z = 1

(1 - 2t) + 2t = 1

1 = 1

Third equation:

0 = 0

This equation is always true.

Therefore, the parametric solution satisfies all three equations.

**Step 7: Determine the number of solutions**

There are three variables but only two pivot positions.

Therefore, one variable is free.

There is no contradictory equation, and the free variable can take any real value.

Consequently, the system has infinitely many solutions.

**Final Answer:**

x = 1 + 5t

y = 1 - 2t

z = t

where t is any real number.

The system has infinitely many solutions because z is a free variable.