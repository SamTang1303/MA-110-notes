---
aliases: 
tags:
  - batch/school/class/ma111
  - batch/math
type: Problem
---
# Problem 13.267 MA-111

> [!problem] Problem 13.267
> By [[Problem 10.172 MA-111|Problem 172]], we know that $A_{5}\lhd S_{5}$. Suppose that $H$ is any other proper, nontrivial, normal subgroup of $S_{5}$. Use Lemma 10.13 to show that $\left| H \right|=2$. Then show that no such $H$ can exist. Conclude that $S_{5}$ is not solvable.

Given that $A_{5}$ is a normal subgroup of $S_{5}$, let $H$ be any other proper, nontrivial, normal subgroup of $S_{5}$. Both $H$ and $A_{5}$ are normal in $S_{5}$, so $A_{5}\cap H$ must be as well. Thus $A_{5}\cap H \lhd A_{5}$ as well. Because $A_{5}$ has no nontrivial proper normal subgroups, $A_{5}\cap H=\{ e \}$. Thus, Lemma 10.13 says that $A_{5}H$ is a subgroup of $A_{5}$. It must be equal to $A_{5}$, because there are no subgroups between $A_{5}$ and $S_{5}$. Furthermore, it implies that
$$
120=\left| S_{5} \right|=\left| A_{5} \right| \left| H \right| =60 \cdot \left| H \right| .
$$
Thus, $H$ is of order 2. But, any normal subgroup must contain all conjugates. Therefore, any normal subgroup with a 2-cycle will have many more than two elements. Therefore, $S_{5}$ has no normal subgroups other than $A_{5}$, which itself has no normal subgroups, and therefore is not solvable.
