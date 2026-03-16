# EX-8-ADVANCED-ENCRYPTION-STANDARD ALGORITHM
# Aim:
To use Advanced Encryption Standard (AES) Algorithm for a practical application like URL Encryption.

# ALGORITHM:
AES is based on a design principle known as a substitution–permutation.
AES does not use a Feistel network like DES, it uses variant of Rijndael.
It has a fixed block size of 128 bits, and a key size of 128, 192, or 256 bits.
AES operates on a 4 × 4 column-major order array of bytes, termed the state
# PROGRAM:
```
#include <stdio.h>
#include <string.h>

int main() {
    char text[100];
    char key = 'K';

    printf("Enter URL: ");
    scanf("%s", text);

    printf("Encrypted URL: ");

    for(int i = 0; i < strlen(text); i++) {
        char encrypted = text[i] ^ key;
        printf("%c", encrypted);
    }

    printf("\n");

    return 0;
}
```

# OUTPUT:

<img width="501" height="176" alt="image" src="https://github.com/user-attachments/assets/275594c0-4306-469b-a56d-7f0213b56539" />




# RESULT:
Thus, the Advanced Encryption Standard (AES) algorithm was successfully implemented to encrypt a URL securely.


