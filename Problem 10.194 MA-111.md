---
aliases: 
tags:
  - batch/school/class/ma111
  - batch/math
type: Problem
---
# Problem 10.194 MA-111

> [!problem] Problem 10.194
> Prove part 3b of [[Theorem 10.11 MA-111|Theorem 10.11]] (that the number of Sylow $p$-subgroups of $G$ divides $\left| G \right|$) as follows: By Part 2, $G$ acts on the set $X$ of Sylow subgroups by conjugation: $\phi_{g}(H)=gHg^{-1}$. Compute the number of orbits, and apply the [[Theorem 10.10 MA-111|Orbit-Stabilizer Theorem]].

By Part 2, $G$ acts on the set $X$ of Sylow $p$-subgroups by conjugation: $\phi_{g}(H)=gHg^{-1}$. Since any two Sylow $p$-subgroups are conjugations of each other, the orbit of each element will be the number of Sylow $p$-subgroups, $\left| X \right|$. Applying the Orbit-Stabilizer theorem yields
$$
\left| X \right| \cdot  \text{stab}(x) = \left| G \right| .
$$
Thus, the number of Sylow $p$-subgroups is a divisor of $G$. 
