---
aliases: 
tags:
  - batch/school/class/ma111
  - batch/math
type: Problem
---
# Problem 13.260 MA-111

> [!problem] Problem 13.260
> Let $F$ be an extension of $\mathbb{Q}$ that does not contain $\omega=e^{2\pi i/n}$. Show that $\text{Gal}(F(\omega)/F)$ is abelian.

Let $F$ be an extension of $\mathbb{Q}$ that does not contain $\omega=e^{2\pi i/n}$. The automorphisms of $F(\omega)$ that fix $F$ will be entirely determined by where they send $\omega$. By Theorem 12.1, $\omega$ must map to another root of $x^{n}-1$, which are just other powers of $\omega$. Composing functions will multiply the degree that $\omega$ is mapped to, making $\text{Gal}(F(\omega)/F)\simeq U(n)$, making it an abelian group.
