# Organ Donation and Transplantation System Using Blockchain

## Overview
The **Organ Donation and Transplantation System** leverages **blockchain technology** to enhance the transparency, security, and efficiency of the organ donation and transplantation process. This system ensures tamper-proof records for donor and recipient information, facilitates real-time matching, and ensures secure tracking of organ donations. By using blockchain, the system enhances trust, accountability, and speed in the life-saving process of organ transplants.

## Features
- **Donor and Recipient Registration**: Secure registration of donor and recipient information using blockchain.
- **Blockchain Ledger**: Immutable and tamper-proof records of donations and transplants stored on the blockchain.
- **Real-Time Matching**: Smart contracts automate matching donors and recipients based on medical and compatibility criteria.
- **Organ Tracking**: Detailed tracking of each organ from donor to recipient to ensure accountability.

## Technologies Used
- **Frontend**: React.js (or HTML/CSS/JavaScript)
- **Backend**: Node.js with Web3.js
- **Blockchain**: Ethereum or Hyperledger Fabric for decentralized ledger
- **Smart Contracts**: Solidity for Ethereum-based contract logic
- **Authentication**: Blockchain-based identity management (e.g., MetaMask or other wallets)
- **Test Blockchain**: Ganache for local testing, or public Ethereum testnets like Rinkeby or Kovan.

## Getting Started

### Prerequisites
Before getting started, ensure you have the following installed on your system:
- **Node.js** (version 14 or later)
- **Ganache** (for local blockchain testing) or access to a **public Ethereum testnet**
- **MetaMask** (or equivalent blockchain wallet for transaction management)

### Installation Steps

1. **Clone the repository**:
   ```bash
   git clone https://github.com/rohit-2002/organ-donation-blockchain.git
   cd organ-donation-blockchain
   
2. **Install dependencies:**
   ``` bash
   npm install
   
3. **Deploy smart contracts:**
   - **Install Truffle (if not already installed):**
     ```bash
     npm install -g truffle
     
4. **Compile and deploy the smart contracts:**
   ```bash
   truffle compile
   truffle migrate --network development
5. **Set up environment variables:**
   - Configure .env file with blockchain RPC URL (for testnet or local Ganache), smart contract addresses, and your Ethereum wallet private key for transactions.
     
6. **Start the application:**
   ```bash
   npm start
