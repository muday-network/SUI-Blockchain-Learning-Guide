# Cryptography in Blockchain

Cryptography is the backbone of blockchain technology, ensuring security, privacy, and data integrity. This section explores the key cryptographic concepts and techniques used in blockchains.

## Key Concepts

### Hash Functions
- **Definition:** A function that converts an input into a fixed-length string of characters, which appears random.
- **Properties:** Deterministic, quick to compute, pre-image resistant, and collision-resistant.
- **Examples:** SHA-256 (used in Bitcoin), Keccak-256 (used in Ethereum).

### Public-Key Cryptography
- **Asymmetric Encryption:** Involves a pair of keys – a public key (shared openly) and a private key (kept secret).
- **Uses:** Ensuring confidentiality and authentication.
- **Examples:** RSA, Elliptic Curve Cryptography (ECC).

### Digital Signatures
- **Purpose:** Ensure the authenticity and integrity of a message or transaction.
- **Process:** A sender signs a message with their private key; the receiver verifies it using the sender's public key.
- **Examples:** ECDSA (Elliptic Curve Digital Signature Algorithm).

### Zero-Knowledge Proofs
- **Definition:** A method by which one party can prove to another that they know a value without conveying any information about the value itself.
- **Applications:** Enhancing privacy in transactions.
- **Examples:** zk-SNARKs (Zero-Knowledge Succinct Non-Interactive Arguments of Knowledge).

## Practical Applications

### Securing Transactions
- **Integrity:** Hash functions ensure that transaction data has not been altered.
- **Authentication:** Digital signatures verify the sender's identity.

### Protecting Data
- **Encryption:** Ensures that sensitive data is only accessible to authorized parties.
- **Anonymity:** Techniques like zero-knowledge proofs provide privacy for users.

### Ensuring Consensus
- **Hash Puzzles:** In PoW, miners solve cryptographic puzzles to add new blocks.
- **Stake Verification:** In PoS, cryptographic techniques verify the legitimacy of staked tokens.

Cryptography is essential for the security and functionality of blockchain networks. For more detailed explanations, refer to the [References](../01_Introduction/09_References.md) section.
