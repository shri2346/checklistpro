# Task Priority Smart Contract dApp

## **Contract Address**
`0x10c2b824eabF079E11e8fdDE9C3b3d2b7858D464`  
View on Flare Coston2 Explorer:  
https://coston2-explorer.flare.network/address/0x10c2b824eabF079E11e8fdDE9C3b3d2b7858D464

---

## **Project Description**
This project is a decentralized Task Priority Manager built on the Flare Coston2 testnet.  
It enables users to store, manage, and complete tasks on-chain with full transparency and immutability.  
By leveraging blockchain, the system ensures trustless task management where data cannot be altered or lost.

---

## **Features**
- **Add Tasks:** Users can add tasks with a simple description.
- **Complete Tasks:** Users can mark any task as completed.
- **View Task Count:** Reads total number of tasks stored in the contract.
- **Read Individual Tasks:** Fetches description + completion state.
- **Fully On-Chain Storage:** All tasks are stored directly inside the smart contract.
- **Wallet-Based Access:** Only connected wallets can interact.
- **UI Status Handling:** Loading, pending, confirmed, and error handling included.

---

## **How It Solves Problems**
Traditional task management apps have issues:
- No transparency
- Easy to manipulate or delete data
- No shared, tamper-proof history
- Centralized systems may lose or compromise data

This blockchain-based task manager solves these problems:
### **1. Immutable Records**
Once a task is added, it cannot be altered by anyone—including the app owner.

### **2. Decentralized Ownership**
Each user interacts directly with the contract using their wallet. No login required.

### **3. Trustless Completion Tracking**
Task completion is validated and stored on-chain, ensuring accuracy.

### **4. Web3 Transparency**
Anyone can verify the state of tasks publicly using the contract address.

### **5. Ideal For:**
- Personal productivity tracking  
- Team transparency workflows  
- Verifiable task registries  
- Learning blockchain state management patterns  

---

## **Tech Stack**
- **Next.js (App Router)**
- **Wagmi + Viem**
- **Flare Blockchain (Coston2 Testnet)**
- **Smart Contract (Solidity)**

---

## **Repository Structure**