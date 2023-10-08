---
aliases: 
tags:
  - batch/school/class/ma110
  - batch/math
type: Problem
---
# Problem 4.60 MA-110

> [!problem] Problem 4.60
> Prove that if $a \in H$, then $aH=H$. (This is the converse of the statement in [[Problem 4.58 MA-110|Problem 58]].)

Let $G$ be a group with subgroup $H$, and let $a \in H$. First, let $x \in H$. $a^{-1}x \in H$ because $H$ is a subgroup, and $a(a^{-1}x)=x$, so $x \in aH$. Thus, $H \subseteq aH$. Now, let $y \in aH$. This implies $ah =y$ for some $h \in H$. Because $ah$ is the product of two elements of subgroup $H$, it must be in $H$ as well. Therefore $y \in H$ and $aH \subseteq H$. Combining these two results yields $aH=H$.
