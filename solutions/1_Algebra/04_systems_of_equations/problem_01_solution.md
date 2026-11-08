## Question

Write the following system of linear equations in the form Ax = b:

2x - y + z = 4
x + 3y - 2z = 1
3x + y + z = 7

Identify:
- The coefficient matrix A.
- The vector of unknowns x.
- The right-hand side vector b.

Explain how each row of the matrix corresponds to one equation.

## Solution

**Step 1: Identify the coefficients**

We are given the system:

2x - y + z = 4
x + 3y - 2z = 1
3x + y + z = 7

The coefficients of x, y, and z in each equation are:

- First equation: 2, -1, 1
- Second equation: 1, 3, -2
- Third equation: 3, 1, 1

**Step 2: Construct the coefficient matrix A**

We place the coefficients into rows:

A = [ 2  -1   1 ]
    [ 1   3  -2 ]
    [ 3   1   1 ]

**Step 3: Construct the vector of unknowns x**

The unknown variables are x, y, and z.

Therefore:

x = [ x ]
    [ y ]
    [ z ]

**Step 4: Construct the right-hand side vector b**

The constants on the right-hand side of the equations are 4, 1, and 7.

Therefore:

b = [ 4 ]
    [ 1 ]
    [ 7 ]

**Step 5: Write the system in matrix form**

Combining the three parts gives:

Ax = b

[ 2  -1   1 ] [ x ]   [ 4 ]
[ 1   3  -2 ] [ y ] = [ 1 ]
[ 3   1   1 ] [ z ]   [ 7 ]

**Step 6: Explain the relationship between rows and equations**

Each row of the coefficient matrix A represents one equation.

- The first row [2, -1, 1] contains the coefficients of the first equation: 2x - y + z = 4.
- The second row [1, 3, -2] contains the coefficients of the second equation: x + 3y - 2z = 1.
- The third row [3, 1, 1] contains the coefficients of the third equation: 3x + y + z = 7.

The corresponding entry in vector b is the right-hand side constant of that equation.

**Final Answer**

The system in matrix form is Ax = b, where:

A = [ 2  -1   1 ]
    [ 1   3  -2 ]
    [ 3   1   1 ]

x = [ x ]
    [ y ]
    [ z ]

b = [ 4 ]
    [ 1 ]
    [ 7 ]