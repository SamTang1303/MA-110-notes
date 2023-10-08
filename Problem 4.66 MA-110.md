---
aliases: 
tags:
  - batch/school/class/ma110
  - batch/math
type: Problem
---
# Problem 4.66 MA-110

> [!problem] Problem 4.66
> Show that any [[Definition 3.1.1 MA-110|homomorphism]] of groups $\phi:G\longrightarrow H$ where $\left| G \right|$ is prime must be either the trivial homomorphism or a one-to-one map.

Let $\phi:G\longrightarrow H$ be a homomorphism of groups where $G$ is prime. Suppose that $\phi$ is not a one-to-one map. Then, by [[Problem 3.52 MA-110|Problem 52]], $\left| \ker(\phi) \right|>1$. $\ker(\phi)$ is a subgroup of $G$ and must have an order that is a factor of $\left| G \right|$ by [[Problem 4.64 MA-110|Problem 64]]. $\left| G \right|$ is prime, so this is only possible if $\left| \ker(\phi) \right|=\left| G \right|$. Therefore, the [[Definition 3.4 MA-110|kernel]] must contain every element of $G$ and $\phi$ is the trivial homomorphism.

Thus, $\phi$ must be either trivial, or a one-to-one map.
