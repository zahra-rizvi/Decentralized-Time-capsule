# 🔮 Magic Time Capsule DApp

A beautiful and magical decentralized application that lets you store secret messages on the Ethereum blockchain, only to be revealed at a future time of your choosing! ✨

## 📖 Table of Contents
- [Overview](#-overview)
- [Features](#-features)
- [Technology Stack](#-technology-stack)
- [Project Structure](#-project-structure)
- [Smart Contract](#-smart-contract)
- [Installation & Setup](#-installation--setup)
- [How to Use](#-how-to-use)
- [Screenshots](#-screenshots)
- [Assignment Requirements](#-assignment-requirements)
- [Learning Outcomes](#-learning-outcomes)

## 🌟 Overview

Magic Time Capsule is a full-stack decentralized application that demonstrates the integration of Solidity smart contracts with a modern web interface. Users can create encrypted time capsules containing secret messages that remain locked until a specified future date, showcasing the power of blockchain for time-based data storage.

## ✨ Features

- **🔐 Secure Time Locking**: Messages remain encrypted until the specified unlock time
- **🎨 Magical UI**: Beautiful gradient animations and floating emojis
- **🦊 MetaMask Integration**: Seamless wallet connection and transaction signing
- **⏰ Future Reveals**: Set custom unlock timestamps for your secrets
- **📱 Fully Responsive**: Works perfectly on desktop and mobile devices
- **🔍 Real-time Updates**: Live status tracking and transaction monitoring
- **🎯 User-friendly**: Intuitive interface with sample data for testing

## 🛠️ Technology Stack

### Blockchain
- **Solidity** ^0.8.19
- **Ethereum** Sepolia Testnet
- **Web3.js** v1.8.2 for blockchain interaction
- **MetaMask** for wallet management

### Frontend
- **HTML5** with semantic structure
- **CSS3** with advanced animations and gradients
- **JavaScript** (ES6+) for dynamic functionality
- **Responsive Design** for cross-device compatibility

## 📁 Project Structure

```
MagicTimeCapsule/
│
├── MagicTimeCapsule.sol          # Solidity smart contract
├── MagicTimeCapsule.html         # Complete DApp frontend
├── screenshots/                  # Demonstration images
│   ├── deployment.png           # Contract deployment proof
│   ├── interface.png           # DApp interface
│   └── transactions.png        # Successful transactions
│
├── README.md                    # Project documentation
└── .gitignore                   # Git ignore file
```

## 📋 Smart Contract

### Contract Address
**`0x5C683c9f05A03E5E8e4c61a812B78Df5064d8604`** (Verified on Sepolia Etherscan)

### Functions

#### Write Functions
- `createCapsule(string message, uint256 unlockTime)` - Create a new time capsule
- `deleteCapsule()` - Remove your existing capsule

#### Read Functions
- `getMyCapsule()` - Retrieve capsule details and message (if unlocked)
- `hasCapsule()` - Check if user has an active capsule
- `getCapsuleStatus()` - Get current capsule status
- `getTotalCapsules()` - View total capsules created

## 🚀 Installation & Setup

### Prerequisites
- MetaMask browser extension installed
- Sepolia ETH for gas fees ([Get test ETH here](https://sepoliafaucet.com))
- Modern web browser (Chrome, Firefox, Brave, Edge)
- VS Code with Live Server extension (recommended)

### Quick Start
1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/magic-time-capsule.git
   cd magic-time-capsule
   ```

2. **Open the DApp**
   - Option 1: Open `MagicTimeCapsule.html` directly in your browser
   - Option 2: Use VS Code Live Server for better development experience

3. **Connect to Sepolia Testnet**
   - Open MetaMask
   - Select Sepolia Testnet from networks
   - Ensure you have Sepolia ETH for transactions

4. **Start Using the DApp**
   - Click "Connect MetaMask"
   - Create your first time capsule!

## 💫 How to Use

### 1. Connect Your Wallet
- Click the **"🦊 Connect MetaMask"** button
- Authorize the connection in MetaMask popup
- Your wallet address will display when connected

### 2. Create a Time Capsule
- Enter your secret message in the text area
- Set a future Unix timestamp ([Get from unixtimestamp.com](https://www.unixtimestamp.com))
- Click **"🎁 Create Time Capsule"**
- Confirm the transaction in MetaMask

### 3. Manage Your Capsule
- **Check Status**: View current capsule state
- **Reveal Message**: Access your secret when unlocked
- **Delete Capsule**: Remove your capsule from blockchain

### 4. Try Sample Data
- Use the **"🧪 Try Sample Data"** button to pre-fill form
- Perfect for testing and demonstration
