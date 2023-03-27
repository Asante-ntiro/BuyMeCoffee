# BuyMeCoffee
A simple smart contract that allows people to gift money along with a message.

## Features
- Accepts gift along with message.
- Maintains a record of all the gifts sent.
- Only owner can withdraw balance from the contract.

## Usage
### Dependencies
This contract depends on the following external libraries:
- Foundry
- solidity ^0.8.13
- @openzeppelin/contracts/token/ERC721/IERC721.sol
- @openzeppelin/contracts/token/ERC20/IERC20.sol

### Deployment
- Compile the contract with the required dependencies
- Deploy the contract to the Ethereum network

### Interacting with the Contract
Gift
Sends a gift along with a message to the contract.

### Parameters
- name (string) - The name of the person sending the gift
- message (string) - The message to be sent along with the gift
