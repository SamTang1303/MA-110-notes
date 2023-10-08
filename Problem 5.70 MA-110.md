---
aliases: 
tags:
  - batch/school/class/ma110
  - batch/math
type: Problem
---
# Problem 5.70 MA-110

> [!problem] Problem 5.70
> Show, by giving an example group $G$, a subgroup $H$, and an element of $a \in G$, that $Ha$ can be different from $aH$. Is the statement, "If $x \in aH$ and $y \in bH$, then $xy \in (ab)H$" true for all $a,b \in G$ in your example?

Let $G=D_{3}$, and consider the subgroup $H=\{ (1), (2\,3) \}$. 
$$
(1\,2\,3)H=\{ (1\,2\,3),(1\,2) \} \neq \{ (1\,2\,3),(1\,3) \} =H(1\,2\,3).
$$
Therefore, in general, left cosets are not equal to right cosets.

In this example, if we choose $a=(1\ 2\ 3)$,  $b = (2\ 3)$, $x=(1)$, and $y =(2\ 3)$,
then $xy=(2\ 3)\notin (ab)H=(1\ 2)H = \{ (1\ 2), (1\ 2\ 3) \}$. The statement given does not hold.
