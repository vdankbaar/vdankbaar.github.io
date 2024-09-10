A [Ring](./Ring.md) with a [Set](../Basic%20terms/Set.md) of polynomials $X$:  
Polynomials are of type $a(X)=a_0+a_1X+a_2X^2\dots a_nX^n$  
Has two [Binary operations](../Basic%20terms/Binary_Operation.md):  
- Addition: Add coefficients of polynomials together (additive group)  
- Multiplication: Perform normal polynomial multiplication (is [Closed](../Properties/Closed.md), [Associative](../Properties/Associative.md) and has a [Neutral element](../Properties/Neutral_element.md))  
	- Degree of $a(X)\times b(X)$ is sum of their degrees  
  
> [!info] Coefficients are finite but degree is infinite  
  
$\mathbb{Z}_2[X]/(1+X^2)$ is a [Ring](./Ring.md) but not a [Field](../Fields/Field.md) because under multiplication $1+X$ has no inverse.  
This is because $1+X^2$ is reducible into $(X+1)(X+1)$  
However $\mathbb{Z}_2[X]/(1+X+X^2)$ is a [Ring](./Ring.md) and also a [Field](../Fields/Field.md)