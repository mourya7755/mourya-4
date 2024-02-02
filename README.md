# SubstanceToken 


## Description

`SubstanceToken` is an Ethereum-based ERC-20 token that represents ownership of substances such as IRON, STEEL, and ALUMINIUM. Users can mint, burn, transfer, and redeem these substances within the contract.

## Features

- Minting: The owner can mint new tokens and distribute them to designated addresses.
- Burning: Users can burn their tokens, reducing the overall supply.
- Transferring: Users can transfer tokens to other addresses.
- Substance Redemption: Users can redeem specific substances by burning the required amount of tokens.

## Substances and Costs

- IRON: 100 tokens
- STEEL: 120 tokens
- ALUMINIUM: 150 tokens

## Contract Functions

### `mint(address to, uint256 no_of_tokens)`

Mint a specified number of tokens and assign them to the given address.

### `burn(uint256 no_of_tokens)`

Burn a specified number of tokens, reducing the total supply.

### `redeemSubstance(uint8 substanceNumber)`

Redeem a substance by burning the corresponding amount of tokens. The substances are represented by the numbers 1, 2, and 3, corresponding to IRON, STEEL, and ALUMINIUM, respectively.

### `transfer_(address recipient, uint256 no_of_tokens)`

Transfer a specified number of tokens to another address.

## Usage

1. Deploy the `SubstanceToken` contract on the Ethereum blockchain.
2. Mint tokens using the `mint` function.
3. Users can burn tokens, transfer them, or redeem substances using the provided functions.

## License Information

This project is licensed under the MIT License - see the [LICENSE](./LICENSE) file for details.

## Author 

Mourya 

mourya7795@gmail.com
