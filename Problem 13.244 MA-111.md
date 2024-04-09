---
aliases: 
tags:
  - batch/school/class/ma111
  - batch/math
type: Problem
---
# Problem 13.244 MA-111

![[Problem 13.242 MA-111#^8b7e0f]]
![[Problem 13.242 MA-111#^5f5e7a]]
![[Problem 13.242 MA-111#^abf1dd]]

> [!problem] Problem 13.244
> Show that $\Phi$ is onto. Does your explanation use the hypotheses that $E$ and $K$ are splitting fields?

Let $\phi$ be an element of $\text{Gal}(E/F)$. Because $K$ is a splitting field of $f(x)$, Theorem 12.5 says that there exists an isomorphism extension of $\phi$, $\sigma: K \longrightarrow K$. Because $\sigma$ is an [[Definition 12.3 MA-11|extension]] of $\phi:E \longrightarrow E$, by definition $\Phi(\sigma)=\sigma|_{E}=\phi$. Because $\phi$ fixed $F$, $\sigma$ will as well.

Thus, $\sigma \in \text{Gal}(K/F)$ and $\Phi$ is onto. This explanation relies on $K$ being a splitting field.
