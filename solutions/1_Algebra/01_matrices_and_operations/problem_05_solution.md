Exercise 5. Matrix Times Vector

Given

Matrix A:

[ 2  -1 ]
[ 1   3 ]

Vector x:

[ 4 ]
[ 2 ]

We need to calculate Ax and express the result as a linear combination of the columns of A.

1. Calculate the Matrix-Vector Product

To multiply a matrix by a vector, multiply each row of the matrix by the corresponding entries of the vector and add the results.

Ax =

[ 2  -1 ]   [ 4 ]
[ 1   3 ] x [ 2 ]

Calculating each entry:

* First entry: 2(4) + (-1)(2) = 8 - 2 = 6
* Second entry: 1(4) + 3(2) = 4 + 6 = 10

Therefore:

Ax = [  6 ]
     [ 10 ]

2. Express the Result as a Linear Combination of Columns

The columns of matrix A are:

First column (a1):

[ 2 ]
[ 1 ]

Second column (a2):

[ -1 ]
[  3 ]

The vector x contains the coefficients 4 and 2.

Therefore:

Ax = 4a1 + 2a2

Substituting the columns:

Ax = 4[  2 ] + 2[ -1 ]
       [  1 ]    [  3 ]
Ax = [ 8 ] + [ -2 ]
     [ 4 ]   [  6 ]
Ax = [  6 ]
     [ 10 ]

3. Verification

Both methods give the same result:

Ax = [  6 ]
     [ 10 ]

This confirms that the matrix-vector multiplication and the linear combination of the columns are consistent.

Final Answer

Ax = [  6 ] = 4a1 + 2a2
     [ 10 ]

A matrix-vector product is a linear combination of the columns of the matrix, where the entries of the vector are the coefficients.