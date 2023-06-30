# Metacrafters-Solidity-course-end-Assessment


## MyToken Contract
The MyToken contract is a basic implementation of a token on the Ethereum blockchain. It allows for
the creation, transfer, and destruction of tokens.

## Features
- Token Name: The contract stores the name of the token as a string.
- Token Abbreviation: The contract stores the abbreviation or symbol of the token as a string.
- Total Supply: The contract keeps track of the total supply of tokens.
- Balances: The contract maintains a mapping of addresses to their token balances.
  
## Functions
- Constructor: The constructor function initializes the token with a name, abbreviation, and initial
total supply. It assigns all the initial tokens to the contract creator's address.
- Mint: The mint function allows for the creation of new tokens. It increases the total supply and
adds the specified number of tokens to the balance of the specified address.
- Burn: The burn function allows for the destruction of tokens. It decreases the total supply and
subtracts the specified number of tokens from the balance of the specified address.

## License
This code is licensed under the MIT license.

## Usage
To use this contract, follow these steps:
1. Deploy the contract to the Ethereum blockchain.
2. Call the constructor function with the desired token name, abbreviation, and initial total supply.
3. Use the
mint
function to create new tokens. Specify the recipient's address and the number of tokens to be
created.
4. Use the
burn
function to destroy tokens. Specify the owner's address and the number of tokens to be destroyed.
5. Use the
Adresstobalance
mapping to check the balance of a specific address.
Note: The contract assumes that the deployer of the contract is the initial owner of all tokens.
