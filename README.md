# TwinLock 🔒🔗

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)  
**Bi‐directional Hashlock/Timelock Atomic Swap** between Ethereum (Sepolia) and Tron (Nile).

TwinLock enables two parties to swap assets—ERC-20 tokens on Ethereum for native TRX on Tron—without intermediaries or custodians, using cryptographic hashlocks and timelocks.

---

## 📋 Table of Contents

- [Features](#features)  
- [Prerequisites](#prerequisites)  
- [Setup](#setup)  
  - [Clone & Install](#clone--install)  
  - [Environment Variables](#environment-variables)  
- [Usage](#usage)  
  - [Lock on Ethereum](#lock-on-ethereum)  
  - [Lock on Tron](#lock-on-tron)  
  - [Claim on Ethereum](#claim-on-ethereum)  
  - [Claim on Tron](#claim-on-tron)  
  - [Refund on Ethereum](#refund-on-ethereum)  
  - [Refund on Tron](#refund-on-tron)  
- [Project Structure](#project-structure)  
- [Testing](#testing)  
- [Contributing](#contributing)  
- [License](#license)  

---

## ✨ Features

- **Hashlock / Timelock** HTLC on both chains  
- **ERC-20 support** on Ethereum  
- **Native TRX support** on Tron  
- **Single shared secret** powers both locks  
- **Simple Node.js scripts**—no UI required  
- **Fast end-to-end demo** on testnets  

---

## 🛠 Prerequisites

- **Node.js** v18+ & **npm**  
- **Git** (for cloning and version control)  
- **Infura** or **Alchemy** Sepolia RPC key  
- **Tron** private key for Nile testnet  

---


cd TwinLock
npm install
