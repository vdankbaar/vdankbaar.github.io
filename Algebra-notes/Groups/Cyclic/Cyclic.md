---  
date created: Friday, August 2nd 2024, 1:31:32 pm  
date modified: Saturday, August 17th 2024, 3:18:35 pm  
title: Cyclic  
---  
# Cyclic  
A [Group](../Group.md) $G$ is Cyclic if there exists an element $a$ in $G$ called the cyclic [Generator](../Generator.md) such that every element of $G$ is of the form:  
- $a^n$ with multiplication as the [Law of composition](../../Law_of_composition.md)  
- $an$ with addition as the [Law of composition](../../Law_of_composition.md)  
  
In other words, $G$ is cyclic if the map $f: \mathbb{Z} \rightarrow G$ such that $f(n)=a^n$ (or $f(n)=an$ for additive) is [Surjective](../../Mapping/Surjective.md).  
  
Another way to describe this property is:  
With a [Group](../Group.md) $G$, [Subgroup](../Subgroup.md) $S$ and element $a$ in $S$,  
$S$ consists of elements of the form $a^n$ ($n\in \mathbb{Z})$.  
$a$ is a generator if the [Map](../../Mapping/Map.md) $f: G\rightarrow S$ is [Surjective](../../Mapping/Surjective.md).  
  
> [!info] With $G$ a finite group of [Order](../Order.md) $n>1$ and $a$ an element of $G$ that is not the [Unit Element](../../Unit_Element.md) $e$:  
> 1. The [Period](./Period.md) of $a$ divides $n$.  
> 2. If the [Order](../Order.md) of $G$ is prime $p$, then $G$ is [Cyclic](Cyclic.md) and the period of all [Generators](../Generator.md) are equal to $p$.  
  
> [!info] With $G$ a [Cyclic](Cyclic.md) [Group](../Group.md),  
> 1. Every [Subgroup](../Subgroup.md) of $G$ is [Cyclic](Cyclic.md)  
> 2. With $f$ a [Group-homomorphism](../Morphism/Group-homomorphism.md) of $G$, the [Image](../Morphism/Image.md) of $f$ is [Cyclic](Cyclic.md).  
  
> [!info] An infinite [Cyclic](Cyclic.md) [Group](../Group.md) has exactly two [Generators](../Generator.md) (if $a$ is one then $a^{-1}$ is the other)  
  
>[!info] With a finite [Cyclic](Cyclic.md) [Group](../Group.md) $G$ of [Order](../Order.md) $n$ and $x$ a [Generator](../Generator.md), The [Set](../../Sets/Set.md) of [Generators](../Generator.md) of $G$ contains only elements of the form $x^n$ for which $n$ is relatively prime to $n$.  
  
>[!info] With a [Cyclic](Cyclic.md) [Group](../Group.md) $G$ and two [Generators](../Generator.md) $a$ and $b$,  
>1. There exists an [Group-automorphism](../Morphism/Group-automorphism.md) to map $a$ onto $b$  
>2. Any [Group-automorphism](../Morphism/Group-automorphism.md) of $G$ maps $a$ onto some [Generator](../Generator.md) of $G$  
  
>[!info] With $G$ a [Cyclic](Cyclic.md) [Group](../Group.md) of [Order](../Order.md) $n$ and a positive integer $d$ that divides $n$,  
>There exists a unique [Subgroup](../Subgroup.md) of $G$ that has [Order](../Order.md) $d$.  
  
>[!info] With two [Cyclic](Cyclic.md) [Groups](../Group.md) $G_1$ and $G_2$ of order $m$ and $n$ respectively,  
>if $n$ and $m$ are relatively prime then $G_1\times G_2$ is also [Cyclic](Cyclic.md).  
  
>[!info] With a finite [Abelian](../../Commutativity_28Abelian29.md) [Group](../Group.md) $G$ and a [Cyclic](Cyclic.md) [Group](../Group.md) $C$ of order $p$,  
> if $G$ is not [Cyclic](Cyclic.md), then there exists a prime $p$ and a [Subgroup](../Subgroup.md) of $G$ that is [Isomorphic](../../Monoids/Morphisms/Isomorphism.md) to $C\times C$  
  
