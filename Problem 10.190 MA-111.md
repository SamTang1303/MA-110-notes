---
aliases: 
tags:
  - batch/school/class/ma111
  - batch/math
type: Problem
---
# Problem 10.190 MA-111

> [!problem] Problem 10.190
> Suppose that $H$ is a subgroup of a finite group $G$, with $\left| G \right|=p^{m}n$ for some $m$, $n$, and prime $p$. Suppose also that $\left| H \right|=p^{i}$. Prove that if $i<m$, then $H$ is properly contained in its normalizer (i.e., $H \subsetneq N[H]$).

Suppose that $H$ is a subgroup of a finite group $G$, with $\left| G \right|=p^{m}n$ for some $m$, $n$, and prime $p$. [[Problem 10.189 MA-111|Problem 189]] implies that $[G:H]\equiv[N[H]:H]$. From Lagrange's Theorem, we know $[G:H]=\left| G \right|/\left| H \right|=p^{m-i}n$. Because $m-i$ is positive, $[G:H]$, and therefore $[N[H]:H]$ must be greater than one. This excludes the possibility that $N[H]=H$, implying $H \subsetneq N[H]$.
