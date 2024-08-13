---  
date created: Friday, August 2nd 2024, 2:24:27 pm  
date modified: Tuesday, August 13th 2024, 2:58:33 pm  
title: Isomorphism  
---  
# Isomorphism  
With [Monoids](../Monoid.md) $G$ and $G'$,  
a [Homomorphism](./Homomorphism.md) $f: G \rightarrow G'$ is an isomorphism if there exists another [Homomorphism](./Homomorphism.md) $g: G' \rightarrow G$ such that:  
- $f \circ g$ is an identity mapping $G \rightarrow G$  
- $g \circ f$ is an identity mapping $G' \rightarrow G'$  
Naturally this can only be the case if both $f$ and $g$ are [Bijective](../../Mapping/Bijective.md).  
The existence of this isomorphism can be mathematically denoted by:  
$$G\approx G'$$