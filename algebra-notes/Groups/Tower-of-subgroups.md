---  
date created: Saturday, August 10th 2024, 2:53:57 pm  
date modified: Tuesday, August 13th 2024, 2:58:33 pm  
title: Tower of Subgroups  
---  
# Tower of Subgroups  
A tower of [Subgroups](./Subgroup.md) $G$ is a [Group](./Group.md) that is defined as a sequence of nested [Subgroups](./Subgroup.md).  
It is generally of the form:  
$$G=G_n\subset G_{n-1}\subset\dots\subset G_1\subset G_0$$  
  
## Normal  
A tower is [Normal](./Normal.md) if each of the subgroups in the tower is [Normal](./Normal.md).  
  
## Abelian (Commutative)  
A tower is [Abelian (Commutative)](../Commutativity-(Abelian).md) if it is normal and if each [Factor Group (Modulo)](./Factor-Group-(Modulo).md) $G_i/G_{i+1}$ is [Abelian (Commutative)](../Commutativity-(Abelian).md).  
## Solvable  
A tower is solvable if:  
- It is [Abelian (Commutative)](../Commutativity-(Abelian).md)  
- Its last [Subgroups](./Subgroup.md) (eg. $G_n$) is [Trivial](./Subgroup.md#trivial).  
  
## Refinement  
A refinement of a tower is a new tower where a finite number of subgroups are inserted into the existing tower. This 'refines' the tower by making it more detailed.