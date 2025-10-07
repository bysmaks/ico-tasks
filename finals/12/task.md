## AES Decryption Challenge  

Symmetric encryption uses the same key for both encryption and decryption.  
AES (Advanced Encryption Standard) is a symmetric block cipher standardized by NIST.  
It has a fixed data block size of **16 bytes**. Its keys can be **128, 192, or 256 bits long**.  
AES is very fast and secure, and it is the **de facto standard** for symmetric encryption.  

We have encrypted the flag (`b'{Flag}'`) with AES **key size 16 bytes** under **"MODE_EAX"**.  

The details are shown below:  

- **Key** = `b'ICO-NCL20252021'`  
- **Nonce** = `b'\x19\x0e\xdb\xf5\xf3\xcb\x0c\x82\x90\x01\x83F\x03='`  
- **Ciphertext** = `b';U\x0cZr[\xb4\xd8\x17\x84'`  

### Task:  
Create a program to **decrypt the ciphertext** and get the plaintext.  

Please enter the plaintext you obtain:  
