# ATM DApp

This is a decentralized ATM application built using React, ethers.js, and Hardhat.

## Features
- Connect to MetaMask wallet
- View account balance
- Deposit and withdraw ETH from the smart contract

## Installation Guide

1. Clone the repository:
   ```sh
   git clone <repository-url>
   cd <repository-directory>
   ```

2. Install the dependencies:
   ```sh
   npm install
   ```

3. Open two additional terminals in your VS Code:

4. In the second terminal, start the Hardhat node:
   ```sh
   npx hardhat node
   ```

5. In the third terminal, deploy the smart contract:
   ```sh
   npx hardhat run --network localhost scripts/deploy.js
   ```

6. Back in the first terminal, start the front-end:
   ```sh
   npm run dev
   ```

After this, the project will be running on your localhost. Typically at [http://localhost:3000/](http://localhost:3000/).

## Usage

1. Open your browser and go to [http://localhost:3000/](http://localhost:3000/).
2. Connect your MetaMask wallet.
3. View your account balance.
4. Use the deposit and withdraw buttons to interact with the smart contract.


### Author

[Yash Dhiman]

