---
aliases: 
tags:
  - batch/school/class/ma110
  - batch/math
type: Problem
---
# Problem 1.14 MA-110

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
