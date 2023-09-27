## About libRypt
libRypt is an in-progress cryptography suite of libraries for simple, secure, and efficient cryptography in the Rust programming language.

* 🛠️ - Planned, in progress
* 🆗 - Working (passing tests)
* ✅ - Audited/verified (ready for production use)
* 🚧 - Maintainence, deprecated

**NOTE:** If there is an algorithm or feature missing from this table that you think should be apart of libRypt, please let us know by creating an issue on the main repository!

| **Type of Cryptography**                      | **Implemented Algorithms** |
|-----------------------------------------------|----------------------------|
| Hash Function                                 | [MD2 🛠️](https://www.github.com/librypt/librypt-hash-md2), [MD4 🛠️](https://www.github.com/librypt/librypt-hash-md4), [MD5 🆗](https://www.github.com/librypt/librypt-hash-md5), [MD6 🛠️](https://www.github.com/librypt/librypt-hash-md6), [SHA-1 🆗](https://www.github.com/librypt/librypt-hash-sha1), [SHA-2 🆗](https://www.github.com/librypt/librypt-hash-sha2), [SHA-3 🆗](https://www.github.com/librypt/librypt-hash-sha3), [BLAKE2 🆗](https://www.github.com/librypt/librypt-hash-blake2), BLAKE3 (wrapper) 🛠️, [Whirlpool 🛠️](https://www.github.com/librypt/librypt-hash-whirlpool), GOST 🛠️, RIPEMD 🛠️ |
| Message Authentication Code                   | [HMAC 🆗](https://www.github.com/librypt/librypt-mac-hmac) |
| Key Derivation Function                       | [HKDF 🆗](https://www.github.com/librypt/librypt-kdf-hkdf), PBKDF1 🛠️, PBKDF2 🛠️, Argon2 🛠️ |
| Symmetric Encryption                          | [AES-GCM 🛠️](https://www.github.com/librypt/librypt-aead-aes), Salsa20 🛠️, ChaCha 🛠️ |
| Asymmetric Encryption                         | [RSA 🛠️](https://www.github.com/librypt/librypt-aea-rsa), DLIES 🛠️, ECIES 🛠️ |
| Digital Signatures                            | [DSA 🛠️](https://www.github.com/librypt/librypt-signature-dsa), [RSA 🛠️](https://www.github.com/librypt/librypt-signature-rsa), [ECDSA 🛠️](https://www.github.com/librypt/librypt-signature-ecdsa), [EdDSA 🛠️](https://www.github.com/librypt/librypt-signature-eddsa), Dilithium 🛠️, Falcon 🛠️ |
| Key Agreement Protocols                       | [DH 🛠️](https://www.github.com/librypt/librypt-kap-dh), [ECDH 🛠️](https://www.github.com/librypt/librypt-kap-ecdh) |
| Key Exchange Mechanisms                       | Kyber 🛠️ |
| One-time Passwords                            | [HOTP 🆗](https://www.github.com/librypt/librypt-hotp), [TOTP 🆗](https://www.github.com/librypt/librypt-totp) |

**Goals:**
* Support all common cryptographic traits, primitives, and algorithm implementations
* Written in 100% safe Rust (potentially with optional *unsafe* optimizations)
* Embedded and WASM friendly (no_std everywhere)
* Simple and ergonomic APIs that are hard to misuse
* No third-party dependencies
* Extensive documentation

**Non-goals:**
* Integration with existing cryptography libraries (such as OpenSSL)
* Support for other languages (the APIs are Rust-focused)
