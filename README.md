# Assignment 2

# Overview

This smart contract is for the WorldToken (PTK) cryptocurrency, written in Solidity. It includes functions for minting and burning tokens, as well as tracking the total supply and balances of addresses.

# Features

- tokenName: The name of the token, set to "WorldToken".
- tokenAbbrv: The abbreviation of the token, set to "PTK".
- totalSupply: The total supply of tokens, initialized to 0.
- balances: A mapping of addresses to their balances.

# Functions

- mint(address _address, uint _value): Increases the total supply and balance of a given address by the specified value.
- burn(address _address, uint _value): Decreases the total supply and balance of a given address by the specified value, if the address has sufficient balance.

# Usage

To use this contract, you can deploy it to a blockchain platform such as Ethereum or Binance Smart Chain. Once deployed, you can interact with the contract using a Web3 library or a wallet that supports smart contract interactions.

# Author

Yaismeen

