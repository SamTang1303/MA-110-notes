---
aliases: 
tags:
  - batch/school/class/ma110
  - batch/math
type: Problem
---
# Problem 5.72 MA-110

> [!problem] Problem 72
> Let $H$ be a subgroup of a group $G$ with property that $gH=Hg$ for all $g \in G$. Let $a,b \in G$. Prove that if $x \in aH$ and $y \in bH$, then $xy=(ab)H$.

Let $H$ be a subgroup of $G$ with property that $gH=Hg$ for all $g \in G$. Let $a,b \in G$ and $x \in aH$ and $y \in bH$. (Because of our initial assumption, this also implies $y \in Hb$) Then, for some $h_{1},h_{2} \in H$, $x=ah_{1}$ and $y=h_{2}b$. Thus, $xy=ah_{1}h_{2}b$. $H$ is a group, so $h_{1}h_{2} \in H$, implying $xy \in a(Hb)$. By assumption, 
$$
a(Hb)=a(bH)=(ab)H.
$$
Thus, $xy \in (ab)H$.
