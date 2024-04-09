---
aliases: 
tags:
  - batch/school/class/ma111
  - batch/math
type: Problem
---
# Problem 10.191 MA-111

> [!problem] Problem 10.191
> Investigate the above results for $G=S_{4}$ and $p=2$. In particular, determine all the subgroups of $S_{4}$ that have order $2^{i}$ for some $i$. For each of these subgroups, determine its normalizer.

$\left| S_{4} \right| = 24=2^{3}3$.
Subgroups of order 2:
$$
\begin{align}
&\text{subgroup} &&\text{normalizer}\\
&(1), (1\ 2)  && (1),(1\ 2), (3\ 4), (1\ 2)(3\ 4)\\
&(1), (1\ 3) && (1), (1\ 3), (2\ 4), (1\ 3)(2\ 4)\\ 
&(1), (1\ 4) && (1), (1\ 4), (2\ 3), (1\ 4)(2\ 3)\\
&(1), (2\ 3) && (1), (2\ 3), (1\ 4), (2\ 3)(1\ 4)\\
&(1), (2\ 4) && (1), (2\ 4), (1\ 3), (2\ 4)(1\ 3)\\
&(1), (3\ 4) && (1), (3\ 4), (1\ 2), (3\ 4)(1\ 2)\\
&(1), (1\ 2)(3\ 4) && (1),(1\ 2), (3\ 4), (1\ 2)(3\ 4) \\
&(1), (1\ 3)(2\ 4) && (1), (1\ 3), (2\ 4), (1\ 3)(2\ 4)\\ 
&(1), (1\ 4)(2\ 3) && (1), (1\ 4), (2\ 3), (1\ 4)(2\ 3)\\
&(1), (2\ 3)(1\ 4) && (1), (2\ 3), (1\ 4), (2\ 3)(1\ 4)\\
&(1), (2\ 4)(1\ 3) && (1), (2\ 4), (1\ 3), (2\ 4)(1\ 3)\\
&(1), (3\ 4)(1\ 2) && (1), (3\ 4), (1\ 2), (3\ 4)(1\ 2)\\
\end{align}
$$
I'm not sure what a systematic way to identify all of the subgroups of order 4 or 8 (or find their normalizers are).
