---
aliases: 
tags:
  - batch/school/class/ma110
  - batch/math
type: Problem
---
# Problem 1.6 MA-110

> [!problem] Problem 1.6
> Prove that the following is, or is not a group, as appropriate. The set $\mathbb{R}\setminus \{ 1 \}$ with operation defined by $a*b=a+b-ab$ for all $a,b \in S$.

$\langle S,*\rangle$ is a group, with an identity element $0$ and and inverse, for any element $a \in S$, of $\frac{a}{a-1}$.

*Proof.* First notice that the $*$ operator is clearly commutative. Let $s \in S$. $0*s=s*0=s+0-0 \cdot s=s$. Therefore $0$ is the identity element.

Let $a,b \in S$ and suppose $b = \frac{a}{a-1}$.
$$
\begin{align}
a*b &= a + \frac{a}{a-1} - a  \cdot \frac{a}{a-1}\\
&= \frac{a^{2}-a}{a-1}+\frac{a}{a-1}-\frac{a^{2}}{a-1}\\
&= \frac{0}{a-1}\\
&= 0
\end{align}
$$
Thus, $b$ is the inverse of a, and every element of $S$ has an inverse. Note the last equality relies on $1$ being  from $S$, otherwise $\frac{0}{a-1}=0$ would not hold because the left hand side could be undefined.

Let $a,b,c \in S$.
$$
\begin{align}
(a * b) * c &= (a + b - ab) + c - c(a + b - ab)\\
&= a+b-ab+c-ac-bc+abc\\
&= a+b+c -ab -ac -bc + abc\\
a * (b*c) &= a + (b+c-bc) - a(b+c-bc)\\
&= a + b +c -bc -ab - ac +abc\\
&= a + b +c -ab - ac -ab + abc.
\end{align}
$$
Because these two quantities are equal, the operation is distributive and all of the criteria for a group have been satisfied.
