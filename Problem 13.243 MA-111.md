---
aliases: 
tags:
  - batch/school/class/ma111
  - batch/math
type: Problem
---
# Problem 13.243 MA-111

![[Problem 13.242 MA-111#^8b7e0f]]
![[Problem 13.242 MA-111#^5f5e7a]]
![[Problem 13.242 MA-111#^abf1dd]]

> [!problem] Problem 13.243
> Check that $\Phi$ is a homomorphism of groups, and compute its kernel. Does your explanation use the hypothesis that $E$ and $K$ are splitting fields?

Let $\sigma, \phi \in \text{Gal}(K/F)$.
$$
\begin{align}
\Phi(\sigma)\circ \Phi(\phi ) &=  \sigma|_{E} \circ \phi|_{E} \\
&= \sigma\circ \phi |_{E} \\
&= \Phi(\sigma \circ \phi ).
\end{align}
$$
An element $\sigma \in \text{Gal}(F/K)$ maps to the identity function under $\Phi$ if and only if it fixes $E$. i.e., if it is an element of $\text{Gal}(K/E)$. This explanation does not rely on $E$ or $K$ being splitting fields.
