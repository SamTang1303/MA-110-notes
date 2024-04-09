---
aliases: 
tags:
  - batch/school/class/ma111
  - batch/math
type: Problem
---
# Problem 10.183 MA-111

> [!problem] Problem 10.183
> Consider the group $G=\langle (1\ 2)(3\ 4), (1\ 3)\rangle$ from [[Problem 10.174 MA-111|Problem 174]]. Let $H=\langle (1\ 3)\rangle$. List all the left cosets of $H$ in $G$. For the action, given in [[Problem 10.179 MA-111|Problem 179]], of $H$ on $X=\{ gH \mid g \in G \}$, compute the [[Definition 10.7 MA-111|fixed point]] set $X_{H}$ and all the [[Definition 10.8 MA-111|orbits]] $Hx_{i}$, and show that the class equation holds.

Consider the group $G=\langle (1\ 2)(3\ 4), (1\ 3)\rangle$ from [[Problem 10.174 MA-111|Problem 174]]. Let $H=\langle (1\ 3)\rangle$.
$$
\{ gH \mid g \in  G \} = \Big\{ \{ (1\ 3),(1) \}, \{ (1\ 4)(2\ 3), (1\ 2\ 3\ 4) \}, \{ (2\ 4) , (1\ 3) (2\ 4) \}, \{(1\ 2)(3\ 4) ,(1\ 4\ 3\ 2) \}\Big\}.
$$
Consider the action, given in Problem 179, of $H$ on $X=\{ gH \mid g \in G \}$.
$$
X_{H} = \Big\{ \{ (1\ 3), (1) \}, \{ (2\ 4), (1\ 3)(2\ 4)\} \Big\}.
$$
$$
\begin{align}
H \{ (1\ 4)(2\ 3), (1\ 2\ 3\ 4) \} &= \Big\{ \{ (1\ 4)(2\ 3), (1\ 2\ 3\ 4) \}, \{ (1\ 4\ 3\ 2), (1\ 2)(3\ 4) \} \Big\}. \\
\end{align}
$$
The orbits of the elements of $X_{H}$ are not listed because they only consist of one element, themselves.
$$
\left| X_{H} \right| +\left| H \{ (1\ 4)(2\ 3), (1\ 2\ 3\ 4) \} \right|  = 2 + 2 =4 = \left| X \right| .
$$
Thus, the class equation holds.
