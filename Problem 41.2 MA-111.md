---
aliases: 
tags:
  - batch/school/class/ma111
  - batch/math
type: Problem
---
# Problem 41.2 MA-111

> [!problem] Problem 41.2
> Compute $\partial_{2}(\partial_{3}(P_{1}P_{2}P_{3}P_{4}))$ and show that it is 0, completing the proof of the Theorem 41.9.

$$
\begin{align}
\partial_{2}(\partial_{3}(P_{1}P_{2}P_{3}P_{4})) &= \partial_{2}(P_{2}P_{3}P_{4} - P_{1}P_{3}P_{4}+P_{1}P_{2}P_{4}-P_{1}P_{2}P_{3}) \\
&= (P_{3}P_{4} - P_{2}P_{4} + P_{2}P_{3}) -(P_{3}P_{4}-P_{1}P_{4}+P_{1}P_{3}) \\&+ (P_{2}P_{4} - P_{1}P_{4}+P_{2}P_{4}) - (P_{2}P_{3}-P_{1}P_{3}+P_{1}P_{2}) \\
&= 0.
\end{align}
$$
