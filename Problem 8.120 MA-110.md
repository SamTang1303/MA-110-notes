---
aliases: 
tags:
  - batch/school/class/ma110
  - batch/math
type: Problem
---
# Problem 8.120 MA-110

> [!problem] Problem 8.120
> Prove that a field has no nontrivial proper ideals. Use this fact to explain why any nontrivial homomorphism $\phi:F \longrightarrow E$ of fields must be one-to-one.

Let $F$ be a non-trivial field with ideal $I$. Let $x \in I$ with $x\neq0$. Because $F$ is a field, $x^{-1} \in F$, so $xx^{-1}=1 \in F$. [[Problem 7.107 MA-110|Problem 107]] implies that $I=R$ (i.e. not a proper ideal). Thus ideals of fields must be either trivial or the entire field.

Let $\phi : F\longrightarrow R$ be a non-trivial homomorphism of fields. The kernel of $\phi$  must be an ideal of $F$ by [[Problem 6.101 MA-110|Problem 101]]. From our work above, then it must either be all of $F$ (i.e. $\phi$ is the trivial homomorphism), or $\{ 0 \}$. In the case where $\ker(\phi)=\{ 0 \}$, [[Problem 3.52 MA-110|Problem 52]] tells us that $\phi$ is one-to-one. Thus, any non-trivial homomorphism of fields must be one-to-one.