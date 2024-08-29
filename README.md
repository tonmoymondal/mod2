# Bank
- simple Web3 application for transferring Ether and personalizing your account. 

## Description 

The smart contract used in this project is named `Bank` present inside the `contracts/Bank.sol` file. It allows users to set an account name and transfer funds. The contract emits events for successful transfers and name updates.
The `hardhat.config.js` file is used for configuring the Hardhat development environment. It specifies the Solidity version and required libraries to deploy contracts on the hardhat node.


### Application Preview 


[![Transfer Preview](https://i.postimg.cc/gj4XVxjs/USE.png)](https://postimg.cc/gLX2dkvL)


## Technologies

[![forthebadge](https://forthebadge.com/images/badges/made-with-javascript.svg)](https://forthebadge.com)  ![Ethereum](https://img.shields.io/badge/Ethereum-3C3C3D?style=for-the-badge&logo=Ethereum&logoColor=white)  ![Web3.js](https://img.shields.io/badge/web3.js-F16822?style=for-the-badge&logo=web3.js&logoColor=white)  ![Solidity](https://img.shields.io/badge/Solidity-%23363636.svg?style=for-the-badge&logo=solidity&logoColor=white)  

## Installation ⬇️

1. Download or clone the project.
2. Install the dependencies by running `npm install`.
3. Start the local blockchain using Hardhat by running `npx hardhat node`.
4. Open new terminal and deploy the Bank contract `npx hardhat run --network localhost scripts/deploy.js`.
5. Start the development server by running `npm run dev`.

### Setting RPC

1. Fill in the following details:
   - Network Name: hardhat-test-network
   - RPC URL: http://127.0.0.1:8545/
   - Chain ID: 31337
   - Currency Symbol: GO or ETH


### Add accounts using private keys by Hardhat
1. Select "Import Account" or "Import Account using Private Key" (depending on your version of MetaMask).
2. In the "Private Key" field, enter one of the private keys provided by Hardhat.
   - To access the list of private keys, open the terminal where you started the Hardhat local network.
   - The private keys are displayed as part of the accounts generated by Hardhat.
3. Click on "Import" to import the account into MetaMask.

## Usage 

1. After connecting MetaMask to the Hardhat local network, connect your wallet with the application
2. Click on Transfer Funds and fill in the recipient's address and the amount you want to transfer.
3. Click the "Transfer" button to initiate the transaction.
4. Confirm the transaction in MetaMask.
5. The transaction details will be logged to the console, and the account balance will be updated.


