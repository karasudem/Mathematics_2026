## Question

Consider the following system of linear equations:

x + y = 10

2x + 5y = 32

Solve the system using Gaussian elimination.

Explain geometrically why the system has a unique solution.

**Why this exercise:** Understand the relationship between solving linear systems and the intersection of lines in a two-dimensional plane.

## Solution

**Step 1: Write the augmented matrix**

The system is:

x + y = 10

2x + 5y = 32

The augmented matrix is:

[1   1  |  10]
[2   5  |  32]

**Step 2: Apply Gaussian elimination**

Eliminate the x coefficient in Row 2.

Apply:

R2 <- R2 - 2R1

Calculate the new second row:

[2   5  |  32]
- 2[1   1  |  10]
= [0   3  |  12]

The resulting matrix is:

[1   1  |  10]
[0   3  |  12]

**Step 3: Solve using back substitution**

The second row represents:

3y = 12

Therefore:

y = 12 / 3

y = 4

Now use the first row:

x + y = 10

Substitute y = 4:

x + 4 = 10

x = 6

Therefore:

x = 6

y = 4

**Step 4: Verify the solution**

Substitute x = 6 and y = 4 into both original equations.

First equation:

x + y = 10

6 + 4 = 10

10 = 10

Second equation:

2x + 5y = 32

2(6) + 5(4) = 32

12 + 20 = 32

32 = 32

Both equations are satisfied.

**Step 5: Explain the geometric interpretation**

Each linear equation in two variables represents a straight line in the xy-plane.

The first equation is:

x + y = 10

Rearranging:

y = 10 - x

The second equation is:

2x + 5y = 32

Rearranging:

y = 32/5 - (2/5)x

The slopes of the two lines are:

First line: -1

Second line: -2/5

Since the slopes are different, the lines are not parallel.

Therefore, they intersect at exactly one point.

The intersection point is:

(6, 4)

This point represents the unique solution of the system.

**Step 6: Explain why the solution is unique**

After Gaussian elimination, the matrix is:

[1   1  |  10]
[0   3  |  12]

There is a pivot in both variable columns.

Therefore, neither variable is free.

There is also no contradictory row.

Consequently, the system has exactly one solution.

**Final Answer:**

x = 6

y = 4

The system has exactly one solution because the two lines have different slopes and intersect at exactly one point:

(6, 4)