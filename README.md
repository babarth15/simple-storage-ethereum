# SimpleStorage — Ethereum Smart Contract

This repository contains a simple Solidity smart contract deployed and verified on Ethereum mainnet.

## Contract Details
- **Network:** Ethereum Mainnet
- **Contract Address:** 0x2e53481db8ec56D8D461E4dF9210e98bA1DD6B88
- **Etherscan:** https://etherscan.io/address/0x2e53481db8ec56D8D461E4dF9210e98bA1DD6B88
- **Deployment Tooling:** Remix IDE + MetaMask
- **Solidity Version:** v0.8.31+commit.fd3a2265
- **Verified:** Yes

## Description
`SimpleStorage` allows anyone to store and retrieve a single unsigned integer on-chain.
This project demonstrates end-to-end smart contract development:
- Writing Solidity
- Deploying to Ethereum mainnet
- Verifying source code on Etherscan

## Usage
Public variable `storedValue` can be read directly via Etherscan or via Web3 clients.
The `set(uint256)` function updates the stored value.

## License
MIT
