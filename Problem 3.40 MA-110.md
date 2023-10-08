---
aliases: 
tags:
  - batch/school/class/ma110
  - batch/math
type: Problem
---
# Problem 3.40 MA-110

> [!problem] Problem 3.40
> Draw up an operation table for each of the following groups. Then decide which pairs of these are [[Definition 3.1.2 MA-110|isomorphic]], in the sense of the intuitive "reordering and renaming" description given above; if reordering is necessary, show the reordering; also specify the renaming.
> 1. $\langle \mathbb{Z}_{4}, +\rangle$
> 2. $U(8)$
> 3. $\mathbb{Z}_{2}\times \mathbb{Z}_{2}$, with operation addition modulo 2 on each component.
> 4. $G=\{ 1,-1,i,-i \}$, with operation multiplication in the complex numbers. Recall that $i^{2}=-1$.

^fd9a05

$U(8)$ is [[Definition 3.1.2 MA-110|isomorphic]] to $\langle \mathbb{Z}_{2}\times \mathbb{Z}_{2}, +\rangle$. If rename the following symbols they should have the same multiplication table
$$
\begin{align}
1 &\to (0,0)\\
3 &\to (0,1)\\
5 &\to (1,0)\\
7 &\to (1,1)
\end{align}
$$

| $U(8)$ | 1   | 3   | 5   | 7   |
| ---- | --- | --- | --- | --- |
| 1    | 1   | 3   | 5   | 7   |
| 3    | 3   | 1   | 7   | 5   |
| 5    | 5   | 7   | 1   | 3   |
| 7    | 7   | 5   | 3   | 1   |


| $\langle \mathbb{Z}_{2}\times \mathbb{Z}_{2},+\rangle$ | (0,0) | (0,1) | (1,0) | (1,1) |
| ------------------------------------------------------ | ----- | ----- | ----- | ----- |
| (0,0)                                                  | (0,0) | (0,1) | (1,0) | (1,1) |
| (0,1)                                                  | (0,1) | (0,0) | (1,1) | (1,0) |
| (1,0)                                                  | (1,0) | (1,1) | (0,0) | (0,1) |
| (1,1)                                                  | (1,1) | (1,0) | (0,1) | (0,0) |

- - -

$\langle \{ 1,-1,i,-i \}, \times \rangle$ is [[Definition 3.1.2 MA-110|isomorphic]] to $\langle \mathbb{Z}_{4}, +\rangle$. If we give the following renaming
$$
\begin{align}
1 \to 0\\
i \to 1\\
-1 \to 2\\
-i \to3
\end{align}
$$
then the multiplication tables should match.

| $\langle \{ 1,-1,i,-i \}, \times \rangle$ | 1   | i   | -1  | -i  |
| ----------------------------------------- | --- | --- | --- | --- |
| 1                                         | 1   | i   | -1  | -i  |
| i                                         | i   | -1  | -i  | 1   |
| -1                                        | -1  | -i  | 1   | i   |
| -i                                        | -i  | 1   | i   | -1  |

| $\langle \mathbb{Z}_{4}, +\rangle$ | 0   | 1   | 2   | 3   |
| ------------------------------ | --- | --- | --- | --- |
| 0                              | 0   | 1   | 2   | 3   |
| 1                              | 1   | 2   | 3   | 0   |
| 2                              | 2   | 3   | 0   | 1   |
| 3                              | 3   | 0   | 1   | 2   |

