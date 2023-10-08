---
aliases: 
tags:
  - batch/school/class/ma110
  - batch/math
type: Problem
---
# Problem 1.7 MA-110
> [!problem] Problem 1.7
> Prove that the following is, or is not a group, as appropriate: The set $M_{2}(\mathbb{R})$ of all 2 by 2 matrices, with real numbers as entries, and operation matrix multiplication.

Let $M_{2}(\mathbb{R})$ be the set of all two by two matrices with real number entries along with the operation, $\cdot$ of matrix multiplication. Let $a,b,c,d \in \mathbb{R}$. Suppose
$$
\begin{bmatrix}
1 & 1 \\
1 & 1
\end{bmatrix}^{-1}
$$
exists
$$
I =
\begin{bmatrix}
1 & 0 \\
0 & 1
\end{bmatrix}=
\begin{align}
\begin{bmatrix}
1 & 1 \\
1 & 1
\end{bmatrix}
\cdot 
\begin{bmatrix}
a & b \\
c & d
\end{bmatrix} 
=
\begin{bmatrix}
a + c & b + d \\
a + c & b+d
\end{bmatrix}
\end{align}.
$$
This is clearly a contradiction; the columns of the identity matrix cannot have the same value. Therefore, the given matrix has no inverse, and $M_{2}(\mathbb{R})$ is not a group.
