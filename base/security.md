# security

a device conforming to the openmini specification must support at least the features provided by the Crypto++ library.  
as per the [Crypto++ homepage](https://www.cryptopp.com), these features include:

- authenticated encryption schemes: GCM, CCM, EAX, ChaCha20Poly1305, XChaCha20Poly1305
- high speed stream ciphers: ChaCha (8/12/20), ChaCha (IETF) HC (128/256), Panama, Rabbit (128/256), Sosemanuk, Salsa20 (8/12/20), XChaCha (8/12/20), XSalsa20
- AES and AES candidates: AES (Rijndael), RC6, MARS, Twofish, Serpent, CAST-256
- other block ciphers: ARIA, Blowfish, Camellia, CHAM, HIGHT, IDEA, Kalyna (128/256/512), LEA, SEED, RC5, SHACAL-2, SIMECK, SIMON (64/128), Skipjack, SPECK (64/128), Simeck, SM4,Threefish (256/512/1024), Triple-DES (DES-EDE2 and DES-EDE3), TEA, XTEA
- block cipher modes of operation: ECB, CBC, CBC ciphertext stealing (CTS), CFB, OFB, counter mode (CTR), XTS
- message authentication codes: BLAKE2b, BLAKE2s, CMAC, CBC-MAC, DMAC, GMAC (GCM), HMAC, Poly1305, SipHash, Two-Track-MAC, VMAC
- hash functions: BLAKE2b, BLAKE2s, Keccack (F1600), SHA-1, SHA-2, SHA-3, SHAKE (128/256), SipHash, LSH (128/256), Tiger, RIPEMD (128/160/256/320), SM3, WHIRLPOOL
- public-key cryptography: RSA, DSA, Determinsitic DSA (RFC 6979), ElGamal, Nyberg-Rueppel (NR), Rabin-Williams (RW), EC-based German Digital Signature (ECGDSA), LUC, LUCELG, DLIES (variants of DHAES), ESIGN
- padding schemes for public-key systems: PKCS#1 v2.0, OAEP, PSS, PSSR, IEEE P1363 EMSA2 and EMSA5
- key agreement schemes: Diffie-Hellman (DH), Unified Diffie-Hellman (DH2), Menezes-Qu-Vanstone (MQV), Hashed MQV (HMQV), Fully Hashed MQV (FHMQV), LUCDIF, XTR-DH
- elliptic curve cryptography: ECDSA, Determinsitic ECDSA (RFC 6979), ed25519, ECGDSA, ECNR, ECIES, x25519, ECDH, ECMQV
- insecure or obsolescent algorithms retained for backwards compatibility and historical value: MD2, MD4, MD5, Panama Hash, DES, ARC4, SEAL 3.0, WAKE-OFB, DESX (DES-XEX3), RC2, SAFER, 3-WAY, GOST, SHARK, CAST-128, Square
- pseudo random number generators (PRNG): ANSI X9.17 appendix C, RandomPool, VIA Padlock, DARN, RDRAND, RDSEED, NIST Hash and HMAC DRBGs
- password based key derivation functions: PBKDF1 and PBKDF2 from PKCS #5, PBKDF from PKCS #12 appendix B, HKDF from RFC 5869, Scrypt from RFC 7914
- Shamir's secret sharing scheme and Rabin's information dispersal algorithm (IDA)
- fast multi-precision integer (bignum) and polynomial operations
- finite field arithmetics, including GF(p) and GF(2^n)
- prime number generation and verification
- useful non-cryptographic algorithms
	- DEFLATE (RFC 1951) compression/decompression with gzip (RFC 1952) and zlib (RFC 1950) format support
    - Hex, base-32, base-64, URL safe base-64 encoding and decoding
    - 32-bit CRC, CRC-C and Adler32 checksum

these security features may optionally be implemented using hardware accelerators; software implementations will be provided in the fallback repository
