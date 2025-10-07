For the purpose of this question, let us consider a block cipher with block size of 8 bits. A plaintext of 24 bits was being encrypted using ECB mode. The ciphertext was  

```
10101010 00001010 01011011
```

An attacker eavesdropped the ciphertext. Somehow, the attacker also knew that the plaintext was one of the followings.  

- **P1:** `11111111 00000000 11111111`  
- **P2:** `00000000 00000000 00000000`  
- **P3:** `11111111 00000000 10101010`  

### What could be inferred by the attacker about the plaintext?  
1. ○ Must be P1  
2. ○ Must be P2  
3. ○ Must be P3  
4. ○ Could be P1 or P3, but not P2  
