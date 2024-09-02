---  
title: Jammin cipher  
date created: Thursday, January 1st 1970, 1:00:00 am  
date modified: Monday, September 2nd 2024, 3:55:15 pm  
---  
# Jammin Cipher  
https://eprint.iacr.org/2022/531  
  
Operational [Ideal](../Security%20Strength/Ideal.md) for [Authenticated Encryption (AE)](./Authenticated_Encryption_28AE29.md)  
Goals:  
- $C$ leaks little information  
- Deterministic  
- Forgery free  
  
WIP:  
Upon wrap:   
- For new $AD$ and $P$  
	- Return random $C$ that is larger than $P$* (exclude existing codebook values and banned list)  
	- Save result in codebook  
- For existing $AD$ and $P$ return codebook value  
  
Unwrap:  
- Check $C$ in codebook for given $AD$, return P  
- If none found return $\perp$ and add $C$ to banned list  
  
Multi-instance:  
- Integrate an $ID$ value in all functions to split codebooks  
  
\*: Prevent exhaustion by making $C$ larger than $P$ by $t$ bytes  
$t$ bits is the max. [Security strength](../Security%20Strength/Security_strength.md)