---  
title: Authenticated Encryption (AE)  
date created: Thursday, January 1st 1970, 1:00:00 am  
date modified: Monday, September 2nd 2024, 3:56:46 pm  
---  
# Authenticated Encryption (AE)  
Consists of a [Wrap](./Wrap.md) and [Unwrap](./Unwrap.md) function.  
  
Prevent leakage of information by adding [Nonce](../Nonce.md) to $AD$, this guarantees random $C$ even when all other parameters are the same.  
  
[Ideal](../Security%20Strength/Ideal.md) counterpart:  
Wrap function gives random outputs (random cipher)  
Unwrap function always returns $\perp$