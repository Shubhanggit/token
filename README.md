# token.sol
created token with silidity

This repository contains a simple Solidity smart contract for a basic token. The contract allows minting and burning of tokens, maintaining a record of total supply and individual balances.

EXPLAINATION OF CODE:

tokenName: Name of the token.
tokenAbbrv: Abbreviation of the token.
totalSupply: Total supply of the token.

balances: Maps addresses to their token balances.

mint: Increases total supply and the balance of a specified address.
burn: Decreases total supply and the balance of a specified address, with checks for sufficient balance.

How to Use:

Compile and Deploy:
Use a Solidity compiler or an IDE like Remix to compile and deploy the contract.

Interact with the Contract:
Use the mint and burn functions to manage token supply and balances.
