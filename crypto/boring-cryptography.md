Boring cryptography refers to the idea that cryptographic systems should be easy to use and hard to misuse, making them less complex and more accessible for developers.
Many important Cryptography libraries like OpenSSL are written in C. With the advances of technology we now have languages like Rust. With its built-in safety features 
and the ability to write safeer and more predicatable code. Rust's ownership and borrowing system ensures memory safety by preventing null pointer dereferencing and memory leaks at compile time, which can be crucial for cryptographic operations that require strict adherence to constant-time execution to avoid side-channel attacks.

## Rust Crypto
A very comprehensive collection of Rust crates that are maintained by a core team. Many crates in this ecosystem have never had a security audit performed, use at your own risk. 
https://github.com/RustCrypto

## Dalek Cryptography 
Developed by a cryptographier who has been involved with the development of various cryptographic implementations for Tor and Signal App.
https://github.com/dalek-cryptography

## Cryptographic API Services
CAS is a abstraction layer to various cryptographic algortims implemented by the RustCrypto and Dalek Cryptography teams. It allows you to use the underlying algorithms written in Rust directly in C#, TypeScript, and Python through a Foreign Function Interface.
This project is currently maintained and developed by WingZer0o a R4ptx community member. Feel free to reach out with questions!
https://github.com/Cryptographic-API-Services
