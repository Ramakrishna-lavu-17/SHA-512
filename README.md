# SHA-512

SHA-512 Hashing & Data Integrity
📌 Project Overview

This project demonstrates the use of SHA-512 (Secure Hash Algorithm 512-bit) for generating secure hash values and verifying data integrity.

The project explores how plaintext can be converted into a fixed-length hash and how hashing can be used alongside encryption to provide additional security.

🛠️ Concepts Used
SHA-512 Hashing
Hashcode Generation
Data Integrity
Confidentiality
Encryption & Decryption
Message Verification
Cryptographic Hash Functions
🔢 SHA-512 Hash Generation

SHA-512 converts input data into a 512-bit hash value, represented as a 128-character hexadecimal string.

Original Message
       ↓
    SHA-512
       ↓
512-bit Hash

Example:

"Hello"
   ↓
SHA-512
   ↓
128-character hexadecimal hash

A small change in the original message produces a completely different hash.

🛡️ Confidentiality & Integrity
Confidentiality

Encryption protects the actual content of a message.

Plaintext
   ↓
Encryption
   ↓
Encrypted Message
Integrity

Hashing can be used to determine whether data has been modified.

Message
   ↓
SHA-512
   ↓
Hash Value

The receiver can calculate the hash again and compare it with the original hash.

Original Hash
      ↓
     Compare
      ↑
New Hash

If they match, the data has not changed during the verification process.

🔄 Project Workflow
             Original Message
                    ↓
             SHA-512 Hashing
                    ↓
              Hashcode
                    ↓
          Store / Transmit Data
                    ↓
             Receive Message
                    ↓
            Generate New Hash
                    ↓
              Compare Hashes
                    ↓
          Integrity Verification
📂 Project Components
SHA-512 Hashcode Generation

Generates a cryptographic hash from the given input using the SHA-512 algorithm.

AES-text+hashcode

Demonstrates the combination of AES encryption and hashing, providing encryption for confidentiality and hashing for integrity verification.

Ensuring-Confidentiality&Integrity

Demonstrates the security concepts of protecting message contents through encryption and detecting modifications through hashing.

decrypt the message

Demonstrates the decryption process for recovering the original message from encrypted data.

🎯 Key Learning Outcomes

Through this project, I explored:

SHA-512 cryptographic hashing
Hashcode generation
Data integrity verification
AES encryption and decryption
Confidentiality vs. integrity
Combining encryption and hashing
Cryptographic security concepts
📌 Important Note

SHA-512 is a hashing algorithm, not an encryption algorithm. A SHA-512 hash cannot be "decrypted" back into the original message. Encryption such as AES is reversible with the appropriate key.
