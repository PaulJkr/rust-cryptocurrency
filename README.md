# 🔗 Simple Blockchain in Rust

![Rust](https://img.shields.io/badge/Rust-1.70%2B-orange?logo=rust)
![License](https://img.shields.io/badge/License-MIT-blue.svg)

A **minimal yet functional blockchain implementation** written in Rust 🦀.  
This project demonstrates how core concepts of blockchain work under the hood—blocks, hashes, proof-of-work, and chain validation—all implemented from scratch.

---

## ✨ Features

- 📦 **Block Structure** – Includes index, timestamp, data, previous hash, and current hash
- 🔐 **SHA-256 Hashing** – Ensures block integrity and immutability
- ⛏️ **Proof-of-Work** – Simple mining algorithm with configurable difficulty
- 🔗 **Chain Validation** – Checks for tampering and maintains consistency
- 📄 **Command-Line Logging** – Trace block addition, mining time, and chain status

---

## 🛠️ Tech Stack

- **Language**: [Rust](https://www.rust-lang.org/) (1.70+)
- **Hashing**: [`sha2`](https://crates.io/crates/sha2)
- **Serialization**: [`serde`](https://crates.io/crates/serde), [`serde_json`](https://crates.io/crates/serde_json)
- **Date/Time**: [`chrono`](https://crates.io/crates/chrono)

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/PaulJkr/rust-cryptocurrency.git
cd rust-cryptocurrency
```
### 2. Build and run the project

```bash
cargo run
```
# 🧪 Sample Output
```bash
Mining block 1...
Block mined in 0.231s with hash: 0000c8c7...

Mining block 2...
Block mined in 0.442s with hash: 0000b51a...

Is blockchain valid? true
```
# 📜 License
This project is licensed under the MIT License. See the LICENSE file for details.<br>

# Crafted with ❤️ in Rust for educational purposes
## Author: PaulJkr
