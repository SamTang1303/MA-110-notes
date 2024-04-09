---
aliases: 
tags:
  - batch/school/class/ma111
  - batch/math
type: Problem
---
# Problem 13.266 MA-111

> [!problem] Problem 13.266
> There are lots of ways to prove that $A_{5}$ is a simple group (i.e., that it has no proper, nontrivial subgroups). Search the internet for a proof that $A_{5}$ is simple, and give a "bullet point" summary of the argument in your own words

- A **conjugacy class** is the set of all elements who are conjugates of each other in a given group.
- The table of conjugacy classes is given as follows:

| Representative from Conjugacy Class | $(1)$ | $(1\ 2\ 3\ 4\ 5)$ | $(1\ 3\ 4\ 5\ 2)$ | $(1\ 2)(3\ 4)$ | $(1\ 2\ 3)$ |
| ----------------------------------- | ----- | ----------------- | ----------------- | -------------- | ----------- |
| Order of Conjugacy Class            | 1     | 12                | 12                | 15             | 20          |

- Normal subgroups are invariant under conjugation, so if a normal subgroup of $A_{5}$ contains one element of a conjugacy class, it must contain all the others.
- Thus, any normal subgroup of $A_{5}$ will be the union of conjugacy classes.
- The only possible divisors of $\left| A_{5} \right|=60$ that are summable by $1$ and elements any combination of $1,12,12,15$, and $20$ are $1$ and $60$. Thus, $A_{5}$ is a simple group.
