---
aliases: 
tags:
  - batch/school/class/ma111
  - batch/math
type: Problem
---
# Problem 11.221 MA-111

> [!problem] Problem 11.221
> Recall that a map of vector spaces is determined by where it maps a basis. Furthermore, a map of vector spaces is an isomorphism of vector spaces if it maps a basis to a basis. For example, using the notation of [[Problem 11.220 MA-111|Problem 220]], the vector space map $\psi:\mathbb{Q}(\alpha) \longrightarrow\mathbb{Q}(\beta)$ defined by $\psi(1)=1$, $\psi(\alpha)=\beta^{2}$, and $\psi(\alpha^{2})=\beta$ is an isomorphism of vector spaces. Show that $\psi$ is *not* an isomorphism of fields. (Hint: $\psi$ respects addition. What doesn't it respect?)

Using the notation of [[Problem 11.220 MA-111|Problem 220]], consider the vector space map $\psi:\mathbb{Q}(\alpha) \longrightarrow\mathbb{Q}(\beta)$ defined by $\psi(1)=1$, $\psi(\alpha)=\beta^{2}$, and $\psi(\alpha^{2})=\beta$.
$$
\begin{align}
\psi (\alpha^{2}) &= \beta  \\
\psi (\alpha)\psi(\alpha) &= \beta^{2} \cdot \beta^{2}.
\end{align}
$$
If $\psi$ were an isomorphism of fields then these two quantities would be equal. This is impossible because that would say $\beta=\beta^{4}\iff \beta^{3}=1$. We know $\beta^{3}$ to be $2$ be construction. Thus, $\psi$, while being an isomorphism of vector spaces, is not an isomorphism of fields.
