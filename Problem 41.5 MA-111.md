---
aliases: 
tags:
  - batch/school/class/ma111
  - batch/math
type: Problem
---
# Problem 41.5 MA-111

> [!problem] Problem 41.5
> Describe $C_{i}(X)$, $Z_{i}(X)$, $B_{i}(X)$, and $H_{i}(X)$ for the space $X$ consisting of the 1-simplex $P_{1}P_{2}$.

$$
\begin{align}
C_{0}(X) &= \text{span}_{\mathbb{Z}}(\{ P_{1},P_{2} \})\simeq \mathbb{Z}^{2} \\
Z_{0}(X) &= C_{0}(X) \simeq \mathbb{Z}^{2}\\
B_{0}(X) &= \text{span}_{\mathbb{Z}}(P_{1}-P_{2}) \simeq \mathbb{Z}\\
H_{0}(X)&= C_{0}(X)/B_{0}(X) \simeq \mathbb{Z}\\
C_{1}(X) &= \text{span}_{\mathbb{Z}}(\{ P_{1}P_{2} \})\simeq \mathbb{Z} \\
Z_{1}(X) &= \text{span}_{\mathbb{Z}}(0)=0\\
B_{1}(X) &= \text{span}_{\mathbb{Z}}(0) =0\\
H_{1}(X)&= C_{0}(X)/B_{0}(X) =0\\
\end{align}
$$
For higher dimensions all spaces will be zero, because there are no n-simplexes for $n>1$.
