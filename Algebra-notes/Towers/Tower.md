---  
date created: Saturday, August 10th 2024, 2:53:57 pm  
date modified: Saturday, August 17th 2024, 3:18:35 pm  
title: Tower  
---  
# Tower  
A tower (aka. a tower of [Subgroups](../Groups/Subgroup.md)) $G$ is a [Group](../Groups/Group.md) that is defined as a sequence of nested [Subgroups](../Groups/Subgroup.md).  
It is generally of the form:  
$$G=G_n\subset G_{n-1}\subset\dots\subset G_1\subset G_0$$  
## Normal  
A tower is [Normal](../Groups/Normal.md) if each of the subgroups in the tower is [Normal](../Groups/Normal.md).  
  
## Abelian (Commutative)  
A tower is [Abelian (Commutative)](../Commutativity_28Abelian29.md) if it is [Normal](Tower.md#normal) and if each [Factor Group (Modulo)](../Groups/Factor_Group_28Modulo29.md) $G_i/G_{i+1}$ is [Abelian (Commutative)](../Commutativity_28Abelian29.md).  
  
## Cyclic  
A tower is [Cyclic](../Groups/Cyclic/Cyclic.md) if it is [Normal](Tower.md#normal) and if each [Factor Group (Modulo)](../Groups/Factor_Group_28Modulo29.md) $G_i/G_{i+1}$ is [Cyclic](../Groups/Cyclic/Cyclic.md).  
## Solvable  
A tower is solvable if:  
- It is [Abelian (Commutative)](../Commutativity_28Abelian29.md)  
- Its last [Subgroups](../Groups/Subgroup.md) (eg. $G_n$) is [Trivial](../Groups/Trivial.md).  
  
>[!info] Solvability of [Group](../Groups/Group.md), [Subgroups](../Groups/Subgroup.md) and [Factor Group (Modulo)](../Groups/Factor_Group_28Modulo29.md)  
> With a [Group](../Groups/Group.md) $G$, [Normal](../Groups/Normal.md) [Subgroups](../Groups/Subgroup.md) $H$ and a [Factor Group (Modulo)](../Groups/Factor_Group_28Modulo29.md) $G/H$:  
> $G$ is [Solvable](Tower.md#solvable) if and only if $H$ and $G/H$ are [Solvable](Tower.md#solvable)