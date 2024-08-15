---  
date created: Saturday, August 10th 2024, 2:53:57 pm  
date modified: Thursday, August 15th 2024, 9:46:18 am  
title: Tower of Subgroups  
url_encoded_title: Tower  
---  
# Tower  
A tower of [Subgroups](../Groups/Subgroup.md) $G$ is a [Group](../Groups/Group.md) that is defined as a sequence of nested [Subgroups](../Groups/Subgroup.md).  
It is generally of the form:  
$$G=G_n\subset G_{n-1}\subset\dots\subset G_1\subset G_0$$  
## Normal  
A tower is [Normal](../Groups/Normal.md) if each of the subgroups in the tower is [Normal](../Groups/Normal.md).  
  
## Abelian (Commutative)  
A tower is [Abelian (Commutative)](../Commutativity%2520(Abelian).md) if it is normal and if each [Factor%20Group%20(Modulo)](../Groups/Factor%2520Group%2520(Modulo).md) $G_i/G_{i+1}$ is [Abelian (Commutative)](../Commutativity%2520(Abelian).md).  
  
## Cyclic  
A tower is [Cyclic](../Groups/Cyclic.md) if it is [Normal](../Groups/Normal.md) and if each [Factor%20Group%20(Modulo)](../Groups/Factor%2520Group%2520(Modulo).md) $G_i/G_{i+1}$ is [Cyclic](../Groups/Cyclic.md).  
## Solvable  
A tower is solvable if:  
- It is [Abelian (Commutative)](../Commutativity%2520(Abelian).md)  
- Its last [Subgroups](../Groups/Subgroup.md) (eg. $G_n$) is [Trivial](../Groups/Subgroup.md#trivial).  
  
>[!info] Solvability of [Group](../Groups/Group.md), [Subgroups](../Groups/Subgroup.md) and [Factor%20Group%20(Modulo)](../Groups/Factor%2520Group%2520(Modulo).md)  
> With a [Group](../Groups/Group.md) $G$, [Normal](../Groups/Normal.md) [Subgroups](../Groups/Subgroup.md) $H$ and a [Factor%20Group%20(Modulo)](../Groups/Factor%2520Group%2520(Modulo).md) $G/H$:  
> $G$ is [Solvable](Tower.md#solvable) if and only if $H$ and $G/H$ are [Solvable](Tower.md#solvable)