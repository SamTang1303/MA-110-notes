Sam Tang
Dr. Hunter
Abstract Algebra
2023-08-31
# Pre-Work Problems 8 Through 15 MA-110

> [!problem] Problem 1.8
> Provide at least two examples of abelian groups.

1. The group $\langle \mathbb{Z}, +\rangle$.
2. The group $\langle \mathbb{R}\setminus{0}, \times \rangle$.

> [!problem] Problem 1.9
> Refer back to [[Pre-Work Problems 1 Through 7 MA-110#^problem1-5|Problem 5]]. Identify the finite groups in that question, and for each of these state the order of the group.

1. Infinite order.
2. Not a group.
3. Not a group.
4. Not a group.
5. Infinite order.
6. Order 10 (five rotations for each side of the pentagon).
7. Order 6.
8. Not a group.
9. Not a group.
10. Order 4.

> [!problem] Problem 1.10
> Provide at least two examples of non-abelian groups. For one of these, prove that the group is non-abelian. *This problem was worked on with Brenna Corcoran.*

1. The set of all 2x2 matrices with real entries and non-zero determinants along with matrix multiplication. *Proof.* $$\begin{bmatrix}
1 & 2 \\
3 & 4
\end{bmatrix} \cdot
\begin{bmatrix}
4 & 3 \\
2 & 1
\end{bmatrix}=
\begin{bmatrix}
8 & 5 \\
20 & 13
\end{bmatrix}\neq
\begin{bmatrix}
4 & 3 \\
2 & 1
\end{bmatrix} \cdot
\begin{bmatrix}
1 & 2 \\
3 & 4
\end{bmatrix}=
\begin{bmatrix}
13 & 20 \\
5 & 8
\end{bmatrix}
$$
2. The group all all possible moves of a rubiks cube along with the operation of composing those moves.

> [!problem] Problem 1.11
> Suppose $\langle G,*\rangle$ is a group, with $s,t$ and $u$ in $G$. Prove or disprove as appropriate:
> If $s*t=u*s$, then $t=u$

*Proof.* We will disprove by counterexample. Consider the group of symmetries of an equilateral triangle. $\rho_{1}, \rho_{2, }\mu_{1, }$ are all elements of the group. Referring back to the table on page 2, $\mu_{1}\circ\rho_{1}=\mu_{3}=\rho_{2}\circ\mu_{1}$. Clearly $\rho_{1}\neq \rho_{2}$, so the proposed theorem must be false.

> [!problem] Problem 1.12
> Let $G$ be a group, and let $a \in G$. Prove that $a$ has a unique inverse.

*Proof.* Let $\langle G,*\rangle$ be a group with $a \in G$ and $b,c$ as inverses of $a$. Further, let $e$ be the identity of the group.
$$
\begin{align}
e &= a *b\\
c*e &= c*(a*b)\\
c &= (c*a)*b\\
c &= e*b\\
c &= b
\end{align}
$$
> [!problem] Problem 1.13
> Suppose $G$ is a group, with $a$ and $b$ in $G$. Prove that if $a*b=e$, then $b*a=e$. Use this to prove that if $G$ is a group, with $a$ and $b$ in $G$ and $a*b=e$, then $a$ is the inverse of $b$.

^f23d7c

Let $\langle G, *\rangle$ be a group with $a,b \in G$ and suppose $a*b = e$. Because $\langle G,*\rangle$ is a group, $a^{-1}$ exists and is we can apply it to both sides and preserve equality.
$$
\begin{align}
a^{-1}*a*b &= a^{-1}*e\\
b&= a^{-1}
\end{align}
$$
Thus, if $a*b=e$, then $b=a^{-1}$. By definition of an inverse, this implies $b*a=e$.

<div class="page-break" style="page-break-after: always;"></div> 

> [!problem] Problem 1.14
> In a group $G$, if $a \in G$ and $n \in \mathbb{N}$, then both $(a^{n})^{-1}$ and $(a^{-1})^{n}$ have unambiguous interpretations in terms of the definitions above. Prove that the two are in fact equal.

Let $G$ be a group with $a,b \in G$ and identity $e$. We will prove the following by induction:
> For any $n \in \mathbb{N}$, $(a^{n})^{-1}=(a^{-1})^{n}$ and $aa^{n}=a^{n}a$.

**Base case:** Clearly $a =(a^{1})^{-1}=(a^{-1})^{1}$ and $a*a^{1}=a^{1}*a$, so the base case is verified.

**Inductive hypothesis:** For some $n \in \mathbb{N}$, suppose $(a^{n-1})^{-1}=(a^{-1})^{n-1}$ and $aa^{n-1}=a^{n-1}a$.

**Inductive Step:** 
$$
a^{n}a=a(aa^{n-1})=a(a^{n-1}a)=(aa^{n-1})a=a^{n}a \qquad (1)
$$
The second equality is justified by the inductive hypothesis.
$$
\begin{align}
(a^{-1})^{n}*a^{n} &= a^{-1}(a^{-1})^{n-1}*aa^{n-1}\\
&= a^{-1}(a^{-1})^{n-1}*a^{n-1}a\\
&= a^{-1}[(a^{-1})^{n-1}a^{n-1}]a\\
&= a^{-1}[(a^{n-1})^{-1}a^{n-1}]a\\
&= a^{-1}ea\\
&= a^{-1}a\\
&= e
\end{align}
$$
Therefore, by definition $(a^{-1})^{n} = (a^{n})^{-1}$, and the proof is complete.

> [!problem] Problem 1.15
> Prove that if $G$ is a group, with $a \in G$, then $(a^{-1})^{-1}=a$.

Let $G$ be a group, with $a \in G$. By definition of $a^{-1}$, $aa^{-1}=e$ and $a^{-1}a=e$. This happens to also show, by definition, that the inverse of $a^{-1}$ is $a$.
