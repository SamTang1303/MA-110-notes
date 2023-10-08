---
aliases: 
tags:
  - batch/school/class/ma110
  - batch/math
type: Problem
---
# Problem 3.48 MA-110

> [!problem] Problem 3.48
> In each of the following, prove that the two groups specified are not [[Definition 3.1.2 MA-110|isomorphic]].
> 1. $S_{4}$ and $\mathbb{Z}_{6}\times \mathbb{Z}_{4}$
> 2. $\mathbb{Z}_{2}\times \mathbb{Z}_{4}$ and $\mathbb{Z}_{8}$
> 3. $U(10)$ and $\mathbb{Z}_{2}\times \mathbb{Z}_{3}$
> 4. $\langle \mathbb{Q}^{*},\times \rangle$ and $\langle \mathbb{Z},+\rangle$, where $\mathbb{Q}^{*}$ denotes the nonzero rational numbers.
> 5. $\langle \mathbb{R}^{*}, \cdot\rangle$ and $\langle \mathbb{R},+\rangle$.

1. $(1\,2\,3)(1\,2)=(1\,3)$ and $(1\,2)(1\,2\,3)=(23)$. Because these are not equal, $S_{4}$ cannot be abelian. On the other hand, $\mathbb{Z}_{6}\times \mathbb{Z}_{4}$ is abelian because it is the cross-product of two abelian groups. ([[Problem 2.27 MA-110|Problem 27]].) Therefore, [[Problem 3.46 MA-110|Problem 46]] tells us that the two groups are not isomorphic.
2. $1$ has order $8$ in $\mathbb{Z}_{8}$. For any element $(a,b) \in \mathbb{Z}_{2}\times \mathbb{Z}_{4}$, $(a,b)^{4}=(4a,4b)$, but anything times $4$ is $0$ in mod 2 and mod 4. Therefore, $(a,b)^{4}=(0,0)$, which is the groups identity element, implying no elements have order greater than 4. Therefore, by [[Problem 3.47 MA-110|Problem 47]], the groups are not isomorphic.
3. $U(10)=\{ 1,3,7,9 \}$ and has order 4. $\mathbb{Z}_{2}\times \mathbb{Z}_{3}= \{ (0,0),(0,1),(0,2),(1,0),(1,1),(1,2),(2,0),(2,1),(2,2) \}$ which has order $6$. Therefore, there can be no bijection between the sets and they cannot be isomorphic.
4. $\langle \mathbb{Z},+\rangle=\langle 1\rangle$ and is cyclic. If $\langle \mathbb{Q}^{*}, \cdot \rangle$ were cyclic, it would imply every element of the set could be represented as $a^{n}$ for some $a \in \mathbb{Q}^{*}$ and $n \in \mathbb{Z}$. Because $q$ is rational we could rewrite this as $\left( \frac{p}{q} \right)^{n}=\frac{p^{n}}{q^{n}}$ where $p,q \in \mathbb{Z}$ and are coprime. If we choose a prime $\rho\neq q$ then it is clear $\frac{1}{\rho }$ is not of this form. Therefore, $\langle \mathbb{Q}^{*}, \times \rangle$ cannot be cyclic or isomorphic to $\langle \mathbb{Z},+\rangle$.
5. In $\langle \mathbb{R}^{*},  \cdot \rangle$, $\langle -1\rangle=\{ -1,1 \}$ has order two. But, under $\langle \mathbb{R},  +\rangle$, $\langle x\rangle=\{ x^{n}:n \in \mathbb{Z} \}$ has infinite order for all $x\neq0$ and order $1$ when $x=0$. Therefore, $\langle \mathbb{R},+\rangle$ has no element of order $2$ and cannot be isomorphic to $\langle \mathbb{R}^{*},  \cdot \rangle$.
