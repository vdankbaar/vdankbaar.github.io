With [Group](./Group.md) $G$ and [Subgroup](./Subgroup.md) $H$ of $G$,  
A [Subgroup](./Subgroup.md) is called normal if for all $x$ in $G$: $xHx^{-1}=H$  
This means that an element from $H$ will still be in $H$ after commuting with an element from $G$ but it need not be the same element.  
  
> [!example] A normal subgroup is the [Kernel](./Kernel.md) of a [Group-homomorphism](./Morphisms/Group-homomorphism.md).  
> With a [Set](../Sets/Set.md) $G'$ of [Cosets](./Coset.md) as defined by the normal subgroup $H$,  
> if $xH$ and $yH$ are cosets then $xHyH$ is also a coset as:  
> $$xHyH = xyHH=xyH$$ This makes $G'$ a [Group](./Group.md) as:  
> 1. This product of [Cosets](./Coset.md) can be seen as an [associative](../Associativity.md) [Law of composition](../Law-of-composition.md) on $G'$.  
> 2. The [Cosets](./Coset.md) $H$ can be seen as a [Unit Element](../Unit-Element.md) under this [Law of composition](../Law-of-composition.md).  
> 3. There is a notion of inverses as $x^{-1}H$ is the [Inverse](../Inverse.md) of $xH$.  
>   
> So $G'$ meets all the requirements to be a [Group](./Group.md).  
>  
>We can now define a [Group-homomorphism](./Morphisms/Group-homomorphism.md) $f: G \rightarrow G'$:  
>With element $x$ in $G$ and $xH$ being a [Cosets](./Coset.md): $$f(x)=xH$$  
>We can find the [Kernel](./Kernel.md) of $f$ by determining for what $x$: $f(x)=H$  
>In combination with the definition of $f$ it follows: $xH=H$  
>As $H$ is the [Unit Element](../Unit-Element.md) $H=HH$. From this it follows that $xH=HH$ and $x=H$.  
>In conclusion, the normal subgroup $H$ is the [Kernel](./Kernel.md) of our [Group-homomorphism](./Morphisms/Group-homomorphism.md) $f$.  
  
