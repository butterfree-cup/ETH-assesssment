# MyToken Solidity Smart Contract
 This serves as an entry for the ETH Beginner course assesssement. The source code demonstrates how a cryptocurrency token is minted and burned in a simple way.

# Description
This Solidity smart contract, named "MyToken," is designed to demonstrate the creation and management of a basic cryptocurrency token. It includes functions for minting (creating) and burning (destroying) tokens, as well as storing token details.

# Content Overview
1. Token Details:
    - The contract has public variables to store essential information about the cryptocurrency token:
        - tokenName: The name of the token, set to "Tom's World."
        - tokenAbbrev: The abbreviation or symbol of the token, set to "TWRLD."
        - totalSupply: The total supply of the token, initially set to 0.

2. Balances Mapping:
    - The contract uses a mapping to associate Ethereum addresses with their respective token balances:
        - balances: Maps Ethereum addresses (type address) to token balances (type uint).

3. Mint Function:
    - The mint function allows the creation of new tokens by specifying an Ethereum address and a value.
    - It increases the total token supply by the specified value and balance of the specified Ethereum address by the same value.

4. Burn Function:
    - The burn function enables the destruction of tokens by specifying an Ethereum address and a value.
    - It deducts the specified value from the total token supply and from the balance of the specified Ethereum address.
    - To prevent unauthorized token destruction, the burn function includes a conditional check to ensure that the balance of the sender (specified Ethereum address) is greater than or equal to the amount to be burned.

# Getting Started
## Executing the program
- This code was executed on Remix Online IDE.
- Compile the eth-assessment.sol file and deploy it using the Deploy & Run Transactions tab of the Remix IDE.
- The accounts given on this field can be used as the address input for the mint and burn functions.

  ![image](https://github.com/butterfree-cup/ETH-assesssment/assets/113696831/9afd23e1-3649-48b0-8f73-057a7fe47eda)

# Authors
Deanne Joy R. Santos

