---
aliases: 
tags:
  - batch/school/class/ma111
  - batch/math
type: Problem
---
# Problem 12.228 MA-111

> [!problem] Problem 12.228
> Compute $\text{Gal}(\mathbb{Q}(\sqrt{ 2 },\sqrt{ 3 })/\mathbb{Q}(\sqrt{ 2 }))$ and $\text{Gal}(\mathbb{Q}(\sqrt{ 2 },\sqrt{ 3 })/\mathbb{Q})$. What familiar groups are these groups isomorphic to?

Consider the group $\text{Gal}(\mathbb{Q}(\sqrt{ 2 },\sqrt{ 3 })/\mathbb{Q}(\sqrt{ 2 }))$. By Theorem 12.1 we know that any automorphism of $\mathbb{Q}(\sqrt{ 2 },\sqrt{ 3 })=(\mathbb{Q}(\sqrt{ 2 }))(\sqrt{ 3 })$ that fixes $\mathbb{Q}(\sqrt{ 2 })$ must map $\sqrt{ 3 }$ to a root of the polynomial $x^{2}-3$. This leaves us with only two functions, defined by the maps given below.
$$
\begin{align}
\phi_{1}(\sqrt{ 3 }) &= \sqrt{ 3 } \\
\phi_{2}(\sqrt{ 3 }) &= -\sqrt{ 3 }.
\end{align}
$$
So, $\text{Gal}(\mathbb{Q}(\sqrt{ 2 },\sqrt{ 3 })/\mathbb{Q}(\sqrt{ 2 }))=\{ \phi_{1},\phi_{2} \}$, where $\phi_{1}$ is the identity function. This must be isomorphic to $\mathbb{Z}_{2}$ because it is a group of order 2. 

In [[Problem 11.225 MA-111|Problem 225]] we showed that the set of all automorphisms on $\mathbb{Q}(\sqrt{ 2 },\sqrt{ 3 })$ has three elements. Because every automorphism fixes $\mathbb{Q}$ by [[Problem 11.222 MA-111|Problem 222]], this set is equivalent to $\text{Gal}(\mathbb{Q}(\sqrt{ 2 },\sqrt{ 3 })/\mathbb{Q})$. Thus $\left|\text{Gal}(\mathbb{Q}(\sqrt{ 2 },\sqrt{ 3 })/\mathbb{Q})  \right|=3$, implying it is isomorphic to $\mathbb{Z}_{3}$.
