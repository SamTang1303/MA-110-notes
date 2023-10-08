---
aliases: 
tags:
  - batch/school/class/ma110
  - batch/math
type: Problem
---
# Problem 2.33 MA-110

> [!problem] Problem 2.33
> Suppose $G$ and $H$ are groups, with $S$ a subgroup of $G$, and $T$ a subgroup of $H$. Prove or disprove as appropriate: $S\times T$ is a subgroup of $G\times H$.

Let $G$ and $H$ be groups with $S$ a subgroup of $G$ and $T$ a subgroup of $H$. We will prove $S\times T$ is a subgroup of $G\times H$ with operation defined component-wise.

Let $(e_{G},e_{H})$ be the identity element of $G\times H$. Consider an arbitrary $(g,h) \in G\times H$. By definition of an identity,
$$
(g,h)(e_{G},e_{H})  = (ge_{G}, he_{H}) = (g,h),
$$
implying $ge_{G}=g$ and $he_{H}=h$. We could argue similarly to show $e_{G}g=g$ and $e_{H}h=h$. Therefore, $e_{G}$ and $e_{H}$ must be the identities of $G$ and $H$ respectively. By the definition of a subgroup, $S$ must contain $e_{G}$ and $T$ must contain $e_{H}$. Therefore, $(e_{G},e_{H}) \in S\times T$ and the first criterion for $S\times T$ being a subgroup is satisfied.

Let $(s_{1},t_{1}), (s_{1},t_{2}) \in S\times T$. By definition, $s_{1},s_{2} \in S$ and $t_{1}, t_{2} \in T$. By definition of a subgroup $s_{1}s_{2} \in S$ and $t_{1}t_{2} \in T$. So, $(s_{1},t_{1})(s_{2},t_{2}) = (s_{1}s_{2},t_{1}t_{2}) \in S\times T$. Therefore, $S\times T$ is closed under the operation of $G\times T$.

Finally, let $(s,t) \in S\times T$. Thus, $s \in S$ and $t \in T$. Because $S$ and $T$ are both subgroups, $s ^{-1} \in S$, $t^{-1} \in T$, and $(s ^{-1}, t^{-1}) \in S\times T$.
$$
(s,t)(s ^{-1}, t^{-1}) = (s s ^{-1}, t t^{-1}) = (e_{G}, e_{H}). \text{ The reverse order of mulitplication is shown similarly.}
$$
We have already shown this to be the identity of $S\times T$ and in $S\times T$, so this is the last piece needed to show $S\times T$ is a subgroup of $G\times H$.
