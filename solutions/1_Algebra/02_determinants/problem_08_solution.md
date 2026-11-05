Exercise 8 – Solution

Given:

det(A) = 3

det(B) = -5

We need to calculate det(AB), det(BA), and det(A^(-1)B).

Step 1: Calculate det(AB)

The determinant of a product is equal to the product of the determinants.

det(AB) = det(A) * det(B)

det(AB) = 3 * (-5)

det(AB) = -15

Step 2: Calculate det(BA)

Using the same property:

det(BA) = det(B) * det(A)

det(BA) = (-5) * 3

det(BA) = -15

Therefore:

det(AB) = det(BA)

Step 3: Calculate det(A^(-1)B)

The determinant of an inverse matrix is the reciprocal of the original determinant.

det(A^(-1)) = 1 / det(A)

det(A^(-1)) = 1 / 3

Now:

det(A^(-1)B) = det(A^(-1)) * det(B)

det(A^(-1)B) = (1 / 3) * (-5)

det(A^(-1)B) = -5 / 3

This determinant exists because A is invertible (det(A) is not zero).

Step 4: Explain Why the First Two Results Are Equal

Matrix multiplication is not generally commutative, which means:

AB is usually not equal to BA.

However, the determinant of a product follows this rule:

det(AB) = det(A) * det(B)

det(BA) = det(B) * det(A)

Since multiplication of real numbers is commutative, both determinants are equal.

Final Answer

det(AB) = -15

det(BA) = -15

det(A^(-1)B) = -5 / 3

The first two determinants are equal even though AB and BA are generally different matrices.