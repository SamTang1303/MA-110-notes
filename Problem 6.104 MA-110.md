---
aliases: 
tags:
  - batch/school/class/ma110
  - batch/math
type: Problem
---
# Problem 6.104 MA-110

> [!problem] Problem 6.104
> Let $I$ be the subset of $M_{2}(\mathbb{R})$ consisting of matrices whose second column is zero. That is,
> 
> $$
> I=
> \left\{ 
> \begin{bmatrix}
> a & 0 \\
> b & 0
> \end{bmatrix}
> \mid a,b \in  \mathbb{R}
> \right\}
> $$
> Prove that $I$ is a left ideal but isn't a right ideal.

We know that the elements of $M_{2}(\mathbb{R})$ are a ring under matrix addition and multiplication. So, since $I\subseteq M_{2}(\mathbb{R})$, to show $I$ is a subring of $M_{2}(\mathbb{R})$ we must only show $I$ contains the identity of $M_{2}(\mathbb{R})$, is closed under additive inverses, is closed under addition, and is closed under multiplication.

Let $A,B \in I$ such that $A=\begin{bmatrix}a_{1} & 0\\a_{2} & 0\end{bmatrix}$ and $B=\begin{bmatrix}b_{1} & 0\\b_{2} & 0\end{bmatrix}$.
$$
\begin{align}
0_{M_{2}(\mathbb{R})} &=
\begin{bmatrix}
0 & 0 \\
0 & 0
\end{bmatrix}
\in I,\\
-A &=
\begin{bmatrix}
-a_{1} & 0 \\
-a_{2} & 0
\end{bmatrix}
\in  I, \\
AB &=
\begin{bmatrix}
a_{1} &  0\\
a_{2} & 0
\end{bmatrix}
\cdot 
\begin{bmatrix}
b_{1}  & 0 \\
b_{2} & 0
\end{bmatrix} 
=
\begin{bmatrix}
a_{1}b_{1}  & 0\\
a_{2}b_{1} & 0
\end{bmatrix}
\in  I.
\end{align}
$$
Thus, $I$ is a subring of $M_{2}(\mathbb{R})$.

Let $\begin{bmatrix}i_{1} & 0\\ i_{3} & 0\end{bmatrix} \in I$ and $\begin{bmatrix}a & b\\c & d\end{bmatrix} \in M_{2}(\mathbb{R})$.
$$
\begin{align}
\begin{bmatrix}a & b\\c & d\end{bmatrix} \cdot \begin{bmatrix}i_{1} & 0\\ i_{3} & 0\end{bmatrix}
= 
\begin{bmatrix}
ai_{1}+bi_{3} & 0 \\
ci_{1}di_{3} & 0
\end{bmatrix}
\in  I.
\end{align}
$$
Thus $I$ is a left ideal.

On the other hand, consider the example
$$
\begin{align}
\begin{bmatrix}
1 & 0 \\
1 & 0
\end{bmatrix}
\cdot 
\begin{bmatrix}
1 & 1 \\
1 & 1
\end{bmatrix}
=
\begin{bmatrix}
1 & 1 \\
1 & 1
\end{bmatrix}
\notin  I.
\end{align}
$$
The righthand matrix is in $M_{2}(R)$ and the lefthand matrix is in $I$, but the multiplication yields an element not in $I$, meaning $I$ is *not* a right ideal.
