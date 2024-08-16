---  
title: Extended Euclidean Algorithm  
date created: Friday, August 16th 2024, 2:57:00 pm  
date modified: Friday, August 16th 2024, 2:57:44 pm  
---  
# Extended Euclidean Algorithm  
Given two starting numbers $a$ and $b$,  
The extended Euclidean Algorithm starts with a run of the [Euclidean Algorithm](./Euclidean20Algorithm.md) to determine $GCD(a,b)$.  
Given that the $GCD$ turns out to be 1,  
Then some of the calculations of the [Euclidean Algorithm](./Euclidean20Algorithm.md) can then be substituted into one another to determine the inverse of $a$ modulo $b$.  
  
## Traditional method  
Below you can see the steps to the [Extended Euclidean Algorithm](Extended20Euclidean20Algorithm.md).  
1. Start by calculating the modulo between $a$ and $b$ (33 and 19 respectively in this example)  
2. Iterate down repeating the modulo function till 0 is reached  
3. Recreate the full equations of every step including the quotients (blue).  
4. Start with the bottom equation. Step-by-step substitute every equation into it till you reach the top.  
5. The number that is being multiplied with $b$ is the inverse.   
![EEA-step-by-step.svg](./Images/EEA-step-by-step.svg)  
  
## Quick paper method  
In my opinion, the traditional method is nice to get an understanding on how the EEA is supposed to work.  
However, I found it to be quite time consuming doing every substitution and subsequent calculations, especially when I have multiple inverses I need to calculate.  
Below I've written down a streamlined method based off the traditional calculations.  
It gets the answer faster at the cost of being not immediately intuitive.   
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
