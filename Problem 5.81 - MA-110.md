---
aliases:
  - All normal subgroups are kernels
tags:
  - batch/school/class/ma110
  - batch/math
type: Problem
---
# Problem 5.81 MA-110

> [!problem] Problem 5.81
>     In [[Pre-Work Problems 69 Through 72 MA-110#^efc336|Problem 71]], you proved that all kernels are normal subgroups. Prove that all normal subgroups are kernels. That is, give a group $G$ with a [[Definition 5.2 MA-110|normal subgroup]] $N \trianglelefteq G$, give a definition for a [[Definition 3.1.1 MA-110|homomorphism]] $\phi:G\longrightarrow G/N$ such that $\ker(\phi)=N$, and show that the phi you define really is a [[Definition 3.1.1 MA-110|homomorphism]] with this [[Definition 3.4 MA-110|kernel]].

Let $N\trianglelefteq G$ for a group $G$, and consider the function $\phi:G\longrightarrow G/N$ such that
$$
\phi(g) = gN \qquad \text{for all } g \in  G.
$$
[[Pre-Work Problems 60 Through 63 MA-110#^0d748d|Problem 61]] guarantees that $\phi(g)$ is a well-defined function.

Let $a,b \in G$.
$$
\begin{align}
\phi(ab)&=(ab)N \\
N\phi (ab)&= N(ab)N \\
\phi(ab) &= N(ab)N && N \text{ is the identity of } G/H\\
\phi(ab) &= (Na)(bN) &&\text{ associativity of coset multiplication} \\
\phi(ab) &=  (aN)(bN) && N \trianglelefteq G \\
\phi(ab) &=  \phi(a)\phi(b).
\end{align}
$$
Thus, $\phi$ is a [[Definition 3.1.1 MA-110|homomorphism]].

As discussed in [[Pre-Work Problems 73 Through 77 MA-110#^6bd883|Problem 76]], $N$ is the identity of $G/N$. Further, $\phi(g)=gN=N$ if and only if $g \in N$ (combination of [[Pre-Work Problems 54 Through 59 MA-110#^2d7d15|Problem 58]] and [[Pre-Work Problems 60 Through 63 MA-110#^0fd621|Problem 60]].) Thus, $N$ is exactly the [[Definition 3.4 MA-110|kernel]] of $\phi.$
