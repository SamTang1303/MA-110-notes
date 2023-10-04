---
aliases: 
tags:
  - batch/math
  - batch/school/class/ma110
---
Sam Tang
Dr. Hunter
Abstract Algebra
2023-10-01
# Pre-Work Problems 69 Through 72 MA-110

> [!problem] Problem 5.69
> The group $A_{4}$ is a subgroup of $S_{4}$ with the following multiplication table.
> ![[A4_multiplication_table.jpg]]
> 1. The set $V=\{ (1), (1\,2)(3\,4), (1\,3)(2\,4), (1\,4)(2\,3)\}$ is a subgroup of $A_{4}$. Explain how this fact can be easily verified using the table above
> 2. Write out the cosets of $V$ in $A_{4}$. (How big are they? How many of them are there?)
> 3. Print out the above table, or make a screenshot and edit it in a drawing program. Assign a different color to each coset, and color each element in the table according to which coset it belongs to. What do you notice?
> 4. Name the cosets $X,Y$, and $Z$. Is there an obvious multiplication that makes the sets $\{ X,Y,Z \}$ into a group? Draw a multiplication table.
> 5. According to the "obvious" multiplication, if $\alpha V$ and $\beta V$ are cosets, what coset is their product $(\alpha V)(\beta V)$?

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

> [!problem] Problem 5.70
> Show, by giving an example group $G$, a subgroup $H$, and an element of $a \in G$, that $Ha$ can be different from $aH$. Is the statement, "If $x \in aH$ and $y \in bH$, then $xy \in (ab)H$" true for all $a,b \in G$ in your example?

Let $G=D_{3}$, and consider the subgroup $H=\{ (1), (2\,3) \}$. 
$$
(1\,2\,3)H=\{ (1\,2\,3),(1\,2) \} \neq \{ (1\,2\,3),(1\,3) \} =H(1\,2\,3).
$$
Therefore, in general, left cosets are not equal to right cosets.

In this example, if we choose $a=(1\ 2\ 3)$,  $b = (2\ 3)$, $x=(1)$, and $y =(2\ 3)$,
then $xy=(2\ 3)\notin (ab)H=(1\ 2)H = \{ (1\ 2), (1\ 2\ 3) \}$. The statement given does not hold.

> [!problem] Problem 5.71
> Let $\phi:G\longrightarrow H$ be a homomorphism of groups, and let $K$ be the kernel of $\phi$. Prove that $aK=Ka$ for any $a \in G$.

^efc336

Let $G\longrightarrow H$ be a homomorphism of groups, $a \in G$, and let $K$ be the kernel of $\phi$. We proved [[Pre-Work Problems 64 Through 68 MA-110#^6bf01f|Problem 68]] for left cosets, but an identical proof would clearly hold for right cosets. Therefore, $aK=\{ x \in G: \phi(x)=\phi(a) \}=Ka$.

> [!problem] Problem 72
> Let $H$ be a subgroup of a group $G$ with property that $gH=Hg$ for all $g \in G$. Let $a,b \in G$. Prove that if $x \in aH$ and $y \in bH$, then $xy=(ab)H$.

^fc2739

Let $H$ be a subgroup of $G$ with property that $gH=Hg$ for all $g \in G$. Let $a,b \in G$ and $x \in aH$ and $y \in bH$. (Because of our initial assumption, this also implies $y \in Hb$) Then, for some $h_{1},h_{2} \in H$, $x=ah_{1}$ and $y=h_{2}b$. Thus, $xy=ah_{1}h_{2}b$. $H$ is a group, so $h_{1}h_{2} \in H$, implying $xy \in a(Hb)$. By assumption, 
$$
a(Hb)=a(bH)=(ab)H.
$$
Thus, $xy \in (ab)H$.
