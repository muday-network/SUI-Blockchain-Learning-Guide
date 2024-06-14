# Installing SUI Node

Setting up a SUI node is the first step to interacting with the SUI blockchain. This guide will walk you through the installation process.

## Prerequisites

- **Operating System:** Linux, macOS, or Windows (using WSL)
- **Hardware Requirements:** Minimum 4GB RAM, 2 CPU cores
- **Software Requirements:** Git, Docker, Node.js

## Step-by-Step Installation

### 1. Clone the SUI Repository

```bash
git clone https://github.com/sui-blockchain/sui.git
cd sui
```
2. Install Dependencies
Make sure you have Docker installed. Then run:


```sh
docker-compose up -d
```
4. Verify Installation
To ensure the node is running, you can check the logs:

```sh
docker-compose logs -f sui-node
```
If everything is set up correctly, you should see the node syncing with the network.

Troubleshooting
Common Issues: If you encounter errors, check the Troubleshooting Guide.
Support: Visit the SUI Community Forum for additional help.

### 04_Setting_Up_Environment/02_Setting_Up_Development_Environment.md

```markdown
# Setting Up Development Environment

To start developing on the SUI blockchain, you'll need a properly configured development environment. This guide will help you set up the essential tools.

## Prerequisites

- **Code Editor:** VS Code (recommended), Atom, Sublime Text
- **Package Manager:** npm or yarn

## Step-by-Step Setup

### 1. Install Node.js

Download and install Node.js from [nodejs.org](https://nodejs.org/).

### 2. Set Up VS Code

Install Visual Studio Code from [code.visualstudio.com](https://code.visualstudio.com/). Recommended extensions:

- **Prettier:** Code formatter
- **ESLint:** Linting tool for JavaScript
- **Solidity:** Support for Solidity smart contract language

### 3. Install SUI CLI

```bash
npm install -g sui-cli
```
4. Initialize a Project
Create a new project directory and initialize it:

```sh
mkdir sui-project
cd sui-project
sui-cli init
```

5. Configure Environment Variables
Set up necessary environment variables in a .env file:
```sh
SUI_NODE_URL=http://localhost:9000
```

Additional Setup
Git: Version control system. Install from git-scm.com.
Docker: For containerized environments. Install from docker.com.
Your development environment is now ready. Proceed to the next section to learn how to use the SUI Wallet.


### 04_Setting_Up_Environment/03_Using_SUI_Wallet.md

```markdown
# Using SUI Wallet

The SUI Wallet allows you to manage your tokens, interact with dApps, and more. This guide will show you how to set up and use the SUI Wallet.

## Installing SUI Wallet

### 1. Download the Wallet

Visit the [SUI Wallet website](https://wallet.sui-blockchain.com) and download the appropriate version for your operating system.

### 2. Install the Wallet

Follow the installation instructions provided on the website to install the wallet on your device.

## Setting Up Your Wallet

### 1. Create a New Wallet

Open the SUI Wallet application and select "Create New Wallet." Follow the prompts to set up a new wallet.

### 2. Secure Your Wallet

Write down your seed phrase and store it in a safe place. This is crucial for recovering your wallet if you lose access.

### 3. Add Funds

To add funds to your wallet, you can:

- **Receive Tokens:** Use the "Receive" feature to get your wallet address and transfer tokens from another wallet.
- **Faucet:** On the testnet, use the SUI Faucet to get free test tokens.

## Using the Wallet

### 1. Sending Tokens

To send tokens, select the "Send" option, enter the recipient's address, the amount, and confirm the transaction.

### 2. Interacting with dApps

Use the "dApps" section of the wallet to interact with decentralized applications built on the SUI blockchain.

### 3. Viewing Transaction History

Check your transaction history in the "Transactions" tab to see all past transactions.

For more detailed information, refer to the [SUI Wallet Documentation](https://docs.sui-blockchain.com/wallet).
