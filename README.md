# AES-Cryptography

This repository contains a Python implementation of the AES (Advanced Encryption Standard) cryptographic algorithm. The program supports both encryption and decryption processes, utilizing a 256-bit key. It emphasizes the four core AES operations that make the algorithm secure, including SubBytes, ShiftRows, MixColumns, and key expansion.

---

## Key Features

- **256-Bit Key Encryption**: The implementation uses a 256-bit key, supporting 14 rounds of transformation as per AES standards.
- **Key Expansion**: Generates a robust schedule of round keys from the input key using bitwise operations, modular arithmetic, and S-box transformations.
- **SubBytes Transformation**: Applies a substitution step using S-box values for data security.
- **ShiftRows Transformation**: Shifts rows in the state array to enhance diffusion.
- **MixColumns Transformation**: Combines data across columns of the state array for additional mixing (encryption only).
- **Round-Based Processing**: Performs 14 rounds of AES transformations for both encryption and decryption.
- **Encryption and Decryption Modes**: Supports both encrypting plaintext into ciphertext and decrypting ciphertext back into plaintext.
