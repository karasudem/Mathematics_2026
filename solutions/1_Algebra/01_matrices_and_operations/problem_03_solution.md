 ## Question

The matrix sizes are:

A: 2 x 3

B: 3 x 4

C: 4 x 2

D: 2 x 2

For the following products:

AB, BA, BC, CB, AC, CA, AD, DA

Determine whether each product is defined. If it is defined, state the size of the resulting matrix.

Justify each decision using the dimension compatibility condition.

 ## Solution

Exercise 3. When Can Matrices Be Multiplied?

Given Matrix Dimensions

* Matrix A: 2 × 3
* Matrix B: 3 × 4
* Matrix C: 4 × 2
* Matrix D: 2 × 2

Rule of Matrix Multiplication

Two matrices can be multiplied if the number of columns in the first matrix is equal to the number of rows in the second matrix.

If the dimensions are (m × n) and (n × p), the resulting matrix has dimensions (m × p).

1. Product AB

A has dimensions 2 × 3.

B has dimensions 3 × 4.

The inner dimensions are both 3, so multiplication is possible.

Result: 2 × 4.

Therefore, AB is defined.

2. Product BA

B has dimensions 3 × 4.

A has dimensions 2 × 3.

The inner dimensions are 4 and 2. They are not equal.

Therefore, BA is not defined.

3. Product BC

B has dimensions 3 × 4.

C has dimensions 4 × 2.

The inner dimensions are both 4, so multiplication is possible.

Result: 3 × 2.

Therefore, BC is defined.

4. Product CB

C has dimensions 4 × 2.

B has dimensions 3 × 4.

The inner dimensions are 2 and 3. They are not equal.

Therefore, CB is not defined.

5. Product AC

A has dimensions 2 × 3.

C has dimensions 4 × 2.

The inner dimensions are 3 and 4. They are not equal.

Therefore, AC is not defined.

6. Product CA

C has dimensions 4 × 2.

A has dimensions 2 × 3.

The inner dimensions are both 2, so multiplication is possible.

Result: 4 × 3.

Therefore, CA is defined.

7. Product AD

A has dimensions 2 × 3.

D has dimensions 2 × 2.

The inner dimensions are 3 and 2. They are not equal.

Therefore, AD is not defined.

8. Product DA

D has dimensions 2 × 2.

A has dimensions 2 × 3.

The inner dimensions are both 2, so multiplication is possible.

Result: 2 × 3.

Therefore, DA is defined.

Final Answers

Product	Defined?	Resulting Size
AB	Yes	2 × 4
BA	No	Not defined
BC	Yes	3 × 2
CB	No	Not defined
AC	No	Not defined
CA	Yes	4 × 3
AD	No	Not defined
DA	Yes	2 × 3

Conclusion

Matrix multiplication is possible only when the number of columns in the first matrix equals the number of rows in the second matrix.

The size of the resulting matrix is determined by the outer dimensions.

The order of multiplication matters because changing the order can make a product undefined or produce a matrix of a different size.