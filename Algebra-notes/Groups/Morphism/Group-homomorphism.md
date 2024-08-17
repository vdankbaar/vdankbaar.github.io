---  
date created: Friday, August 2nd 2024, 2:12:25 pm  
date modified: Saturday, August 17th 2024, 3:18:35 pm  
title: Group-homomorphism  
---  
# Group-homomorphism  
Group-homomorphism works similar to [Monoid-homomorphism](../../Monoids/Morphisms/Homomorphism.md) except it uses [Groups](../Group.md) for $G$ and $G'$.  
Additionally:  
With Group-homomorphism $f: G\rightarrow G'$:  
- $f(x^{-1})=f(x)^{-1}$  
  
With Group-homomorphism $f: G \rightarrow G'$ and $g: G' \rightarrow G''$:  
* $f\circ g$ is also a Group-homomorphism   
  
With:  
- [Groups](../Group.md) $G$ and $G'$  
- [Set](../../Sets/Set.md) $S$ that [Generates](../Generator.md) $G$  
- A map $f: S \rightarrow G'$  
If there exists a Group-homomorphism $\bar{f}: G \rightarrow G'$ that when restricted to $S$ is equivalent to $f$ then there can only exist one.  
  
If the [Kernel](./Kernel.md) of a Group-homomorphism is [Trivial](../Trivial.md) then the Group-homomorphism is [Injective](../../Mapping/Injective.md).  
If the Group-homomorphism is also [Surjective](../../Mapping/Surjective.md) then the Group-homomorphism is [Bijective](../../Mapping/Bijective.md), making the Group-homomorphism a [Group-isomorphism](./Group-isomorphism.md).