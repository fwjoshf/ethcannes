# MeowPay

## 📝 Description

MeowPay is a decentralized salary payment platform designed to guarantee freelancers and employees receive their wages securely and on time. The system combines a smart contract, a subgraph for indexing via The Graph, and a modern web application.  

Employers can pre-fund and lock their organization’s account, giving freelancers and employees confidence that payments are guaranteed. Once work is registered, employees can trigger their payments anytime, ensuring financial autonomy and security.  

---

## ⚙️ Tech Stack

### 🛠 Smart Contract
- Solidity
- Hardhat
- Base Chain (Base-Sepolia)

### 🔒 Verification & Security
- WorldID for human verification

### 📊 Indexing & Data Query
- The Graph
- @apollo/client (GraphQL queries to Subgraph)

### 💻 Web Application
- React / Next.js
- TypeScript
- MUI (Material-UI for UI components)

### 🔗 Blockchain Interaction
- Wagmi
- Viem

### 🌐 Additional Integrations
- ENS for simplified and secure employee registration
- WalletConnect for seamless wallet integration
- BlockScout for contract verification and monitoring on-chain activity

---

## ✨ Features

- Employers can pre-fund and lock organizational accounts.
- Employees can trigger payments anytime after logging their work.
- Supports unbanked individuals through blockchain-based payments.
- Records all transactions on-chain for transparency and accountability.
- Simplified employee registration using ENS.
- Verifies employees as real humans with WorldID.
- Seamless wallet connections with WalletConnect.
- Smart contract and on-chain activities viewable on BlockScout.

---

## 🔥 How It Works

1. **Employer Registration** – Employers register and fund their organization’s account.  
2. **Employee Registration** – Employees sign up using ENS and verify their identity with WorldID.  
3. **Work Logging** – Employees log their work sessions/days.  
4. **Payment Trigger** – Employees can initiate payment anytime after work is logged.  

This workflow ensures secure, transparent, and instant salary disbursement.

---

## 🚀 Getting Started

1. Clone the repository:
   ```bash
   git clone <your-repo-url>
