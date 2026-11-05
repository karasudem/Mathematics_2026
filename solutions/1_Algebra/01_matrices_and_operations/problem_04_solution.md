Exercise 4. Matrix Multiplication and Noncommutativity

Given Matrices

Matrix A:

[ 1  2 ]
[ 0  1 ]

Matrix B:

[ 2  0 ]
[ 3  1 ]

We need to calculate AB and BA and determine whether they are equal.

1. Calculate AB

To calculate AB, we multiply each row of A by each column of B.

AB = [ 1  2 ] [ 2  0 ]
     [ 0  1 ] [ 3  1 ]

Calculating each entry:

* First row, first column: 1(2) + 2(3) = 2 + 6 = 8
* First row, second column: 1(0) + 2(1) = 0 + 2 = 2
* Second row, first column: 0(2) + 1(3) = 3
* Second row, second column: 0(0) + 1(1) = 1

Therefore:

AB = [ 8  2 ]
     [ 3  1 ]

2. Calculate BA

Now we reverse the order of multiplication.

BA = [ 2  0 ] [ 1  2 ]
     [ 3  1 ] [ 0  1 ]

Calculating each entry:

* First row, first column: 2(1) + 0(0) = 2
* First row, second column: 2(2) + 0(1) = 4
* Second row, first column: 3(1) + 1(0) = 3
* Second row, second column: 3(2) + 1(1) = 7

Therefore:

BA = [ 2  4 ]
     [ 3  7 ]

3. Compare AB and BA

We obtained:

AB = [ 8  2 ]
     [ 3  1 ]
BA = [ 2  4 ]
     [ 3  7 ]

Clearly:

AB ≠ BA

The two products have different entries.

4. Explanation of Noncommutativity

Matrix multiplication is generally not commutative.

This means that changing the order of multiplication can change the result.

For ordinary numbers, multiplication is commutative because 2 × 3 = 3 × 2.

However, for matrices, AB is not necessarily equal to BA.

This example demonstrates that the order of matrix multiplication matters.

Final Answer

AB = [ 8  2 ]
     [ 3  1 ]
BA = [ 2  4 ]
     [ 3  7 ]
AB ≠ BA

Therefore, matrix multiplication is not commutative in general.