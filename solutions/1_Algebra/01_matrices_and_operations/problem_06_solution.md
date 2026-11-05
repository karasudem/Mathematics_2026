Exercise 6. Transpose

Given

Matrix A:

[ 1  2  3 ]
[ 4  5  6 ]

Matrix B:

[  1  0 ]
[  2  1 ]
[ -1  3 ]

We need to calculate A^T, B^T, and AB. Then we must verify that (AB)^T = B^T A^T.

1. Calculate the Transpose of Matrix A

The transpose of a matrix is obtained by changing its rows into columns and its columns into rows.

Original matrix A:

[ 1  2  3 ]
[ 4  5  6 ]

Therefore, its transpose is:

A^T = [ 1  4 ]
      [ 2  5 ]
      [ 3  6 ]

2. Calculate the Transpose of Matrix B

Original matrix B:

[  1  0 ]
[  2  1 ]
[ -1  3 ]

After changing rows into columns:

B^T = [ 1  2  -1 ]
      [ 0  1   3 ]

3. Calculate AB

To multiply A by B, we multiply each row of A by each column of B.

AB = [ 1  2  3 ] [  1  0 ]
     [ 4  5  6 ] [  2  1 ]
                   [ -1  3 ]

Calculating each entry:

* First row, first column: 1(1) + 2(2) + 3(-1) = 1 + 4 - 3 = 2
* First row, second column: 1(0) + 2(1) + 3(3) = 0 + 2 + 9 = 11
* Second row, first column: 4(1) + 5(2) + 6(-1) = 4 + 10 - 6 = 8
* Second row, second column: 4(0) + 5(1) + 6(3) = 0 + 5 + 18 = 23

Therefore:

AB = [ 2  11 ]
     [ 8  23 ]

4. Verify the Transpose Property

We need to verify:

(AB)^T = B^T A^T

First, calculate the transpose of AB.

AB = [ 2  11 ]
     [ 8  23 ]

Therefore:

(AB)^T = [  2   8 ]
         [ 11  23 ]

Now calculate B^T A^T.

B^T = [ 1  2  -1 ]
      [ 0  1   3 ]
A^T = [ 1  4 ]
      [ 2  5 ]
      [ 3  6 ]

Multiplying the matrices:

* First row, first column: 1(1) + 2(2) + (-1)(3) = 2
* First row, second column: 1(4) + 2(5) + (-1)(6) = 8
* Second row, first column: 0(1) + 1(2) + 3(3) = 11
* Second row, second column: 0(4) + 1(5) + 3(6) = 23

Therefore:

B^T A^T = [  2   8 ]
          [ 11  23 ]

5. Verification and Conclusion

We obtained:

(AB)^T = [  2   8 ]
         [ 11  23 ]
B^T A^T = [  2   8 ]
          [ 11  23 ]

Both matrices are equal.

Therefore:

(AB)^T = B^T A^T

This example verifies the transpose property: the transpose of a product of two matrices is equal to the product of their transposes in reverse order.

Final Answers

A^T = [ 1  4 ]
      [ 2  5 ]
      [ 3  6 ]
B^T = [ 1  2  -1 ]
      [ 0  1   3 ]
AB = [ 2  11 ]
     [ 8  23 ]
(AB)^T = B^T A^T

The transpose of a matrix changes its rows into columns, and the order of multiplication is reversed when taking the transpose of a matrix product.