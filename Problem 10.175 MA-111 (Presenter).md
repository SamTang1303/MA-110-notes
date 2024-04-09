---
aliases: 
tags:
  - batch/school/class/ma111
  - batch/math
type: Problem
---
# Problem 10.175 MA-111 (Presenter)

> [!problem] Problem 10.175
> Use the group in [[Problem 10.174 MA-111|Problem 174]] to find groups $K,H,$ and $G$ respectively such that $K\trianglelefteq H \trianglelefteq G$, but $K\not\trianglelefteq G$. (This shows that the normality relation is not transitive.)

Consider the groups $G=D_{4}, H=V,$ and $K=\{ (1), (1\ 2)(3\ 4) \}$. Each successive group has half the order of the previous, so [[Problem 10.172 MA-111|Problem 172]] implies that $K \trianglelefteq H \trianglelefteq G$. But,
$$
(1\ 2\ 3\ 4)\big[(1\ 2)(3\ 4)\big](1\ 2\ 3\ 4)^{-1} = (2\ 3)(1\ 4) \notin  K.
$$
Thus, $K \not\trianglelefteq G$.
