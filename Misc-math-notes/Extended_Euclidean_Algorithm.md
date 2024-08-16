---  
title: Extended Euclidean Algorithm  
date created: Friday, August 16th 2024, 2:57:00 pm  
date modified: Friday, August 16th 2024, 5:04:53 pm  
---  
# Extended Euclidean Algorithm  
Given two starting numbers $a$ and $b$,  
The extended Euclidean Algorithm is often used to determine the inverse of $a$ modulo $b$.  
## Traditional Method  
The Extended Euclidean Algorithm starts with a run of the [Euclidean Algorithm](./Euclidean_Algorithm.md) to determine the various divisors (also determining the $gcd(a,b)$ along the way).  
Next the equations are written to take on the following form:  
$remainder = dividend-quotient * divisor$   
These equations are then substituted into one another to retrieve an equation of the form:$gcd(a,b)=x*a+y*b$  
where if $gcd(a,b)=1$, $x$ is the inverse of $a$.  
Below you can see the steps to the [Extended Euclidean Algorithm](Extended_Euclidean_Algorithm.md).  
1. Start by calculating the modulo between $a$ and $b$ (19 and 33 respectively in this example)  
2. Iterate down repeating the modulo function till 0 is reached  
3. Recreate the full equations (including the quotients in blue).  
4. Start with the bottom equation. Step-by-step substitute every equation into it till you reach the top.  
5. The number that is being multiplied with $a$ (19) is the inverse.   
![EEA-step-by-step.svg](./Images/EEA-step-by-step.svg)  
  
## Quick Paper Method  
In my opinion, the traditional method is nice to get an understanding of how the EEA works.  
However, I found it to be quite time consuming doing every substitution and subsequent calculations by hand. Especially when I have multiple inverses I need to calculate.  
Below is a streamlined method based off the traditional calculations.  
It gets the answer faster at the cost of being not very intuitive.   
![EEA-quick-paper-method.svg](./Images/EEA-quick-paper-method.svg)  
  
### Example $661^{-1}$ modulo $877$  
Following the above diagram we generate the table below.  
  
| Step 1 | Step 2 | Step 3 |  
| :----: | :----: | ------ |  
|  877   |        | -337   |  
|  661   |   -1   | 254    |  
|  216   |   -3   | -83    |  
|   13   |  -16   | 5      |  
|   8    |   -1   | -3     |  
|   5    |   -1   | 2      |  
|   3    |   -1   | -1     |  
|   2    |   -1   | 1      |  
|   1    |   -    |        |  
|   0    |        |        |  
  
The result is $-337$ which is $540$ mod $877$.  
And sure enough $661*540\equiv1$ mod $877$.  
