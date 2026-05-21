# Blockchain Notetaking App

Rara Sekiguchi,  Mohammad Kazemi  


This is a simple decentralized app (dApp) for blockchain course. It lets you connect your MetaMask wallet, write notes, and save them permanently to a smart contract. You can also view all your saved notes right on the main dashboard.

## Tech Stack
* **Smart Contract:** Solidity
* **Frontend:** HTML, Vanilla JavaScript, CSS
* **Web3 Library:** Ethers.js

## How to test it out
To get this running, you can't just double-click the HTML files. MetaMask blocks standard `file://` protocols for security reasons. Here is the easy way to get it running:

1. **Get MetaMask:** Make sure you have the MetaMask browser extension installed.
2. **Run a Local Server:** Open this project folder in a code editor (like VS Code) and use an extension like **Live Server** to host it locally. 
3. **Check the Network:** Make sure your MetaMask is connected to the right test network (like Sepolia or your local Hardhat node) where the smart contract is actually deployed.
4. **Open the App:** Go to the local server address (usually `http://127.0.0.1:5500/index.html`) in your browser.
5. **Connect and Play:** Click "Connect wallet" to log in, add a note, and watch it show up on your dashboard once the blockchain confirms the transaction!

## Core Files
* `Notes.sol`: The smart contract handling the logic and storage.
* `index.html`: The main dashboard where you connect your wallet and view your notes.
* `add.html`: The page where you write and push new notes to the blockchain.
