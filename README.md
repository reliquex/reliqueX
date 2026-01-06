# ReliqueX

ReliqueX is a luxury-focused Real-World Asset (RWA) protocol that enables authenticated physical assets such as sneakers, watches, and collectibles to be securely vaulted, tokenized, and fractionalized on-chain.

The protocol is built exclusively on BNB Smart Chain (BSC) and optimized for low fees, fast settlement, and retail-friendly access.

---

## Overview

ReliqueX bridges high-value physical luxury assets with on-chain ownership by combining AI-assisted authentication, secure custody, and programmable fractional ownership.

Each physical asset is represented by a Master NFT, while economic rights are distributed via fractional ownership tokens.  
Liquidation or buyout events are executed through smart contracts, with proceeds distributed automatically to fractional holders.

ReliqueX focuses on culturally relevant RWAs rather than traditional assets like real estate or bonds.

---

## Technology Stack

- Blockchain: BNB Smart Chain (BSC)
- Smart Contracts: Solidity ^0.8.x  
- Frontend: Next.js + React + wagmi + ethers.js  
- Development: Hardhat, OpenZeppelin libraries  
- Metadata Storage: IPFS / Arweave  
- Authentication Layer: AI-assisted verification + human review  

---

## Supported Networks

- BNB Smart Chain Mainnet (Chain ID: 56)  
- BNB Smart Chain Testnet (Chain ID: 97)  

> ReliqueX is currently deployed only on BNB Chain.

---

## Contract Addresses

### BNB Smart Chain Mainnet (56)

| Contract | Address |
|--------|---------|
| Core / Vault Contract | 0x........ |
| Fraction Token Contract | 0x........ |
| Governance / Controller | 0x........ |

---

### BNB Smart Chain Testnet (97)

| Contract | Address |
|--------|---------|
| Core / Vault Contract | 0x........ |
| Fraction Token Contract | 0x........ |
| Governance / Controller | 0x........ |

---

## Core Components

### 1. Asset Vault
- Manages custody references for authenticated physical assets  
- Each asset receives a unique Vault ID  
- Vault state and lifecycle tracked on-chain  

### 2. Master NFT
- Represents the authenticated physical asset  
- Stores immutable metadata (provenance, authentication, vault ID)  
- Serves as the root reference for fractionalization  

### 3. Fractional Ownership Tokens
- ERC-1155 / ERC-20 based fractional shares  
- Represent proportional economic rights  
- Fully transferable on BNB Smart Chain  

### 4. Liquidation & Buyout Logic
- Assets can be liquidated via buyout or governance-driven sale  
- Smart contracts handle trustless profit distribution  
- No manual settlement or intermediaries  

---

## Key Features

- Luxury-Focused RWAs: Sneakers, watches, collectibles, and high-value goods  
- AI-Assisted Authentication: Reduces counterfeit risk before vaulting  
- Fractional Ownership: Access appreciation without full ownership  
- On-Chain Transparency: Ownership and payouts enforced by smart contracts  
- BNB Chain Optimized: Low gas costs and fast execution  
- Production Deployed: Live contracts on mainnet and testnet  

---

## Security

- Built using OpenZeppelin audited libraries  
- Modular contract architecture  
- Admin controls protected with role-based access  
- Pause mechanisms for emergency situations  
- External audits planned / ongoing  

---

## Development Status

- ✅ Smart contracts deployed (Mainnet & Testnet)  
- ✅ Core vault & fractionalization logic live  
- ✅ Frontend integration in progress  
- 🚧 Governance extensions planned  

---

## Disclaimer

ReliqueX is a protocol involving real-world assets.  
Users should perform their own due diligence before interacting with deployed contracts.  
Nothing in this repository constitutes financial or investment advice.

---

## Links

- Website: https://reliquex.com  
- X (Twitter): https://x.com/reliquexbnb  

---
