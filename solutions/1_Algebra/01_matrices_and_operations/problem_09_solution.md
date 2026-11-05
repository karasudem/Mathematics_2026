Exercise 9. Composing Transformations

Given Matrices and Vector

We are given:

Matrix S:

[ 2  0 ]
[ 0  1 ]

Matrix R:

[ 0  -1 ]
[ 1   0 ]

Vector x:

[ 1 ]
[ 2 ]

Matrix S describes nonuniform scaling, while matrix R describes a 90-degree counterclockwise rotation.

We need to calculate RSx and SRx and compare the results.

1. Calculate RSx

First, we calculate Sx:

Sx = [ 2  0 ] [ 1 ] = [ 2 ]
     [ 0  1 ] [ 2 ]   [ 2 ]

Now we multiply the result by R:

RSx = [ 0  -1 ] [ 2 ] = [ -2 ]
      [ 1   0 ] [ 2 ]   [  2 ]

Therefore:

RSx = [ -2 ]
      [  2 ]

2. Calculate SRx

First, we calculate Rx:

Rx = [ 0  -1 ] [ 1 ] = [ -2 ]
     [ 1   0 ] [ 2 ]   [  1 ]

Now we multiply the result by S:

SRx = [ 2  0 ] [ -2 ] = [ -4 ]
      [ 0  1 ] [  1 ]   [  1 ]

Therefore:

SRx = [ -4 ]
      [  1 ]

3. Compare the Results

We obtained:

RSx = [ -2 ]
      [  2 ]
SRx = [ -4 ]
      [  1 ]

Clearly:

RSx is not equal to SRx.

The two results are different because the order of the transformations changes the final vector.

4. Geometrical Explanation

When we calculate RSx, we first apply scaling and then rotate the vector.

When we calculate SRx, we first rotate the vector and then apply scaling.

Scaling changes the horizontal coordinate but does not change the vertical coordinate.

Therefore, applying scaling before or after rotation produces different results.

This demonstrates that the order of matrix transformations matters.

Final Answer

RSx = [ -2 ]
      [  2 ]
SRx = [ -4 ]
      [  1 ]

RSx is not equal to SRx.

Matrix transformations are generally not commutative because changing their order can produce a different result.