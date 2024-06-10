 MyToken Smart Contract

This is a basic smart contract called MyToken that implements a custom token with minting and burning functions.

## Requirements

1. Public variables store token details (Token Name, Token Abbreviation, Total Supply).
2. Mapping of addresses to balances is used (address => uint).
3. Mint function increases total supply by a specified value and increases the balance of the sender's address.
4. Burn function decreases total supply and sender's balance by a specified value.
5. Burn function includes conditionals to check if the sender's balance is sufficient for burning.

## Usage

1. Deploy the MyToken contract on a compatible blockchain network.
2. Use the mint function to create new tokens and distribute them to addresses.
3. Use the burn function to destroy tokens and reduce the total supply.

