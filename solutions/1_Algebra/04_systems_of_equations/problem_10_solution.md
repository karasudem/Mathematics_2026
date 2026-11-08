## Question

Find a quadratic polynomial passing through the following three points:

(0, 1), (1, 3), (2, 9)

Assume that the polynomial has the form:

p(x) = ax^2 + bx + c

Convert the conditions into a system of linear equations and solve for a, b, and c.

Verify that the resulting polynomial passes through all three given points.

**Why this exercise:** Understand how polynomial interpolation can be reduced to solving a system of linear equations.

## Solution

**Step 1: Write the general form of the polynomial**

We are given a quadratic polynomial:

p(x) = ax^2 + bx + c

We need to find the values of a, b, and c.

The polynomial must pass through the points:

(0, 1), (1, 3), (2, 9)

**Step 2: Substitute the first point**

The first point is:

(0, 1)

This means:

p(0) = 1

Substitute x = 0:

a(0)^2 + b(0) + c = 1

Therefore:

c = 1

**Step 3: Substitute the second point**

The second point is:

(1, 3)

This means:

p(1) = 3

Substitute x = 1:

a(1)^2 + b(1) + c = 3

Therefore:

a + b + c = 3

**Step 4: Substitute the third point**

The third point is:

(2, 9)

This means:

p(2) = 9

Substitute x = 2:

a(2)^2 + b(2) + c = 9

Therefore:

4a + 2b + c = 9

**Step 5: Write the system of linear equations**

The three equations are:

c = 1

a + b + c = 3

4a + 2b + c = 9

Rearranging the variables in the order a, b, c:

0a + 0b + c = 1

a + b + c = 3

4a + 2b + c = 9

The augmented matrix is:

[0   0   1  |  1]
[1   1   1  |  3]
[4   2   1  |  9]

**Step 6: Apply Gaussian elimination**

Swap Row 1 and Row 2:

R1 <-> R2

The matrix becomes:

[1   1   1  |  3]
[0   0   1  |  1]
[4   2   1  |  9]

Eliminate the a coefficient in Row 3:

R3 <- R3 - 4R1

The matrix becomes:

[1   1   1  |  3]
[0   0   1  |  1]
[0  -2  -3  | -3]

Swap Row 2 and Row 3:

R2 <-> R3

The matrix becomes:

[1   1   1  |  3]
[0  -2  -3  | -3]
[0   0   1  |  1]

**Step 7: Solve using back substitution**

From the third row:

c = 1

From the second row:

-2b - 3c = -3

Substitute c = 1:

-2b - 3 = -3

-2b = 0

b = 0

From the first row:

a + b + c = 3

Substitute b = 0 and c = 1:

a + 0 + 1 = 3

a = 2

Therefore:

a = 2

b = 0

c = 1

**Step 8: Write the resulting polynomial**

The general form is:

p(x) = ax^2 + bx + c

Substitute the values:

p(x) = 2x^2 + 0x + 1

Therefore:

p(x) = 2x^2 + 1

**Step 9: Verify the polynomial using all three points**

First point: (0, 1)

p(0) = 2(0)^2 + 1

p(0) = 1

The first point is satisfied.

Second point: (1, 3)

p(1) = 2(1)^2 + 1

p(1) = 2 + 1

p(1) = 3

The second point is satisfied.

Third point: (2, 9)

p(2) = 2(2)^2 + 1

p(2) = 8 + 1

p(2) = 9

The third point is satisfied.

**Final Answer:**

a = 2

b = 0

c = 1

The required quadratic polynomial is:

p(x) = 2x^2 + 1

It passes through all three given points:

(0, 1), (1, 3), and (2, 9).