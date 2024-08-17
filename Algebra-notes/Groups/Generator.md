---  
date created: Thursday, August 1st 2024, 7:37:06 pm  
date modified: Saturday, August 17th 2024, 3:18:35 pm  
title: Generator  
---  
# Generator  
With a [Group](./Group.md) $G$ and a [Subset](../Sets/Subset.md) of $G$ called $S$,  
The [Subset](../Sets/Subset.md) $S$ generates $G$ if all elements of $G$ can be expressed as a product of elements of $S$ and their inverses.  
The [Set](../Sets/Set.md) of these various products becomes a [Subgroup](./Subgroup.md) of $G$ itself (the empty product is the [Unit Element](../Unit_Element.md)).  
  
>[!info] $S$ generates $G$ if and only if the **smallest** [Subgroup](./Subgroup.md) of $G$ containing all the elements of $S$ is $G$ itself.  
  
In other words, an element $a$ in [Group](./Group.md) $G$ is a Generator if the map $f: \mathbb{Z} \rightarrow G$ such that $f(n)=a^n$ (or $f(n)=an$ for additive) is [Surjective](../Mapping/Surjective.md).  
  
Ways to write this property:  
- $S$ is a [Set](../Sets/Set.md) of generators for $G$.   
- $S$ generates $G$  
- Mathematically it is written as: $G=\langle S\rangle$  
  
  
  
