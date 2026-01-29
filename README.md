# 🌊 VelaCore Smart Contracts (Flow EVM)

This repository contains the core financial infrastructure of VelaCore, ported to the Flow Blockchain to leverage its high throughput and consumer-friendly ecosystem.

## 📜 Included Contracts
- **VEC Token:** The native utility token for the VelaCore ecosystem.
- **Staking Module:** High-yield staking logic for $VEC holders.
- **Payment Gateway(In Development):** Smart contracts for non-custodial merchant settlements.

## 🚀 Why Flow EVM?
We are deploying on Flow's Crescendo (EVM) layer to provide:
- **Sub-second Finality:** Essential for retail merchant payments.
- **Predictable Fees:** Ensuring micro-transactions remain viable for SMEs.
- **Ethereum Compatibility:** Full Solidity support with Flow's scalability.

## 🛠 Tech Stack
- **Language:** Solidity (^0.8.0)
- **Framework:** Remix / Hardhat
- **Network:** Flow EVM Testnet

## 🔒 Security
All contracts are currently in the testing phase on Flow Testnet. Private keys are managed via environment variables and are never committed to this repository.
