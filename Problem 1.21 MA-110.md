---
aliases:
  - shoes socks principle
tags:
  - batch/school/class/ma110
  - batch/math
type: Problem
---
# Problem 1.21 MA-110

> [!problem] Problem 1.21
> Prove or disprove, as appropriate: If $G$ is a group, with $a$ and $b$ in $G$, then $(ab)^{-1}=b^{-1}a^{-1}$.

*Proof.* Let $G$ be a group with $a,b \in G$ and an identity element $e$.
$$
\begin{align}
(ab)^{-1} (ab) &= e && \text{By definition}\\
(ab)^{-1}(ab)(b^{-1}a^{-1}) &= e(b^{-1}a^{-1})\\
(ab)^{-1}a(bb^{-1})a^{-1} &= b^{-1}a^{-1}\\
(ab)^{-1}(aa^{-1}) &= b^{-1}a^{-1}\\
(ab)^{-1} &= b^{-1}a^{-1}.
\end{align}
$$
