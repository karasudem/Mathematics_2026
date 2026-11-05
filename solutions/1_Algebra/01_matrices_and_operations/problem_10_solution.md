Exercise 10. Columns of a Matrix Product

Given Matrices

Matrix A:

[ 1  2  0 ]
[ 0  1  1 ]

Matrix B:

[  1  2 ]
[ -1  0 ]
[  3  1 ]

The columns of matrix B are called b1 and b2.

We need to calculate Ab1 and Ab2, calculate AB, and compare the results.

1. Calculate Ab1 and Ab2

The first column of B is:

b1 = [  1 ]
     [ -1 ]
     [  3 ]

We multiply matrix A by the first column:

Ab1 = [ 1  2  0 ] [  1 ]
      [ 0  1  1 ] [ -1 ]
                    [  3 ]

Calculating each entry:

First entry:

1(1) + 2(-1) + 0(3) = 1 - 2 + 0 = -1

Second entry:

0(1) + 1(-1) + 1(3) = 0 - 1 + 3 = 2

Therefore:

Ab1 = [ -1 ]
      [  2 ]

The second column of B is:

b2 = [ 2 ]
     [ 0 ]
     [ 1 ]

We multiply matrix A by the second column:

Ab2 = [ 1  2  0 ] [ 2 ]
      [ 0  1  1 ] [ 0 ]
                    [ 1 ]

Calculating each entry:

First entry:

1(2) + 2(0) + 0(1) = 2

Second entry:

0(2) + 1(0) + 1(1) = 1

Therefore:

Ab2 = [ 2 ]
      [ 1 ]

2. Calculate the Matrix Product AB

To calculate AB, we multiply each row of A by each column of B.

AB = [ 1  2  0 ] [  1  2 ]
     [ 0  1  1 ] [ -1  0 ]
                 [  3  1 ]

Calculating each entry:

First row, first column:

1(1) + 2(-1) + 0(3) = -1

First row, second column:

1(2) + 2(0) + 0(1) = 2

Second row, first column:

0(1) + 1(-1) + 1(3) = 2

Second row, second column:

0(2) + 1(0) + 1(1) = 1

Therefore:

AB = [ -1  2 ]
     [  2  1 ]

3. Compare the Results

We obtained:

Ab1 = [ -1 ]       Ab2 = [ 2 ]
      [  2 ]             [ 1 ]

The matrix product is:

AB = [ -1  2 ]
     [  2  1 ]

The first column of AB is exactly Ab1.

The second column of AB is exactly Ab2.

Therefore, the columns of AB are the vectors Ab1 and Ab2.

4. Explanation

When multiplying two matrices, each column of the second matrix is multiplied separately by the first matrix.

The resulting vectors become the columns of the product matrix.

This explains why the columns of AB are exactly Ab1 and Ab2.

Final Answer

Ab1 = [ -1 ]
      [  2 ]
Ab2 = [ 2 ]
      [ 1 ]
AB =  [ -1  2 ]
      [  2  1 ]

The columns of AB are exactly the results of multiplying A by the individual columns of B.