Exercise 14 – Solution

Given the rotation matrix:

R(theta) = [ cos(theta)  -sin(theta) ]
[ sin(theta)   cos(theta) ]

We need to compute R(alpha) * R(beta) and show that:

R(alpha) * R(beta) = R(alpha + beta)

Step 1: Write the Matrices

R(alpha) = [ cos(alpha)  -sin(alpha) ]
[ sin(alpha)   cos(alpha) ]

R(beta) = [ cos(beta)  -sin(beta) ]
[ sin(beta)   cos(beta) ]

Step 2: Multiply the Matrices

R(alpha) * R(beta) =

[ cos(alpha)  -sin(alpha) ]   [ cos(beta)  -sin(beta) ]
[ sin(alpha)   cos(alpha) ] * [ sin(beta)   cos(beta) ]

Multiplying the matrices:

= [ cos(alpha)cos(beta) - sin(alpha)sin(beta)
-(cos(alpha)sin(beta) + sin(alpha)cos(beta)) ]

[ sin(alpha)cos(beta) + cos(alpha)sin(beta)
cos(alpha)cos(beta) - sin(alpha)sin(beta) ]

Step 3: Use the Angle-Sum Formulas

Recall the trigonometric identities:

cos(alpha + beta) = cos(alpha)cos(beta) - sin(alpha)sin(beta)

sin(alpha + beta) = sin(alpha)cos(beta) + cos(alpha)sin(beta)

Using these formulas, we get:

R(alpha) * R(beta) =

[ cos(alpha + beta)  -sin(alpha + beta) ]
[ sin(alpha + beta)   cos(alpha + beta) ]

This is exactly the definition of R(alpha + beta).

Therefore:

R(alpha) * R(beta) = R(alpha + beta)

Step 4: Geometrical Explanation

A rotation matrix rotates a vector around the origin by a given angle.

First, R(beta) rotates the vector by angle beta.

Then, R(alpha) rotates the result by angle alpha.

The total rotation is alpha + beta.

Therefore, performing two rotations one after another is equivalent to performing one rotation by the sum of their angles.

Final Answer

R(alpha) * R(beta) = R(alpha + beta)

Two consecutive rotations around the same origin are equivalent to one rotation by the sum of the two angles.