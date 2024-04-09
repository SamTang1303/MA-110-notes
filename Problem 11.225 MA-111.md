---
aliases: 
tags:
  - batch/school/class/ma111
  - batch/math
type: Problem
---
# Problem 11.225 MA-111

> [!problem] Problem 11.225
> An isomorphism from a field $F$ to itself is called an **automorphism** of $F$. Find three different automorphisms of $\mathbb{Q}(\sqrt{ 2 },\sqrt{ 3 })$, besides the identity. (Consider that $\mathbb{Q}(\sqrt{ 2 },\sqrt{ 3 })=(\mathbb{Q}(\sqrt{ 2 }))(\sqrt{ 3 })=(\mathbb{Q}(\sqrt{ 3 }))(\sqrt{ 2 })$, and apply Theorem 12.1.)

Consider the field $\mathbb{Q}(\sqrt{ 2 },\sqrt{ 3 })=(\mathbb{Q}(\sqrt{ 2 }))(\sqrt{ 3 })=(\mathbb{Q}(\sqrt{ 3 }))(\sqrt{ 2 })$. Both $\sqrt{ 2 }$ and $-\sqrt{ 2 }$ are roots of the irreducible polynomial $x^{2}-2 \in \mathbb{Q}(\sqrt{ 3 })[x]$. Thus, Theorem 12.1 says the map $\phi:\mathbb{Q}(\sqrt{ 3 },\sqrt{ 2 })\longrightarrow \mathbb{Q}(\sqrt{ 3 },-\sqrt{ 2 })$ defined by $\phi(\sqrt{ 2 })=-\sqrt{ 2 }$ is an isomorphism. Further, because $-\sqrt{ 2 } \in \mathbb{Q}(\sqrt{ 3 },\sqrt{ 2 })$, $\mathbb{Q}(\sqrt{ 3 },\sqrt{ 2 })=\mathbb{Q}(\sqrt{ 3 },-\sqrt{ 2 })$, meaning that $\phi$ is an automorphism. We can argue similarly to show that the map $\phi:\mathbb{Q}(\sqrt{ 2 },\sqrt{ 3 })\longrightarrow\mathbb{Q}(\sqrt{ 2 },-\sqrt{ 3 })$ defined by $\phi(\sqrt{ 3 })=-\sqrt{ 3 }$ is an automorphism as well. Because the property of being an automorphism is preserved under function composition, composing the two automorphisms already found will yield our third automorphism.
