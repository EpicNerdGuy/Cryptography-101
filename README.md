# Cryptography Resources and Tools

Welcome to the ultimate repository for cryptography resources, tools, and information. Whether you're a beginner or a seasoned professional, you'll find valuable information and tools to enhance your understanding and practice of cryptography.

## Table of Contents

- [Introduction](#introduction)
- [Theory](#theory)
  - [Types of Encryption](#types-of-encryption)
  - [Symmetric Encryption](#symmetric-encryption)
  - [Asymmetric Encryption](#asymmetric-encryption)
  - [Hash Functions](#hash-functions)
  - [Key Length and Security](#key-length-and-security)
  - [Approved Algorithms](#approved-algorithms)
- [Articles](#articles)
- [Books](#books)
- [Courses](#courses)
- [Tools](#tools)
  - [Standalone](#standalone)
  - [Plugins](#plugins)
  - [Programming Libraries](#programming-libraries)
- [Resources](#resources)
  - [Blogs](#blogs)
  - [Mailing Lists](#mailing-lists)
  - [Web Tools](#web-tools)
  - [Websites](#websites)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Encryption is crucial for keeping digital information private and secure. This repository provides an overview of encryption types, algorithms, and essential tools for implementing cryptography in various programming languages.

## Theory

### Types of Encryption

Encryption transforms readable data into an encoded format. The two main types of encryption are:

- **Symmetric Encryption**: Uses a single secret key for both encryption and decryption.
- **Asymmetric Encryption**: Uses a pair of keys (public and private) for encryption and decryption.

### Symmetric Encryption

- **3DES (Triple DES)**: Applies the DES algorithm three times to each data block. Generates 192-bit keys.
- **AES (Advanced Encryption Standard)**: Generates keys of 128, 192, or 256 bits. Highly secure and widely used.

### Asymmetric Encryption

- **RSA (Rivest Shamir Adleman)**: Produces public and private key pairs. Key sizes: 1,024, 2,048, or 4,096 bits.
- **DSA (Digital Signature Algorithm)**: Standard algorithm introduced by NIST, with key lengths of 2,048 bits.

### Hash Functions

- **MD5**: Produces a 128-bit hash value. Vulnerable to extensive attacks, mainly used for checksums.
- **SHA1**: Produces a 160-bit hash value. No longer considered secure.
- **SHA2**: Includes SHA-256 and SHA-512, producing 256-bit and 512-bit hash values, respectively.
- **SHA3**: Designed to resist attacks from quantum computers, producing hash values of 224, 256, 384, or 512 bits.

### Key Length and Security

Longer keys provide better security but slower processing times. Balancing security and performance is crucial in modern encryption.

### Approved Algorithms

Web applications often combine symmetric and asymmetric encryption for security and performance. Examples include AES (symmetric) and RSA (asymmetric).

## Articles

- [How to Generate Secure Random Numbers in Various Programming Languages](https://nullprogram.com/blog/2017/01/25/)
- [Password Insecurity](https://www.troyhunt.com/password-insecurity/)
- [Secure Account Recovery Made Simple](https://paragonie.com/blog/2017/02/simplifying-secure-account-recovery)

## Books

- *A Graduate Course in Applied Cryptography* - [Amazon Link](https://www.amazon.com/Graduate-Applied-Cryptography-Dan-Boneh/dp/110701386X)
- *An Introduction to Mathematical Cryptography* - [Amazon Link](https://www.amazon.com/Introduction-Mathematical-Cryptography-Undergraduate-Mathematics/dp/1441926741)
- *Applied Cryptography: Protocols, Algorithms and Source Code in C* - [Amazon Link](https://www.amazon.com/Applied-Cryptography-Protocols-Algorithms-Source/dp/1119096723)
- *Crypto101* - [Crypto101.io](https://crypto101.io/)
- *Cryptography Engineering* - [Amazon Link](https://www.amazon.com/Cryptography-Engineering-Principles-Practical-Applying/dp/1119020918)
- *Handbook of Applied Cryptography* - [Free Download](http://cacr.uwaterloo.ca/hac/)
- *Introduction to Modern Cryptography* - [Amazon Link](https://www.amazon.com/Introduction-Modern-Cryptography-Principles-Protocols/dp/0367331581)
- *OpenSSL Cookbook* - [Free Download](https://www.feistyduck.com/library/openssl-cookbook/)
- *Practical Cryptography for Developers* - [GitHub Link](https://cryptobook.nakov.com/)
- *Real World Cryptography* - [Amazon Link](https://www.amazon.com/Real-World-Cryptography-David-Wong/dp/1617296717)
- *Security Engineering* - [Free Download](https://www.cl.cam.ac.uk/~rja14/book.html)
- *Serious Cryptography* - [Amazon Link](https://www.amazon.com/Serious-Cryptography-Practical-Introduction-Encryption/dp/1593278268)
- *The Code Book* - [Amazon Link](https://www.amazon.com/Code-Book-Science-Secrecy-Cryptography/dp/0385495323)
- *The Cryptoparty Handbook* - [Free Download](https://cryptoparty.in/documentation/handbook)
- *Understanding Cryptography* - [Amazon Link](https://www.amazon.com/Understanding-Cryptography-Textbook-Students-Practitioners/dp/3642041000)

## Courses

- *Cryptography I* (Coursera) - [Course Link](https://www.coursera.org/learn/crypto)
- *Applied Cryptography* (Stanford Online) - [Course Link](https://online.stanford.edu/courses/soe-ycscrypto-applied-cryptography)
- *Modern Cryptography* (Udemy) - [Course Link](https://www.udemy.com/course/cryptography/)

## Tools

### Standalone

- **OpenSSL**: Open-source tool for generating public and private keys. [OpenSSL](https://www.openssl.org/)
- **GnuPG**: Tool for secure communication and data storage. [GnuPG](https://gnupg.org/)

### Plugins

- **OpenSSL Plugin**: Plugins for integrating OpenSSL with various applications. [OpenSSL Plugins](https://www.openssl.org/docs/manmaster/man7/ossl_store.html)

### Programming Libraries

- **C**: [OpenSSL](https://www.openssl.org/), [libgcrypt](https://gnupg.org/software/libgcrypt/index.html)
- **C#**: [BouncyCastle](https://www.bouncycastle.org/csharp/), .NET Cryptography API
- **C++**: [Crypto++](https://www.cryptopp.com/), [Botan](https://botan.randombit.net/)
- **Java**: [BouncyCastle](https://www.bouncycastle.org/), [Java Cryptography Architecture (JCA)](https://docs.oracle.com/javase/8/docs/technotes/guides/security/crypto/CryptoSpec.html)
- **JavaScript**: [CryptoJS](https://cryptojs.gitbook.io/docs/), [Node.js crypto module](https://nodejs.org/api/crypto.html)
- **Python**: [PyCryptodome](https://www.pycryptodome.org/), [cryptography](https://cryptography.io/en/latest/)
- **Ruby**: [OpenSSL](https://ruby-doc.org/stdlib-2.6.1/libdoc/openssl/rdoc/OpenSSL.html), [RbNaCl](https://github.com/cryptosphere/rbnacl)
- **Rust**: [RustCrypto](https://github.com/RustCrypto), [ring](https://briansmith.org/rustdoc/ring/)
- **Other Languages**: Various libraries and frameworks available for different languages.

## Resources

### Blogs

- [Bruce Schneier on Security](https://www.schneier.com/)
- [Krebs on Security](https://krebsonsecurity.com/)
- [The Security Ledger](https://securityledger.com/)

### Mailing Lists

- [Cryptography Mailing List](http://lists.randombit.net/mailman/listinfo/cryptography)
- [OpenSSL Announce](https://mta.openssl.org/mailman/listinfo/openssl-announce)

### Web Tools

- [SSL Labs](https://www.ssllabs.com/)
- [Cryptographic Best Practices](https://www.cryptobestpractices.com/)

### Websites

- [NIST Computer Security Resource Center](https://csrc.nist.gov/)
- [OpenSSL Project](https://www.openssl.org/)
- [IETF Crypto Forum Research Group](https://irtf.org/cfrg)

## Contributing

Contributions are welcome! Please read the [contributing guidelines](CONTRIBUTING.md) before submitting any changes.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
