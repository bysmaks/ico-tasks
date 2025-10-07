For the purpose of this question, let us consider a block cipher with block size of 8 bits. Two plaintext of 16 bits were being encrypted using CTR mode (i.e. stream cipher). The ciphertexts were:

```
C1 = 11111111 11111111 00000000
C2 = 00000000 00001111 00001111
```

Note that the respective first block in C1 and C2 was the IV. An attacker eavesdropped both ciphertexts. Somehow, the attacker also knew that the two corresponding plaintexts must be among the following 4 possibilities.

- **P1:** `11110101 00001111`
- **P2:** `00001010 00000000`
- **P3:** `11111111 00001010`

### What could be inferred by the attacker about the corresponding plaintext of C1 and C2?
1. ○ Both were P1.  
2. ○ One of them was P1, and the other was P2.  
3. ○ One of them was P2, and the other was P3.  
4. ○ No additional information could be inferred.  
