Exercise 11. When Do Matrices Commute?

Given Matrices

A = [ 1  1 ]
[ 0  1 ]

B = [ a  b ]
[ c  d ]

We need to find the conditions under which AB = BA.

1. Calculate AB

We multiply matrix A by matrix B.

AB = [ 1  1 ] [ a  b ]
[ 0  1 ] [ c  d ]

Calculating each entry:

* First row, first column: 1(a) + 1(c) = a + c
* First row, second column: 1(b) + 1(d) = b + d
* Second row, first column: 0(a) + 1(c) = c
* Second row, second column: 0(b) + 1(d) = d

Therefore:

AB = [ a+c  b+d ]
[ c     d   ]

2. Calculate BA

Now we reverse the order of multiplication.

BA = [ a  b ] [ 1  1 ]
[ c  d ] [ 0  1 ]

Calculating each entry:

* First row, first column: a(1) + b(0) = a
* First row, second column: a(1) + b(1) = a+b
* Second row, first column: c(1) + d(0) = c
* Second row, second column: c(1) + d(1) = c+d

Therefore:

BA = [ a  a+b ]
[ c  c+d ]

3. Find the Conditions for AB = BA

For two matrices to be equal, their corresponding entries must be equal.

Comparing the first entries:

a + c = a

Therefore:

c = 0

Comparing the second entries:

b + d = a + b

Therefore:

d = a

Comparing the third entries:

c = c

This condition is always true.

Comparing the fourth entries:

d = c + d

Therefore:

c = 0

The conditions are:

c = 0
d = a

There is no restriction on a or b.

4. General Form of Matrix B

Using the conditions c = 0 and d = a, matrix B becomes:

B = [ a  b ]
[ 0  a ]

Therefore, all matrices of this form commute with A.

5. Verification

Substituting c = 0 and d = a into AB:

AB = [ a  b+a ]
[ 0  a   ]

Substituting the same conditions into BA:

BA = [ a  a+b ]
[ 0  a   ]

Since a+b = b+a, both products are equal.

Therefore:

AB = BA

Final Answer

The matrices commute when:

c = 0 and d = a.

The general form of B is:

B = [ a  b ]
[ 0  a ]

where a and b can be any real numbers.

This shows that matrix multiplication is not always commutative, but certain matrices do commute.