---
aliases: 
tags:
  - batch/school/class/ma111
  - batch/math
type: Problem
---
# Problem 10.180 MA-111

> [!problem] Problem 10.180
> For the symmetry group of the regular tetrahedron ([[Problem 10.176 MA-111|Problem 176]]), compute the orbit and stabilizer of the vertex labeled 1. Check that the [[Theorem 10.10 MA-111|Orbit-Stabilizer Theorem]] holds.

We can model the symmetries of a regular tetrahedron as $S_{4}$ acting on the set of vertices $\{ 1,2,3,4\}$. $S_{4}$ is the set of all bijections from $\{ 1,2,3,4 \}\times \{ 1,2,3,4 \}$, so $S_{4}1=\{ 1,2,3,4 \}$. $\text{stab}(1)=\{ (1), (2\ 3\ 4), (2\ 4\  3), (2\ 4), (2\ 3), (3\ 4) \}$. Thus $\left| \text{stab}(x) \right|=6$ and $\left| S_{4} \right|$, so $[S_{4}:\text{stab}(x)]=4=S_{4}1$. Therefore the Orbit-Stabilizer theorem holds.
