# Medical Health Management Blockchain Dapp

## Project Overview

This repository contains the source code for a Medical Health Management Dapp built using Solidity, Hardhat, Next.js, Context API, and Web3 providers. Follow the instructions below to set up and run the project successfully.

## Setup Instructions

### Prerequisites
Ensure you have the necessary software installed before proceeding:

#### Install VS Code Editor
[Download VS Code](https://code.visualstudio.com/download)

#### Node.js & NPM Version
- **Node.js:** v18.12.1 or v18.17.1 (MUST)
- **NPM:** 8.19.2
- [Download Node.js](https://nodejs.org/en/download)
- [Setup Video](https://youtu.be/)

#### Pinata (IPFS Storage)
- [Get Pinata API Key](https://pinata.cloud)
- [Get Pinata Secret Key](https://pinata.cloud)

### Clone Starter File
Clone the project starter files from the repository:
```
git clone https://github.com/YOUR-REPO-URL
cd medical-health-dapp
```

## Running the Project

If you have downloaded the final source code, follow these steps:

### Setup & Demo
Watch the setup and demo video for a detailed walkthrough:
```
WATCH: Setup & Demo Of Project
```

### Install Dependencies
Run the following command in the project directory:
```
npm install
```

### Running the Dapp Locally
```
npm run dev
```

### Deploying the Smart Contract
We are using RemixID for deploying the contract and generating the ABI, but you can also use Hardhat.
- [Open RemixID](https://remix-project.org)

### Free Test Faucets
Alchemy provides free test faucets to fund your wallet for deploying the contract.
- [Get Free Test Faucets](https://www.theblockchaincoders.com/resource)

### RPC URL Provider
We are using **ANKR** as the RPC provider.
- [ANKR RPC URL](https://www.ankr.com/rpc/)

### OpenAI API Key (Optional)
If using OpenAI features, add your API key:
```
NEXT_PUBLIC_OPEN_AI_KEY=YOUR_OPEN_AI_KEY
```
- [OpenAI API Reference](https://platform.openai.com/docs/api-reference/introduction)

### Pinata IPFS Keys
If using Pinata for IPFS storage, add your API keys:
```
NEXT_PUBLIC_PINATA_API_KEY=YOUR_PINATA_API_KEY
NEXT_PUBLIC_PINATA_SECRET_KEY=YOUR_PINATA_SECRET_KEY
```
- [Pinata Cloud](https://www.pinata.cloud/)

## Additional Resources
- [Final Source Code](#)
- [Final Code Setup Video](#)

# Hardhat Setup

## Overview

Hardhat development environment for local Ethereum smart contract testing. The accounts listed below are only available when using Hardhat's localhost network.

## Requirements

- **Node.js Version:** 18.17.1 (Must)
- **Installation:**
  ```sh
  npm install
  ```
- **Start Hardhat Node:**
  ```sh
  npm run node
  ```
- **Default Admin Account:**
  - Address: `0xf39Fd6e51aad88F6F4ce6aB8827279cffFb92266`
  - Balance: `10000 ETH`

## MetaMask Localhost Configuration

- **Network Name:** localhost
- **RPC URL:** `http://127.0.0.1:8545`
- **Chain ID:** 1337
- **Currency Symbol:** ETH / GO
- **Block Explorer URL:** Leave empty

### Important Notice

If you switch between different accounts in MetaMask, **clear your MetaMask history** each time to prevent issues.

## Hardhat Accounts

| Account # | Address | Private Key | Balance |
|-----------|------------------------------------------------------|------------------------------------------------------------------|----------|
| 0 (Admin) | `0xf39Fd6e51aad88F6F4ce6aB8827279cffFb92266` | `0xac0974bec39a17e36ba4a6b4d238ff944bacb478cbed5efcae784d7bf4f2ff80` | 10000 ETH |
| 1 | `0x70997970C51812dc3A010C7d01b50e0d17dc79C8` | `0x59c6995e998f97a5a0044966f0945389dc9e86dae88c7a8412f4603b6b78690d` | 10000 ETH |
| 2 | `0x3C44CdDdB6a900fa2b585dd299e03d12FA4293BC` | `0x5de4111afa1a4b94908f83103eb1f1706367c2e68ca870fc3fb9a804cdab365a` | 10000 ETH |
| 3 | `0x90F79bf6EB2c4f870365E785982E1f101E93b906` | `0x7c852118294e51e653712a81e05800f419141751be58f605c371e15141b007a6` | 10000 ETH |
| 4 | `0x15d34AAf54267DB7D7c367839AAf71A00a2C6A65` | `0x47e179ec197488593b187f80a00eb0da91f1b9d0b13f8733639f19c30a34926a` | 10000 ETH |
| 5 | `0x9965507D1a55bcC2695C58ba16FB37d819B0A4dc` | `0x8b3a350cf5c34c9194ca85829a2df0ec3153be0318b5e2d3348e872092edffba` | 10000 ETH |
| 6 | `0x976EA74026E726554dB657fA54763abd0C3a0aa9` | `0x92db14e403b83dfe3df233f83dfa3a0d7096f21ca9b0d6d6b8d88b2b4ec1564e` | 10000 ETH |
| 7 | `0x14dC79964da2C08b23698B3D3cc7Ca32193d9955` | `0x4bbbf85ce3377467afe5d46f804f221813b2bb87f24d81f60f1fcdbf7cbf4356` | 10000 ETH |
| 8 | `0x23618e81E3f5cdF7f54C3d65f7FBc0aBf5B21E8f` | `0xdbda1821b80551c9d65939329250298aa3472ba22feea921c0cf5d620ea67b97` | 10000 ETH |
| 9 | `0xa0Ee7A142d267C1f36714E4a8F75612F20a79720` | `0x2a871d0798f97d79848a013d4936a73bf4cc922c825d33c1cf7073dff6d409c6` | 10000 ETH |
| ... | ... | ... | ... |

_(Full account list continues up to Account #19)_

## Notes

- These accounts are pre-funded with **10,000 ETH** for development and testing.
- Never use these private keys on a testnet or mainnet.
- If you encounter connection issues, ensure your Hardhat node is running on localhost.

---

For any issues, feel free to open a GitHub issue or contribute to the repository!

Follow the above instructions carefully to successfully build and deploy your Medical Health Management Blockchain Dapp.

