# Blockchain Using Single Linked Lists

## Overview

This project implements a basic blockchain-like data structure using a reversed **singly linked list** in Java. Each node in the list represents a block containing a **timestamp, hash, previous hash, and data**. The purpose of this project is to demonstrate the fundamental concepts of blockchain, such as hashing and linking blocks together sequentially. This project was done in Dec '22.

[![forthebadge](https://forthebadge.com/images/badges/made-with-java.svg)](https://forthebadge.com) 

## Project Structure

```
EndSem/
├── Node.java                   # Defines the blockchain node structure
├── Block1.java                 # (Expected) Represents a block with attributes and methods
├── BlockChainExample.java      # (Expected) Manages the linked list and blockchain operations
├── SLL1.java                   # (Expected) Runs the blockchain demonstration
```

## Installation & Usage

1. Clone the repository:
   ```sh
   git clone https://github.com/Aadigha-git/Blockchain_using_Singly_Linked_Lists.git
   ```
2. Navigate to the project directory and compile the Java files:
   ```sh
   javac EndSem/*.java
   ```
3. Run the project:
   ```sh
   java EndSem.Main
   ```

## Features

- **Block Structure:** Each block stores data, timestamp, hash, and previous hash.
- **Hashing Mechanism:** Hashes are computed using Java's `hashCode()` method.
- **Linked List Implementation:** Blocks are linked using a singly linked list.
- **Immutable History:** Once a block is added, its hash is computed based on its contents and previous block hash.
- **Fundamental Blockchain Characteristics:**
  - Network of distributed immutable digital ledgers.
  - Can store anything of importance.
  - Allows digital information to be recorded and distributed but not edited.
  - Every change of information is recorded in a new block, validated with the owner's digital signature.
  - Decentralized ledger ensuring transparency and security.
  - Proof of Work mechanism for validation.

## How Blockchain Relates to Linked Lists
 <p align="center">
  <img src="https://github.com/user-attachments/assets/6e7dd2a7-ab18-4b20-bc4c-cd1bcd616d72" alt="App Screenshot" width="600">
</p>
- A **linked list** is a set of linear data structures linked together using pointers.
- Each **node** in a linked list stores data (element) and a pointer to the next node.
- While **blockchains are not linked lists**, they can be represented as a singly linked list.
- In a blockchain, each element (block) consists of:
  - A **header** describing the block.
  - A **storage part** containing the actual data.
  - A **hash** that links it to the previous block.
- This creates a **backward-linked structure**, ensuring integrity and security.

## Future Enhancements

- Implement **Proof of Work (PoW)** mechanism for better security.
- Use **cryptographic hash functions (e.g., SHA-256)** instead of `hashCode()`.
- Enhance the linked list to support **double linking (doubly linked list)**.
- Implement a **network-based blockchain** with peer-to-peer communication.

## Contributing

Feel free to fork this repository, submit pull requests, or open issues for any suggestions or improvements.
