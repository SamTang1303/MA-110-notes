---
aliases: 
tags:
  - batch/school/class/ma111
  - batch/math
type: Problem
---
# Problem 11.212 MA-111

> [!problem] Problem 11.212
> Check that $\sqrt{ 3 } \notin \mathbb{Q}(\sqrt{ 2 })$. It follows that $\{ 1,\sqrt{ 3 } \}$ is a basis for $\mathbb{Q}(\sqrt{ 2 },\sqrt{ 3 })$ over $\mathbb{Q}(\sqrt{ 2 })$. Use the Degree Multiplication Theorem to find a basis for $\mathbb{Q}(\sqrt{ 2 },\sqrt{ 3 })$ as a vector space over $\mathbb{Q}$. Justify your answer.

**Showing that $\sqrt{ 3 } \notin \mathbb{Q}(\sqrt{ 2 })$**. Suppose to the contrary that $\sqrt{ 3 } \in \mathbb{Q}(\sqrt{ 2 })$. Then, for some $a,b \in \mathbb{Q}$, $a+b\sqrt{ 2 }=\sqrt{ 3 }$.
$$
\begin{align}
a+b\sqrt{ 2 }&=\sqrt{ 3 } \\
(a+b\sqrt{ 2 })^{2}&=3 \\
a^{2}+2\sqrt{ 2 }ab+2b^{2} &= 3 \\
a^{2}+2b^{2}-3 &= -2\sqrt{ 2 }ab \\
\frac{a^{2}+2b^{2}-3}{-2ab}=\sqrt{ 2 }.
\end{align}
$$
Because $\sqrt{ 2 }$ is irrational, this is a contradiction. Thus, $\sqrt{ 3 }\notin \mathbb{Q}(\sqrt{ 2 })$. The Degree Multiplication Theorem says the basis for $\mathbb{Q}(\sqrt{ 2 },\sqrt{ 3 })$ will be
$$
\{ 1 \cdot 1,1 \cdot \sqrt{ 3 },\sqrt{ 2 } \cdot 1,\sqrt{ 2 }  \cdot \sqrt{ 3 } \}=\{ 1,\sqrt{ 2 },\sqrt{ 3 }, \sqrt{ 2 }\sqrt{ 3 } \}.
$$
