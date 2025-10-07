## Shift Cipher Encryption  

Shift cipher is one of the simplest and most widely known encryption techniques. It is a type of substitution cipher in which each letter in the plaintext is replaced by a letter some fixed number of positions down the alphabet.  

Give the below C shift cipher program:  

```c
int main()  
{  
    char text[500], ch;  
    int key;  
    printf("Enter a message to encrypt: ");  
    scanf("%s", text);  
    printf("Enter the key: ");  
    scanf("%d", &key);  
    for (int i = 0; text[i] != '\0'; ++i)  
    {  
        ch = text[i];  
        ch = (ch - 'a' + key) % 26 + 'a';  
        text[i] = ch;  
    }  
    printf("Encrypted message: %s", text);  
    return 0;  
}  
```

With the input string **iparticipateico** and the key value **999**, what encrypted message will you get?  
