## Question

Given the following matrices:

A = [  1   2 ]
[ -1   3 ]

B = [ 4  -2 ]
[ 0   5 ]

Compute:

1. A + B
2. A - B
3. 3A - 2B

Explain why matrix addition is possible only for matrices of the same size.


## Solution

Exercise 2. Addition and Scalar Multiplication

Given:

A =
[  1   2  ]
[ -1   3  ]

B =
[  4  -2  ]
[  0   5  ]

1. Matrix Addition (A + B)

Matrix addition is performed by adding corresponding entries.

A + B =

[ 1 + 4      2 + (-2) ]
[ -1 + 0     3 + 5    ]

Therefore,

A + B =

[ 5    0 ]
[ -1   8 ]

2. Matrix Subtraction (A - B)

Matrix subtraction is performed by subtracting corresponding entries.

A - B =

[ 1 - 4      2 - (-2) ]
[ -1 - 0     3 - 5    ]

Therefore,

A - B =

[ -3    4  ]
[ -1   -2  ]

3. Scalar Multiplication (3A - 2B)

First, multiply every entry of A by 3:

3A =

[ 3    6 ]
[ -3   9 ]

Next, multiply every entry of B by 2:

2B =

[ 8    -4 ]
[ 0    10 ]

Now subtract the matrices:

3A - 2B =

[ 3 - 8      6 - (-4) ]
[ -3 - 0     9 - 10   ]

Therefore,

3A - 2B =

[ -5    10 ]
[ -3    -1 ]

4. Why Must Matrices Have the Same Size for Addition?

Matrix addition is possible only when both matrices have the same number of rows and columns.

This is because each entry in the first matrix must be added to the corresponding entry in the second matrix.

If the dimensions are different, the corresponding entries cannot be matched correctly.

In this exercise, both A and B have the size 2 × 2, so addition and subtraction are defined.

Verification

The calculations can be checked entry by entry:

A + B:

* 1 + 4 = 5
* 2 + (-2) = 0
* -1 + 0 = -1
* 3 + 5 = 8

A - B:

* 1 - 4 = -3
* 2 - (-2) = 4
* -1 - 0 = -1
* 3 - 5 = -2

3A - 2B:

* 3(1) - 2(4) = -5
* 3(2) - 2(-2) = 10
* 3(-1) - 2(0) = -3
* 3(3) - 2(5) = -1

All results are consistent with the calculated matrices.

Final Answers

A + B =

[ 5    0 ]
[ -1   8 ]

A - B =

[ -3    4  ]
[ -1   -2  ]

3A - 2B =

[ -5    10 ]
[ -3    -1 ]