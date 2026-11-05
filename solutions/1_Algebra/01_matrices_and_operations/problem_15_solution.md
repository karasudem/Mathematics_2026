Exercise 15 – Solution

Given:

A = [ 1  2  0 ]
[ 0  1  1 ]

B = [  1  0 ]
[  2  1 ]
[ -1  3 ]

C = [ 2   1 ]
[ 0  -1 ]

We need to calculate (AB)C and A(BC), compare the results, and explain the associativity of matrix multiplication.

Step 1: Calculate AB

AB =

[ 1  2  0 ]   [  1  0 ]
[ 0  1  1 ] * [  2  1 ]
[ -1  3 ]

AB =

[ 1+4+0    0+2+0 ]
[ 0+2-1    0+1+3 ]

AB = [ 5  2 ]
[ 1  4 ]

Step 2: Calculate (AB)C

(AB)C =

[ 5  2 ]   [ 2   1 ]
[ 1  4 ] * [ 0  -1 ]

(AB)C =

[ 10  5-2 ]
[  2  1-4 ]

(AB)C = [ 10   3 ]
[  2  -3 ]

Step 3: Calculate BC

BC =

[  1  0 ]   [ 2   1 ]
[  2  1 ] * [ 0  -1 ]
[ -1  3 ]

BC =

[  2   1 ]
[  4   1 ]
[ -2  -4 ]

Step 4: Calculate A(BC)

A(BC) =

[ 1  2  0 ]   [  2   1 ]
[ 0  1  1 ] * [  4   1 ]
[ -2  -4 ]

A(BC) =

[ 2+8+0    1+2+0 ]
[ 4-2     1-4   ]

A(BC) = [ 10   3 ]
[  2  -3 ]

Step 5: Compare the Results

We obtained:

(AB)C = [ 10   3 ]
[  2  -3 ]

A(BC) = [ 10   3 ]
[  2  -3 ]

Therefore:

(AB)C = A(BC)

Both calculation paths give exactly the same result.

Step 6: Compare the Calculation Paths

Both methods require two matrix multiplications.

However, the number of scalar multiplications is different:

* First method (AB)C: 20 scalar multiplications.
* Second method A(BC): 24 scalar multiplications.

Therefore, calculating (AB)C is more efficient in this example.

Final Answer

(AB)C = A(BC) =

[ 10   3 ]
[  2  -3 ]

Matrix multiplication is associative because changing the grouping of the matrices does not change the final result.

However, different calculation paths may require different amounts of work.