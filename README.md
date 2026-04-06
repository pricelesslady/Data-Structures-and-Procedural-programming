# Algorithm Collection: Set Theory & Vector Geometry

This collection provides two logical sets for data manipulation and linear algebra.

1. Distinct Element Summation (Symmetric Difference)
- Logic: Performs a bidirectional "relative complement" check, finding elements in Set A not in B, and Set B not in A, then summing them.
- Goal: Sum of symmetric difference between two sets.
- Example: A=[3,1,7,9], B=[2,4,1,9,3] -> Unique are {7, 2, 4} -> Sum: 13.
- Use Case: Identifying discrepancies between two databases.

2. Orthogonal Vector Check (Dot Product)
- Logic: Multiplies corresponding components of two vectors (e.g., [x1, y1]·[x2, y2] = x1*x2 + y1*y2) and sums them.
- Goal: Determine if vectors are perpendicular.
- Rule: If Dot Product == 0, vectors are orthogonal.
- Process: Accepts pairs of vectors, calculates dot product, verifies if zero.
- Use Case: Collision detection and 3D rendering.

*Note: The orthogonal check requires that the sum of the products of components is zero [1, 3].
