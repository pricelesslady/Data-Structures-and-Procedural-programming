README: Vector & Set OperationsThis repository contains 
pseudocode and Python implementations for two core mathematical operations: 
Vector Orthogonality and Distinct Element Summation.
1. Vector Orthogonality (Pseudocode)Determines if two vectors are orthogonal (perpendicular) by calculating their dot product.
Logic: If (v1[0]*v2[0] + ... + v1[n]*v2[n]) = 0, the vectors are orthogonal.
Features: Includes both a Procedure (using VAR reference) and a Function for flexible implementation 
Distinct Element Summation (Python)Calculates the sum of all elements that appear in exactly one of two provided sets.
Logic:Iterates set1: adds elements not found in set2.Iterates set2: adds elements not found in set1.
Example: [3, 1, 7, 9] + [2, 4, 1, 9, 3] → Result: 13 (7 + 2 + 4).🛠 UsageOrthogonality:
Use Orthogonal_Check_Nested for batch processing of vector pairs.
Set Sum: Call sum_of_distinct_elements(s1, s2) to retrieve the unique total
