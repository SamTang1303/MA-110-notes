---
aliases: 
tags:
  - batch/school/class/ma111
  - batch/math
type: Problem
---
# Problem 12.229 MA-111

> [!problem] Problem 12.229
> Assign convenient labels to the elements of $\text{Gal}(\mathbb{Q}(\sqrt{ 2 },\sqrt{ 3 },\sqrt{ 5 })/\mathbb{Q})$ and make the group table.

As observed in class, automorphisms on $\mathbb{Q}(\sqrt{ 2 },\sqrt{ 3 },\sqrt{ 5 })$ are defined by how they permute the roots of the polynomials $x^{2}-2, x^{2}-3,x^{2}-5$. Assign the following symbols to each of the roots of these polynomials

| Root | Symbol |
| ---- | ---- |
| $\sqrt{ 2 }$ | 1 |
| $-\sqrt{ 2 }$ | 2 |
| $\sqrt{ 3 }$ | 3 |
| $-\sqrt{ 3 }$ | 4 |
| $\sqrt{ 5 }$ | 5 |
| $-\sqrt{ 5 }$ | 6 |
We can now think of automorphism permutation elements of $S_{6}$. For example, the automorphism defined by mapping $\sqrt{ 2 }\longmapsto-\sqrt{ 2 }$ and $\sqrt{ 5 }\longmapsto-\sqrt{ 5 }$ would be assigned $(1\ 2)(5\ 6)$. Note all roots of an irreducible polynomial can only map to other roots of that same polynomial. This yields the following multiplication table

<div class="page-break" style="page-break-after: always;"></div> 

|  | $(1)$ | $(1\ 2)$ | $(3\ 4)$ | $(5\ 6)$ | $(1\ 2)(3\ 4)$ | $(1\ 2)(5\ 6)$ | $(3\ 4)(5\ 6)$ | $(1\ 2)(3\ 4)(5\ 6)$ |
| ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- |
| $(1)$ | $(1)$ | $(1\ 2)$ | $(3\ 4)$ | $(5\ 6)$ | $(1\ 2)(3\ 4)$ |  |  |  |
| $(1\ 2)$ | $(1\ 2)$ | $(1)$ | $(1\ 2)(3\ 4)$ | $(1\ 2)(5\ 6)$ | $(3\ 4)$ |  |  |  |
| $(3\ 4)$ | $(3\ 4)$ | $(1\ 2)(3\ 4)$ | $(1)$ | $(3\ 4)(5\ 6)$ | $(1\ 2)$ |  |  |  |
| $(5\ 6)$ | $(5\ 6)$ | $(1\ 2)(5\ 6)$ | $(3\ 4)(5\ 6)$ | $(1)$ | $(1\ 2)(3\ 4)(5\ 6)$ |  |  |  |
| $(1\ 2)(3\ 4)$ | $(1\ 2)(3\ 4)$ | $(3\ 4)$ | $(1\ 2)$ | $(1\ 2)(3\ 4)(5\ 6)$ | $(1)$ |  |  |  |
| $(1\ 2)(5\ 6)$ | $(1\ 2)(5\ 6)$ | $(5\ 6)$ | $(1\ 2)(3\ 4)(5\ 6)$ | $(1\ 2)$ | $(3\ 4)(5\ 6)$ |  |  |  |
| $(3\ 4)(5\ 6)$ | $(3\ 4)(5\ 6)$ | $(1\ 2)(3\ 4)(5\ 6)$ | $(5\ 6)$ | $(3\ 4)$ | $(1\ 2)(5\ 6)$ |  |  |  |
| $(1\ 2)(3\ 4)(5\ 6)$ | $(1\ 2)(3\ 4)(5\ 6)$ | $(3\ 4)(5\ 6)$ | $(1\ 2)(5\ 6)$ | $(1\ 2)(3\ 4)$ | $(5\ 6)$ |  |  |  |
