---  
date created: Friday, August 2nd 2024, 1:59:25 pm  
date modified: Thursday, August 15th 2024, 1:15:09 pm  
title: Homomorphism  
---  
# Homomorphism  
With [Monoids](../Monoid.md) $G$ and $G'$, a homomorphism (aka. monoid-homomorphism) is a mapping $f: G\rightarrow G'$ such that:  
$$f(xy) = f(x)f(y)$$  
Simply put, composing elements before mapping is equivalent to mapping first and then composing.  
  
> [!tldr] The [Unit Element](../../Unit20Element.md) in $G$ maps to the [Unit Element](../../Unit20Element.md) in $G'$   
> Given the [Unit Element](../../Unit20Element.md) $e$ from $G$ and the [Unit Element](../../Unit20Element.md) $e'$ from $G'$: $$f(e)=e'$$  
> Proof:  
> 1. Apply property of [Unit Element](../../Unit20Element.md): $f(e)=f(ee)$  
> 2. Apply property of Homomorphism: $f(ee)=f(e)f(e)$  
> 3. Property of [Unit Element](../../Unit20Element.md): $f(e) = f(e)e'$  
> 4. Cancel out terms: $f(e)f(e)=f(e)e'$ becomes $f(e)=e'$  
  
> [!info] A sequence of homomorphisms  
> A sequence of homomorphisms is written as: $G' \overset{f}{\rightarrow} G \overset{g}{\rightarrow} G''$.  
> ## Exact  
> A sequence is exact if $Im(f) = Ker(g)$