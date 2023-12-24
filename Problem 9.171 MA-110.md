---
aliases: 
tags:
  - batch/school/class/ma110
  - batch/math
type: Problem
---
# Problem 9.171 MA-110

> [!problem] Problem 9.171
> Given a field $F$ and a non-constant polynomial $f(x) \in F[x]$, prove that there is an extension field $E$ that contains a copy of $F$ and a root of $f(x)$.

Let $F$ be a field, and $f(x) \in F[x]$ a non-constant polynomial. If $f(x)$ is irreducible, let $g(x)=f(x)$. If $f(x)$ is not irreducible, factor $f(x)$ into terms of lower degree, and continue to do so until we have an irreducible factor of $f(x)$, which we will call $g(x)$.

Consider the field $E=F[x]/(g(x))$. We know this to be a field by [[Problem 9.168 MA-110|Problem 168]]. Further, consider the subset of $F[x]/(g(x))$, $F/(g(x))=\{ a + g(x)\mid a \in F \}$. For any element $a +(g(x)) \in F/g(x)$, consider the map $\phi:F/(g(x))\longrightarrow F$ such that $\phi(a+(g(x)))=r(x)$, where $r(x)$ is the remainder produced by applying the division algorithm to any element of $a+(g(x))$ and $g(x)$. [[Problem 8.126 MA-110|Problem 126]] guarantees that this map is well-defined, and that $r(x)=a$.

We will now show that $F/g(x)\simeq F$. Let $a+g(x), b+g(x) \in F/g(x)$.
$$
\begin{align}
\phi\Big(\big(a+(g(x))\big)+\big(b+(g(x))\big)\Big) &= \phi\Big(a+b+(g(x))\Big) \\
&= a+b \\
&= \phi(a)+\phi(b). \\
&\text{ Further,} \\
\phi\Big(\big(a+(g(x))\big)\big(b+(g(x))\big)\Big) &= \phi\Big(ab+\big(g(x)\big)\Big) \\
&= ab \\
&= \phi(a)\phi (b).
\end{align}
$$
Thus, $\phi$ is a [[Problem 6.97 MA-110|ring homomorphism]]. Let $a \in F$. Then $a+(g(x)) \in F/(g(x))$ and $\phi(a+(g(x)))=a$. Therefore, $\phi$ is onto. For some $a+(g(x)),b+g(x) \in F/(g(x))$, suppose that $\phi(a+(g(x)))=\phi(b+(g(x)))$ and $a=b$. Then clearly $a+(g(x))=b+(g(x))$. Thus $\phi$ is also one-to-one. We have now shown that $\phi$ is an isomorphism, implying that
$$
F\simeq F/(g(x))\subseteq F[x]/(g(x))=E.
$$
Therefore, $E$ contains a copy of $F$, up to isomorphism.

Further, $f(x+(g(x)))=f(x)+(g(x))=(g(x))$, because $f(x)$ is a multiple of $g(x)$. Thus $x+(g(x))$ is a root of $f(x)$ in $E$.
