# The Non-Pappus matroid

The notebook `nonpappus.ipynb` contains a calculation (using SageMath) that complements Example 7.41 of my paper: 

*A Miyaoka-Yau inequality for hyperplane arrangements in complex projective space* **(joint with Dima Panov)**.

The Hirzebruch quadratic form of the Non-Pappus matroid is a function $q$ on $\mathbb{R}^9$ given by
```math
q(\mathbf{x}) = \mathbf{x}^t \cdot Q \cdot \mathbf{x}
```
where $Q$ is a certain $(9 \times 9)$-matrix written in cell [2] of the notebook.

**Main result:** the maximum value of $q$ on the closed positive octant of the unit $8$-sphere is $-1$. 

The above result is proved in cell [27].
To do this, we calculate the maximum among all eigenvalues of principal submatrices of $Q$ whose eigenspaces intersect the positive octant.

We also show that there are $3$ maximum points. See Theorem 2 after cell [34].
