# Blockchain Using Single Linked Lists

## Overview
This project implements a basic blockchain-like data structure using a reversed **singly linked list** in Java. Each node in the list represents a block containing a **timestamp, hash, previous hash, and data**. The purpose of this project is to demonstrate the fundamental concepts of blockchain, such as hashing and linking blocks together sequentially.

## Features
- **Block Structure:** Each block stores data, timestamp, hash, and previous hash.
- **Hashing Mechanism:** Hashes are computed using Java's `hashCode()` method.
- **Linked List Implementation:** Blocks are linked using a singly linked list.
- **Immutable History:** Once a block is added, its hash is computed based on its contents and previous block hash.

## Project Structure
```
EndSem/
├── Node.java          # Defines the blockchain node structure
├── Block1.java        # (Expected) Represents a block with attributes and methods
├── Blockchain.java    # (Expected) Manages the linked list and blockchain operations
├── Main.java          # (Expected) Runs the blockchain demonstration
```

## Installation & Usage
1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/blockchain_using_single_linked_lists.git
   ```
2. Navigate to the project directory and compile the Java files:
   ```sh
   javac EndSem/*.java
   ```
3. Run the project:
   ```sh
   java EndSem.Main
   ```

## Future Enhancements
- Implement **Proof of Work (PoW)** mechanism for better security.
- Use **cryptographic hash functions (e.g., SHA-256)** instead of `hashCode()`.
- Enhance the linked list to support **double linking (doubly linked list)**.
- Implement a **network-based blockchain** with peer-to-peer communication.

## Contributing
Feel free to fork this repository, submit pull requests, or open issues for any suggestions or improvements.
