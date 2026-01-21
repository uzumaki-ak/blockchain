# Blockchain Fundamentals – Personal Notes

This repository documents my handwritten notes while learning blockchain fundamentals.  
The content below is limited strictly to what I studied and wrote, up to **Proof of Work (PoW)**.

---

## What is Blockchain?

- Blockchain is a **global ledger**
- All full nodes store a copy of the blockchain
- Data once written **cannot be changed**
- Used to transfer value without a central authority

---

## Blocks & Transactions

- A blockchain is made up of **blocks**
- Each block contains:
  - Transactions
  - Block header
  - Hash of the previous block

### Block Header Includes:
- Previous block hash
- Timestamp
- Nonce
- Merkle root

---

## Hashing

- Hash = output of a cryptographic hash function
- Any small change in input completely changes the hash
- Hashing ensures **data integrity**

---

## Cryptography in Blockchain

### Public Key
- Used to **receive funds**
- Can be shared openly

### Private Key
- Used to **sign transactions**
- Must be kept secret
- Whoever has the private key controls the funds

### Digital Signatures
- Proves ownership
- Ensures transaction authenticity
- Prevents tampering

---

## Nodes

- Nodes are computers running blockchain software
- Types of nodes:
  - Full nodes
  - Mining nodes

Roles of nodes:
- Validate transactions
- Maintain a copy of the blockchain
- Broadcast data to the network

---

## Gas & Transaction Fees (Ethereum Context)

- Gas measures **computational effort**
- Similar to weight in a delivery system

### Key Points:
- More complex transactions → more gas
- Gas price depends on network demand
- Transaction fee formula:

Transaction Fee = Gas Used × Gas Price


### Fee Levels:
- Slow
- Market
- Advanced

- Fees are paid in the **native currency**
  - Ethereum → ETH

---

## Blocks & Chain Linking

- Each block contains the **hash of the previous block**
- This links blocks together to form a chain
- Changing one block breaks all following hashes

---

## Nonce

- Nonce is a number used **once**
- Miners change the nonce to find a valid hash
- Helps satisfy the difficulty condition

---

## Proof of Work (PoW)

- Consensus mechanism used by Bitcoin and earlier Ethereum
- Miners compete to find a valid hash
- Requires:
  - Computational power
  - Energy

### How PoW Works:
1. Miner collects transactions
2. Creates a block
3. Tries different nonces
4. Finds a hash that meets difficulty target
5. Block is added to the chain
6. Miner gets rewarded

---

## Mining

- Mining = process of validating transactions
- Miners:
  - Secure the network
  - Prevent double spending
  - Add new blocks

---

## Difficulty

- Difficulty controls how hard it is to find a valid hash
- Adjusts based on:
  - Network hash power
  - Block production time

---

## Notes

- These notes cover concepts **only up to Proof of Work**
- Proof of Stake (PoS) is **not included**
- Further concepts will be added later after study

---
