---
aliases: []
tags:
  - batch/school/class/ma110
  - batch/math
type: Problem
---
# Problem 1.20 MA-110

> [!problem] Problem 1.20
> Prove or disprove, as appropriate: If $G$ is a group, with $a$ and $b$ in $G$, then $(ab)^{-1}=a^{-1}b^{-1}$.

We will prove by counterexample. Once again, let $G$ be the group of symmetries of an equilateral triangle, and let $a=\rho_{1}$ and $b=\mu_{1}$.
$$
(ab)^{-1}= (\rho_{1}\mu_{1})^{-1}= (\mu_{2})^{-1}=\mu_{2}.
$$
Yet,
$$
a^{-1}b^{-1} = \rho_{1}^{-1}\mu_{1}^{-1} = \rho_{2}\mu_{1} = \mu_{3}.
$$
Because these two are not equal, the theorem does not hold in general.
