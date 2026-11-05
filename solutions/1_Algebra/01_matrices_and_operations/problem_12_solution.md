Exercise 12 – Solution

Given:

A = [ 1  1 ]
[ 0  1 ]

We need to calculate A^2, A^3, A^4, find a general formula for A^n, and prove it by mathematical induction.

Step 1: Calculate A^2

A^2 = A * A

A^2 = [ 1  1 ] * [ 1  1 ]
[ 0  1 ]   [ 0  1 ]

A^2 = [ 1  2 ]
[ 0  1 ]

Step 2: Calculate A^3

A^3 = A^2 * A

A^3 = [ 1  2 ] * [ 1  1 ]
[ 0  1 ]   [ 0  1 ]

A^3 = [ 1  3 ]
[ 0  1 ]

Step 3: Calculate A^4

A^4 = A^3 * A

A^4 = [ 1  3 ] * [ 1  1 ]
[ 0  1 ]   [ 0  1 ]

A^4 = [ 1  4 ]
[ 0  1 ]

Step 4: Find the General Formula

From the calculations, we can observe the pattern:

A^2 = [ 1  2 ]
[ 0  1 ]

A^3 = [ 1  3 ]
[ 0  1 ]

A^4 = [ 1  4 ]
[ 0  1 ]

Therefore, we can conjecture that:

A^n = [ 1  n ]
[ 0  1 ]

Step 5: Proof by Mathematical Induction

Base Case (n = 1):

A^1 = [ 1  1 ]
[ 0  1 ]

The formula is true for n = 1.

Inductive Hypothesis:

Assume that the formula is true for some positive integer n:

A^n = [ 1  n ]
[ 0  1 ]

Inductive Step:

We need to prove that the formula is also true for n + 1.

A^(n+1) = A^n * A

A^(n+1) = [ 1  n ] * [ 1  1 ]
[ 0  1 ]   [ 0  1 ]

A^(n+1) = [ 1  n+1 ]
[ 0   1  ]

This is exactly the formula for n + 1.

Therefore, by mathematical induction, the formula is true for all positive integers n.

Final Answer

A^n = [ 1  n ]
[ 0  1 ]

for every positive integer n.