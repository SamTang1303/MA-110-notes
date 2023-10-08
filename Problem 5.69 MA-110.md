---
aliases: 
tags:
  - batch/school/class/ma110
  - batch/math
type: Problem
---
# Problem 5.69 MA-110

> [!problem] Problem 5.69
> The group $A_{4}$ is a subgroup of $S_{4}$ with the following multiplication table.
> ![[A4_multiplication_table.jpg]]
> 1. The set $V=\{ (1), (1\,2)(3\,4), (1\,3)(2\,4), (1\,4)(2\,3)\}$ is a subgroup of $A_{4}$. Explain how this fact can be easily verified using the table above
> 2. Write out the cosets of $V$ in $A_{4}$. (How big are they? How many of them are there?)
> 3. Print out the above table, or make a screenshot and edit it in a drawing program. Assign a different color to each [[Definition 4.1 and 5.1 MA-110|coset]], and color each element in the table according to which [[Definition 4.1 and 5.1 MA-110|coset]] it belongs to. What do you notice?
> 4. Name the cosets $X,Y$, and $Z$. Is there an obvious multiplication that makes the sets $\{ X,Y,Z \}$ into a group? Draw a multiplication table.
> 5. According to the "obvious" multiplication, if $\alpha V$ and $\beta V$ are cosets, what [[Definition 4.1 and 5.1 MA-110|coset]] is their product $(\alpha V)(\beta V)$?

1. We can easily verify the statement in 1. by looking at the top right 4x4 section which corresponds to $V$. Because all of the cells in this area are in $V$, it is closed under multiplication. Because $V$ contains $(1)$, it has the identity. Because every row and column in this section have a $(1)$ in them, every element must have an inverse. This verifies all of the criteria for a subgroup.
2. $V=\{ (1), (1\ 2)(3\ 4), (1\ 3)(2\ 4), (1\ 4)(2\ 3)\}$, $(1\ 2\ 3)V=\{ (1\ 2\ 3), (2\ 4\ 3), (1\ 4\ 2), (1\ 3\ 4) \}, (1\ 2\ 4)V=\{ (1\ 2 \ 4), (2\ 3\ 4),(1\ 4\ 3), (1\ 3\ 2) \}$.
3. ![[colored_group_table.jpg]]The colored elements seem to form a new multiplication table. (i.e. yellow times blue equals green.)
4. Define $X=V, Y=(1\ 2\ 3)V$, and $Z=(1\ 2\ 4)V$.

|     | $X$ | $Y$ | $Z$ |
| --- | --- | --- | --- |
| $X$ | $X$ | $Y$ | $Z$ |
| $Y$ | $Y$ | $Z$ | $X$ |
| $Z$ | $Z$ | $X$ | $Y$ |

5. According to our "obvious" multiplication, if $\alpha V$ and $\beta V$ are cosets, their product is equal to $(\alpha \beta)V$.
