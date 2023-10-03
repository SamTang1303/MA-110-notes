---
aliases: []
tags:
  - batch/school/class/ma110
  - subject/math
---
Sam Tang
Dr. Hunter
Abstract Algebra
2023-09-03
# Pre-Work Problems 16 Through 22 MA-110

> [!problem] Problem 1.16
> 
> Suppose $G$ is a group, with $a \in G$. Using notation like
> $$
> a^{n} = \underbrace{a*a* \cdots*a}_{n}
> $$
> give an informal argument that $a^{m}a^{n}=a^{m+n}$ and $(a^{m})^{n}=a^{mn}$ for all $m,n \in \mathbb{N}$. (It is tedious, but not hard, to show that these statements hold for $m,n \in \mathbb{Z}$ as well. A formal proof requires induction.)

^1cc1e6

Let $G$ be a group, $a \in G$, and $m,n \in \mathbb{N}$.
$$
\begin{align}
a^{n}*a^{m} &= (\underbrace{ a*a*\cdots  *a }_{ n }) * (\underbrace{ a*a *  \cdots*a }_{ m }) && \text{associativity}\\
&= \underbrace{ a*a*  \cdots*a }_{ n+m }\\
&= a^{n+m}
\end{align}
$$
Similarly,
$$
\begin{align}
(a^{m})^{n} &= (\underbrace{ a*a*\cdots  *a }_{ m })^{n}\\
&= \overbrace{ (\underbrace{ a*a*\cdots  *a }_{ m }) * (\underbrace{ a*a*\cdots  *a }_{ m }) *  \cdots*(\underbrace{ a*a*\cdots  *a }_{ m }) }^{n}\\
&= \underbrace{ a*a *  \cdots *a }_{ m*n }\\
&= a^{mn}.
\end{align}
$$

> [!problem] Problem 1.17
> Suppose $G$ is a group, with $a,b,$ and $x$ in $G$. If $x=a^{-1}b$, can we conclude that $xa=b$? Either prove this conclusion true, or provide a counterexample.

We will disprove with a counterexample, using the symmetries of an equilateral triangle as our group. Let $a=\mu_{1}$ (implying $a^{-1}=\mu_{1}$as well) and $b=\mu_{3}$. Then, 
$$
x=a^{-1}b= \mu_{1} * \mu_{3} = \rho_{1}
$$
But,
$$
xa=\rho_{1} * \mu_{1} = \mu_{2} \neq b
$$
Therefore, the theorem must be false.

> [!problem] Problem 1.18
> Prove or disprove, as appropriate: Suppose $G$ is a group, with $a,b,$ and $c$ in $G$. If $ac=bc$, then $a=b$.

*Proof.* Let $G$ be a group with $a,b,c \in G$. Further, let $ac=bc$. Because $G$ is a group, we know $c^{-1}$ exists.
$$
\begin{align}
ac&= bc\\
(ac)c^{-1}&= (bc)c^{-1}\\
a(cc^{-1})&= b(cc^{-1})\\
a &= b
\end{align}
$$

> [!problem] Problem 1.19
> Prove or disprove as appropriate: If $G$ is a group, with $a$ and $b$ in $G$, then $(ab)^{2}=a^{2}b^{2}$.

We will disprove by counterexample. Let $G$ be the symmetries of an equilateral triangle, and let $a=\rho_{1}$ and $b=\mu_{1}$.
$$
(ab)^{2}=(\rho_{1}\mu_{1})^{2}=(\mu_{2})^{2}= \rho_{0}
$$
But,
$$
a^{2}b^{2} = \rho_{1}^{2}\mu_{1}^{2} = \rho_{2}\mu_{1}=\mu_{3}.
$$
Because these two quantities are not equal the theorem must be false.

> [!problem] Problem 1.20
> Prove or disprove, as appropriate: If $G$ is a group, with $a$ and $b$ in $G$, then $(ab)^{-1}=a^{-1}b^{-1}$.

We will prove by counterexample. Once again, let $G$ be the group of symmetries of an equilateral triangle, and let $a=\rho_{1}$ and $b=\mu_{1}$.
$$
(ab)^{-1}= (\rho_{1}\mu_{1})^{-1}= (\mu_{2})^{-1}=\mu_{2}.
$$
Yet,
$$
a^{-1}b^{-1} = \rho_{1}^{-1}\mu_{1}^{-1} = \rho_{2}\mu_{1} = \mu_{3}.
$$
Because these two are not equal, the theorem does not hold in general.

> [!problem] Problem 1.21
> Prove or disprove, as appropriate: If $G$ is a group, with $a$ and $b$ in $G$, then $(ab)^{-1}=b^{-1}a^{-1}$.

*Proof.* Let $G$ be a group with $a,b \in G$ and an identity element $e$.
$$
\begin{align}
(ab)^{-1} (ab) &= e && \text{By definition}\\
(ab)^{-1}(ab)(b^{-1}a^{-1}) &= e(b^{-1}a^{-1})\\
(ab)^{-1}a(bb^{-1})a^{-1} &= b^{-1}a^{-1}\\
(ab)^{-1}(aa^{-1}) &= b^{-1}a^{-1}\\
(ab)^{-1} &= b^{-1}a^{-1}.
\end{align}
$$

> [!problem] Problem 1.22
> Suppose $G$ is a group, with $a$ and $b$ in $G$. Consider the equation $ax=b$.
> 1. Prove that $a^{-1}b \in G$.
> 2. Prove that by substituting that $x=a^{-1}b$ is a solution for the equation.
> 3. Prove that $x=a^{-1}b$ is the only solution for the equation $ax=b$; that is this solution is *unique*.

Let $\langle G,*\rangle$ be a group with $a,b \in G$.

1. By definition of a group, $a^{-1}$ exists and is unique. Because $*$ is a binary operator on $G$ and $a^{-1}$ and $b$ are both elements $G$, $a^{-1}b$ must be as well.
2. Let $x =a^{-1}b$. $a(a^{-1}b)=(aa^{-1})b=b$. Thus $x=a^{-1}b$ is a valid solution to the equation $ax=b$.
3. Let $x=c$ be a solution to the equation $ax=b$. Then, $ac=b$. $\langle G,*\rangle$ is a group, so we know $a^{-1}$ exists and is well-defined. Thus, $a^{-1}*a*c=a^{-1}*b$ and $c=a^{-1}*b$. Because we did this for a general solution, this solution must be unique. 