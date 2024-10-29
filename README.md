# The quadratic form of the Non-Pappus matroid
This repository contains a calculation (using SageMath) used in Example .. of our paper .. (joint with Dmitri Panov)

Here, the quadratic form of the Non-Pappus matroid is the function $q$ on $\mathbb{R}^9$ given by
```math
q(\mathbf{x}) = \mathbf{x}^t \cdot Q \cdot \mathbf{x}
```
where $Q$ is a certain $(9 \times 9)$-matrix.

We show that the maximum value of $q$ on the closed positive octant of the unit $8$-sphere is $-1$.

To prove this, we calculate the maximum among all eigenvalues of principal submatrices of $Q$ whose eigenspaces intersect the positive octant. 
