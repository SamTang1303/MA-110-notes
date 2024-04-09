---
aliases: 
tags:
  - batch/school/class/ma111
  - batch/math
type: Problem
---
# Problem 13.273 MA-111

> [!problem] Problem 13.273
> Explain why $\{ 1,i \}$ is a basis for $\mathbb{C}$ over $\mathbb{R}$. Use this fact and the quadratic formula to prove that, for any $a,b \in \mathbb{R}$, the equation $(x+iy)^{2}=a+bi$ has a solution where both $x$ and $y$ are real numbers. (Hence every complex number has a square root in $\mathbb{C}$.)

$\mathbb{C}$ is defined as the set $\{ a+bi \mid a,b \in \mathbb{R} \}$. This is also the definition for the spanning set of $1$ and $i$. The set $\{ 1,i  \}$ is clearly linearly independent, so it must be a basis for $\mathbb{C}$.

Let $a,b \in \mathbb{R}$. If you choose values $x,y$ such that
$$
\begin{align}
x&=\sqrt{ \frac{4a+\sqrt{ 16a^{2}+16b^{2} }}{8} } \in  \mathbb{R}\\
y&=\sqrt{ \frac{-4a+\sqrt{ 16a^{2}+16b^{2} }}{8} } \in  \mathbb{R}.
\end{align}
$$
Consider the value of the square of the complex number $x+iy$:
$$
\begin{align}
(x+iy)^{2} &= x^{2}+2ixy-y^{2} \\
&= \frac{4a+\sqrt{ 16a^{2}+16b^{2} }}{8}+2ixy- \frac{-4a+\sqrt{ 16a^{2}+16b^{2} }}{8} \\
&= \frac{8a}{8}+2ixy \\
&= a+2ixy \\
&= a+2i\sqrt{ \frac{(4a+\sqrt{ 16a^{2}+16b^{2} })(-4a+\sqrt{ 16a^{2}+16b^{2} })}{8^{2}} } \\
&= a+\frac{i}{4}\sqrt{ -16a^{2}+(16a^{2}+16b^{2}) } \\
&= a+ \frac{i}{4}\sqrt{ 16b^{2} } \\
&= a+\frac{i}{4}4b \\
&= a+bi.
\end{align}
$$
Thus, we can see that $a+bi$ does have a complex square root.
