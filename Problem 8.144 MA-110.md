---
aliases: 
tags:
  - batch/school/class/ma110
  - batch/math
type: Problem
---
# Problem 8.144 MA-110

> [!problem] Problem 8.144
> Suppose that you carry out the Euclidean algorithm on some polynomials $f(x)$ and $g(x)$ in $F[x]$, a polynomial ring over a field, and that after three steps you find that $r_{3}(x)=u$, a constant polynomial in $F[x]$. Find polynomials $a(x)$ and $b(x)$ (in terms of $u$, the $q_{i}$'s and the $r_{i}$'s) such that $a(x)f(x)=b(x)g(x)=1$.

$$
\begin{align}
f&=q_{1}g + r_{1} \\
g &= q_{2}r_{1} + r_{2} \\
r_{1} &= q_{3}r_{2} +u.
\end{align}
$$
Thus,
$$
\begin{align}
u &= r_{1}-q_{3}(g-q_{2}r) \\
&= r_{1}-q_{3}g-q_{3}q_{2}r_{1} \\
&= r_{1}(1-q_{3}q_{2})-q_{3}g \\
&= (f-q_{1}g)(1-q_{3}q_{2}) - q_{3}g \\
&= f(1-q_{3}q_{2})-g(-q_{1}+q_{1}q_{2}q_{3}-q_{3}).
\end{align}
$$
Multiplying by $u^{-1}$ yeilds
$$
f(1-q_{3}q_{2})u^{-1} +g(-q_{1}+q_{1}q_{2}q_{3}-q_{3})(-u^{-1}) = 1
$$
giving values of $a(x)=(1-q_{3}q_{2})u^{-1}$ and $b(x)=(-q_{1}+q_{1}q_{2}q_{3}-q_{3})(-u^{-1})$.
