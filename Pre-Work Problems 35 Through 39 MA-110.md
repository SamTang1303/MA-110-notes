---
aliases: []
tags:
  - batch/school/class/ma110
  - subject/math
---
Sam Tang
Dr. Hunter
Abstract Algebra
2023-09-10
# Pre-Work Problems 35 Through 39 MA-110

> [!problem] Problem 2.35
> Let $G$ be a group, and let $g$ be a fixed element of $G$. Define $H=\{ g^{n} : n \in \mathbb{Z}  \}$. Prove that $G$ is a subgroup of $G$.

Let $G$ be a group with identity $e$ and let $g$ be a fixed element of $G$. Consider the set $H=\{ g^{n}:n \in \mathbb{Z} \}$.

$g^{0}$ is defined to be the identity, so clearly $e \in H$.

Let $a, b \in H$. We know for some $m,n \in \mathbb{Z}$, $a=g^{n}$ and $b=g^{m}$.
$$
\begin{align}
ab &= g^{n}g^{m}\\
&= g^{n+m} && \text{By Problem 16}
\end{align}
$$
$n+m$ is clearly still an integer, so $ab \in H$, and $H$ is closed under the group multiplication.

Let $x \in G$. For some $n \in \mathbb{Z}$, $x=g^{n}$. $x^{-1}=g^{-n}$. Because $-n$ is still an integer, $x^{-1} \in H$. Therefore $H$ is closed under inverses and satisfies all the criteria for a subgroup.

> [!problem] Problem 2.36
> Show that all of the subgroups considered in [[Pre-Work Problems 29 Through 34 MA-110#^1df4b6|Problem 29]] are cyclic, and write each subgroup in the form $\langle a\rangle$, for a suitably chosen generator $a$ in the parent group.

1 ) Let $M_{n}$ denote the set of all multiples of some integer $n$. From Problem 29 we know all subgroups $\mathbb{Z}$ take the form $M_{n}$ where $n$ is any integer. 

Let $k$ be given and consider $M_{k}$. Any element of $M_{k}$ can be written as $c \cdot k$ where $c \in \mathbb{Z}$. This is simply the additive notation for $k^{c}$, so clearly the group is cyclic and can be represented as $\langle k\rangle$. 

2 ) The subgroups of $\langle \mathbb{Z}_{6}, +\rangle$
$$
\begin{align}
&\{ 0 \} = \langle 0\rangle\\
& \{ 0,2,4 \} = \{ 2 \cdot 0 , 2 \cdot 1, 2 \cdot 2\} = \langle 2\rangle &&\\
&\{ 0,3 \} = \{ 0 \cdot 3, 3 \cdot 1 \} = \langle 3\rangle.
\end{align}
$$
Again, remember that the operation in these groups is addition, so multiplication corresponds to exponentiation in multiplicative notation.

3 ) The subgroups of $\langle \mathbb{Z}^{*}_{5}, \times\rangle$
$$
\begin{align}
& \{ 1 \} = \langle 1\rangle\\
& \{ 1,4 \} = \{ 4^{2}, 4^{1} \} = \langle 4\rangle
\end{align}
$$

> [!problem] Problem 2.37
> 1. Prove that every cyclic group is abelian.
> 2. State the contrapositive of the statement in part 1, and use it to find an example of a group that isn't cyclic.
> 3. Give a counterexample to show that the converse of the statement in part 1 is false.

1 ) Let $G$ be a cyclic group with generator $g$ (i.e. $G=\langle g\rangle$.) 

Let $a, b \in G$. Because $G$ is cyclic, for some $n,m \in \mathbb{Z}$, $a=g^{n}$ and $b=g^{m}$.
$$
ab = g^{n}g^{m}= g^{n+m}=g^{m+n} = g^{m}g^{n} = ba.
$$
The second equality is justified by [[Pre-Work Problems 16 Through 22 MA-110#^1cc1e6|Problem 16]]. Thus, $ab=ba$ and $G$ is abelian.

2 ) The contrapositive of the statement in part 1 is: If a group is not abelian, then it is not cyclic. That proves that $D_{3}$ cannot be cyclic, because we know it is not commutative.

3 ) The converse of the statement in part 1 is: If a group is abelian, then it is cyclic. We will prove this false by counterexample.

Consider the subgroup of $S_{4}$.
$$
G = \{(1), (1\,2), (3 \, 4), (1\,2)(3\, 4) \}.
$$
Because it is a subgroup it is also a group. Clearly, the group is commutative. Yet every element is its own inverse, so none of them can be the generator for the group. Thus, we have found a group that is abelian,  but not cyclic.

<div class="page-break" style="page-break-after: always;"></div> 

> [!problem] Problem 2.38
> Let $G$ and $H$ be groups. Prove that if $G\times H$ is a cyclic group, then $G$ and $H$ are both cyclic groups.

Let $G$ and $H$ be groups and suppose $G\times H$ is a cyclic group with generator $\langle (g,h)\rangle$.

Let $a \in G$ and $b \in H$. By the definition of a cartesian product, $(a,b) \in G\times H$. Because $G\times H$ is cyclic, there exists some $n \in \mathbb{Z}$ such that
$$
(a,b) = (g,h)^{n} = (g^{n},h^{n}).
$$
Therefore, $a=g^{n}$ and $b=h^{n}$. Because we did this for an arbitrary $a \in G$ and $b \in H$, it must be true that $G=\langle g\rangle$ and $H=\langle h\rangle$.

> [!problem] Problem 2.39
> 1. Prove that $U(n)$ is a group under multiplication modulo $n$.
> 2. A group of the form $U(n)$ is called a "$u$-group". Are all $U$-groups cyclic? Prove or disprove.

1 ) For some $n \in \mathbb{N}$, consider $U(n)$. 

$1 \cdot1=1$, so $1 \in U(n)$ and $1 \cdot a=a$ for all $a \in U(n)$. Therefore $U(n)$ has an identity element.

By definition, every element of $U(n)$ has an inverse, so this criterion is trivially satisfied.

Let $a,b \in U(n)$. By definition of $U(n)$ $a^{-1}$ and $b^{-1}$ exist.
$$
(ab)(b^{-1}a^{-1}) = a(bb^{-1})a^{-1}=(ae)a^{-1}=aa^{-1}=1
$$
This verifies that $ab$ and $b^{-1}a^{-1}$ are inverses of each other and therefore both in $U(n)$. Thus, $U(n)$ is closed under multiplication and thus it is a valid binary operator.

Finally, multiplication in $U(n)$ is clearly associative because it is the same as multiplication in $\mathbb{Z}_{n}$. Therefore, $U(n)$ is a group.

2 ) I am not sure how to prove this one.