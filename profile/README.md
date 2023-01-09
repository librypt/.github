## About libRypt
libRypt is an in-progress cryptography suite of libraries for simple, secure, and efficient cryptography in the Rust programming language.

| **Type of Cryptography**                      | **Implemented Algorithms** |
|-----------------------------------------------|----------------------------|
| Hash Function                                 | [MD5](https://www.github.com/librypt/librypt-hash-md5), [SHA-1](https://www.github.com/librypt/librypt-hash-sha1), [SHA-2](https://www.github.com/librypt/librypt-hash-sha2), [SHA-3](https://www.github.com/librypt/librypt-hash-sha3) |
| Message Authentication Code | [HMAC](https://www.github.com/librypt/librypt-mac-hmac)                      |
| Key Derivation Function                       | [HKDF](https://www.github.com/librypt/librypt-kdf-hkdf)    |
| Symmetric Encryption (AEAD)                   | [AES-GCM](https://www.github.com/librypt/librypt-aead-aes) |
| Asymmetric Encryption                         | [RSA](https://www.github.com/librypt/librypt-aea-rsa)      |
| Digital Signatures                            | [ECDSA](https://www.github.com/librypt/librypt-signature-ecdsa), [EdDSA](https://www.github.com/librypt/librypt-signature-eddsa), [RSA](https://www.github.com/librypt/librypt-signature-rsa) |
| Key Agreement Protocols                       | [DH](https://www.github.com/librypt/librypt-kap-dh), [ECDH](https://www.github.com/librypt/librypt-kap-ecdh) |

**Goals:**
* Support many common cryptographic traits & algorithm implementations
* Written in 100% safe Rust (with optional *unsafe* SIMD integration)
* Simple and ergonomic APIs that are hard to misuse
* Extensive documentation

**Non-goals:**
* Integration with existing cryptography libraries (such as OpenSSL)
* Support for other languages (the APIs are Rust-focused)
