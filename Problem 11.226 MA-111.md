---
aliases: 
tags:
  - batch/school/class/ma111
  - batch/math
type: Problem
---
# Problem 11.226 MA-111

> [!problem] Problem 11.226
> How many different automorphisms of $\mathbb{Q}(\sqrt{ 2 },\sqrt{ 3 },\sqrt{ 5 })$ are there? List them.

For the same reason as in [[Problem 11.225 MA-111|Problem 225]], the maps given below are defined entirely by where they map one element, and they are automorphisms. All elements not listed are fixed under the automorphism.
$$
\begin{align}
\phi_{1}(\sqrt{ 2 }) &= -\sqrt{ 2 } \\
\phi_{2}(\sqrt{ 3 }) &= -\sqrt{ 3 } \\
\phi_{3}(\sqrt{ 5 }) &= -\sqrt{ 5 }.
\end{align}
$$
There are ${3 \choose 2}=3$ different ways to compose two of the given automorphisms to yield a new unique automorphism. Finally, we can compose all three functions. This makes for a total of $3+3+1=7$ different possible automorphisms. I don't know how to prove these are all possible automorphisms on $\mathbb{Q}(\sqrt{ 2 },\sqrt{ 3 },\sqrt{ 5 })$.
