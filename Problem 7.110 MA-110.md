---
aliases: 
tags:
  - batch/school/class/ma110
  - batch/math
type: Problem
---
# Problem 7.110 MA-110

> [!problem] Problem 7.110
> Let $I$ be an ideal of a ring $R$, and let $a,b \in R$. Prove that the coset product does not depend on the choice of coset representatives. That is, prove that if $a+I=y+I$ and $b+I=x+I$, then $ab+I=xy+I$.

Let $I$ be an ideal of a ring $R$, and let $a,b,x,y \in R$ such that $a+I=x+I$ and $b+I=y+I$. This assumption implies
$$
\begin{align}
x &= a + i_{1} &&\text{for some } i_{1} \in I \\
&\text{and} \\
y&= b + i_{2} && \text{for some } i_{2} \in  I.
\end{align}
$$
Thus,
$$
\begin{align}
xy + I &= (a+i_{1})(b+i_{2}) + I \\
&= (ab + i_{1}b + ai_{2} + i_{1}i_{2}) + I\\
&= (ab + i_{3} + i_{4} + i_{5} ) + I && \text{for some }i_{3},i_{4},i_{5} \in  I; I \text{ is an ideal} \\
&= (ab + i_{6}) + I && \text{for some }i_{6} \in  I; I \text{ is an ideal} \\
&= ab + I. && \text{absorption}
\end{align}
$$
Thus, the given definition of coset product is well-defined.
