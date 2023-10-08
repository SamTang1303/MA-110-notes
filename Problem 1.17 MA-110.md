---
aliases: 
tags:
  - batch/school/class/ma110
  - batch/math
type: Problem
---
# Problem 1.17 MA-110

> [!problem] Problem 1.17
> Suppose $G$ is a group, with $a,b,$ and $x$ in $G$. If $x=a^{-1}b$, can we conclude that $xa=b$? Either prove this conclusion true, or provide a counterexample.

We will disprove with a counterexample, using the symmetries of an equilateral triangle as our group. Let $a=\mu_{1}$ (implying $a^{-1}=\mu_{1}$as well) and $b=\mu_{3}$. Then, 
$$
x=a^{-1}b= \mu_{1} * \mu_{3} = \rho_{1}
$$
But,
$$
xa=\rho_{1} * \mu_{1} = \mu_{2} \neq b
$$
Therefore, the theorem must be false.
