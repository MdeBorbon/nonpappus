# The quadratic form of the Non-Pappus matroid
This repository contains a calculation (using SageMath) used in Example .. of our paper .. (joint with Dmitri Panov)
We show that the maximum of the quadratic form in $\mathbb{R}^9$ defined by the matrix
$$Q = \left(\begin{array}{rrrrrrrrr}
-5 & 1 & 1 & -2 & 1 & 1 & 1 & 1 & -2 \\
1 & -5 & 1 & 1 & -2 & 1 & 1 & -2 & 1 \\
1 & 1 & -5 & 1 & 1 & -2 & -2 & 1 & 1 \\
-2 & 1 & 1 & -5 & 1 & 1 & 1 & 1 & -2 \\
1 & -2 & 1 & 1 & -5 & 1 & 1 & -2 & 1 \\
1 & 1 & -2 & 1 & 1 & -5 & -2 & 1 & 1 \\
1 & 1 & -2 & 1 & 1 & -2 & -2 & -2 & -2 \\
1 & -2 & 1 & 1 & -2 & 1 & -2 & -2 & -2 \\
-2 & 1 & 1 & -2 & 1 & 1 & -2 & -2 & -2
\end{array}\right)$$
on the closed positive octant of the unit sphere $\Delta = \{x_i \geq 0\} \cap S^8$ is $-1$.

To show this, we calculate the maximum among all eigenvalues of principal submatrices whose eigenspaces intersect the positive octant. 
