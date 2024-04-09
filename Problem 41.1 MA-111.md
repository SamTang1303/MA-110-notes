---
aliases: 
tags:
  - batch/school/class/ma111
  - batch/math
type: Problem
---
# Problem 41.1 MA-111

> [!problem] Problem 41.1
> Assume that $c=2P_{1}P_{3}P_{4}-4P_{3}P_{4}P_{6}+3P_{3}P_{2}P_{4}+P_{1}P_{6}P_{4}$ is a two chain of a certain simplicial complex $X$.
> 1. Compute $\partial_{2}(c)$
> 2. Is $c$ a 2-cycle?
> 3. Is $\partial_{2}(c)$ a 1-cycle?

1 )
$$
\begin{align}
\partial_{2}(c) &= 2(P_{3}P_{4}-P_{1}P_{4}+P_{1}P_{3}) - 4(P_{4}P_{6}-P_{3}P_{6}+P_{3}P_{4}) \\&+ 3(P_{2}P_{4} - P_{3}P_{4}+P_{3}P_{2}) + (P_{1}P_{6}-P_{1}P_{4}+P_{6}P_{4}) \\
&= -5P_{3}P_{4} - 4P_{1}P_{4}+2P_{1}P_{3}-3P_{4}P_{6}-4P_{3}P_{6}+3P_{2}P_{4}-P_{2}P_{3}+P_{1}P_{6}+P_{6}P_{4}. \\
\end{align}
$$
2 ) No, because $\partial_{2}(c)$ is not zero, it is not a two-cycle.

3 )
$$
\begin{align}
\partial_{1}(\partial_{2}(c)) &= -5(P_{4}-P_{3})-4(P_{4}-P_{1})+2(P_{3}-P_{1})-3(P_{6}-P_{4})\\&-4(P_{6}-P_{3})+3(P_{4}-P_{2})-(P_{3}-P_{2})+(P_{6}-P_{1}) + (P_{4}-P_{6}) \\
&= 0.
\end{align}
$$
Thus, $\partial_{2}(c)$ is a one-cycle.
