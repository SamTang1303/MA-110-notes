---
aliases: 
tags:
  - batch/school/class/ma111
  - batch/math
type: Problem
---
# Problem 13.261 MA-111

> [!problem] Problem 13.261
> Let $F$ be an extension of $\mathbb{Q}$ that does not contain $\omega=e^{2\pi i/n}$. Let $K$ be the splitting field of $x^{n}-a$ over $F$. Show that $\text{Gal}(K/F)/\text{Gal}(K/F(\omega))$ is abelian. Give an example to show that $\text{Gal}(K/F)$ need not be abelian.

Let $F$ be an extension of $\mathbb{Q}$ that does not contain $\omega=e^{2\pi i/n}$. Let $K$ be the splitting field of $x^{a}-a$ over $F$. As in [[Problem 13.259 MA-111|Problem 259]], $\omega \in K$, so $F\subseteq F(\omega)\subseteq K$. Note that we are given $K$ is a splitting field of $x^{n}-a$, and $F(\omega)$ is the splitting field of $x^{n}-1$, so [[Problem 13.245 MA-111|Problem 245]] says that
$$
\text{Gal}(K/F)/\text{Gal}(K/F(\omega)) \simeq \text{Gal}(F(\omega )/F).
$$
[[Problem 13.260 MA-111|Problem 260]] says that $\text{Gal}(F(\omega)/F)$ is abelian, thus $\text{Gal}(K/F)/\text{Gal}(K/F(\omega))$ must be as well.

Let $K$ be the splitting field of $x^{3}-2$. In [[Problem 13.248 MA-11|Problem 248]] we found that $\text{Gal}(K/\mathbb{Q})\simeq S_{6}$, which is a non-abelian group. 
