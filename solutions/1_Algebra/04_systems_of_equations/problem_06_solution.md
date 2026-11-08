## Question

Consider the following system of linear equations:

x + y = 2

ax + ay = 4

Determine for which values of the parameter a the system has:

- Exactly one solution.
- Infinitely many solutions.
- No solution.

Explain why any of these cases may be impossible.

**Why this exercise:** Understand how a parameter can affect the consistency and number of solutions of a linear system.

## Solution

**Step 1: Write the augmented matrix**

The system is:

x + y = 2

ax + ay = 4

The augmented matrix is:

[1   1  |  2]
[a   a  |  4]

**Step 2: Apply Gaussian elimination**

Eliminate the x coefficient in the second row.

Apply:

R2 <- R2 - aR1

Calculate the new second row:

[a   a  |  4]
- a[1   1  |  2]
= [0   0  |  4 - 2a]

The resulting matrix is:

[1   1  |  2]
[0   0  |  4 - 2a]

**Step 3: Analyze the case a = 2**

If a = 2, the second row becomes:

[0   0  |  0]

The system is:

x + y = 2

0 = 0

The second equation gives no new restriction.

Therefore, one variable is free.

Choose:

y = t

Then:

x = 2 - t

The parametric solution is:

x = 2 - t

y = t

where t is any real number.

Therefore, the system has infinitely many solutions when:

a = 2

**Step 4: Analyze the case a != 2**

If a is not equal to 2, the second row becomes:

[0   0  |  4 - 2a]

Since a != 2:

4 - 2a != 0

This gives the equation:

0 = 4 - 2a

which is a contradiction.

Therefore, the system has no solution when:

a != 2

**Step 5: Determine whether exactly one solution is possible**

The two equations have proportional coefficients:

- The coefficient of x in the second equation is a times the first.
- The coefficient of y in the second equation is also a times the first.

Therefore, the coefficient matrix never has two independent rows.

The system cannot have exactly one solution.

There is no value of a that produces a unique solution.

**Step 6: Summarize all cases**

Case 1: a = 2

The second equation becomes identical to the first equation.

The system has infinitely many solutions.

Case 2: a != 2

The elimination produces a contradiction.

The system has no solution.

Case 3: Exactly one solution

This case is impossible because the two equations always have proportional coefficient rows.

**Final Answer:**

- Exactly one solution: No value of a.
- Infinitely many solutions: a = 2.
- No solution: a != 2.

The system can never have exactly one solution.