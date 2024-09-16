# MyToken Solidity Project

A simple ERC20-like token implementation with mint and burn functionalities.

## Description

The MyToken Solidity contract defines a basic Ethereum token with the name "HELLO" and symbol "HE". It keeps track of the token supply and balances of each address through a mapping. The contract has two primary functions:

1. **Mint**: Adds new tokens to a specified address, increasing the total supply.
2. **Burn**: Removes tokens from a specified address, decreasing the total supply.

Both minting and burning operations include safety checks to prevent actions involving the zero address or insufficient balances.

## Getting Started

### Installing

1. Clone the repository from [GitHub](https://github.com/example-repo).
2. Make sure you have Solidity 0.8.18 or higher installed.
3. Use any Ethereum development environment like Remix, Hardhat, or Truffle to compile and deploy the contract.

### Modifications

* Modify `tokenName` and `tokenAbbrv` if you need different token details.
* Customize the supply behavior in the `mint` and `burn` functions as needed.

### Executing program

1. Compile the contract using any Solidity compiler or IDE like Remix.
2. Deploy the contract on an Ethereum testnet or local development chain.

```bash
# To deploy using Hardhat
npx hardhat run scripts/deploy.js --network goerli
```

3. Interact with the contract:
   * Call the `mint` function to create tokens.
   * Call the `burn` function to reduce token supply.

```solidity
// Example of minting tokens
mint(0xYourAddressHere, 100);

// Example of burning tokens
burn(0xYourAddressHere, 50);
```

## Help

For common issues:

* Ensure you're using the correct Ethereum address.
* Verify the balance before calling the `burn` function.

```bash
# To get help with Solidity functions
solidity --help
```

## Authors

Dominique Pizzie  
[@DomPizzie](https://twitter.com/dompizzie)

## License

This project is licensed under the MIT License - see the LICENSE.md file for details.
