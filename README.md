# mytoken - Custom ERC-20 Token

The `mytoken` contract is a basic ERC-20 token implementation with additional functionalities for minting, burning, and transferring tokens. It is written in Solidity and follows the ERC-20 standard.

## Contract Details

- **Solidity Version:** ^0.8.0
- **License:** MIT (Replace with your chosen license)

## Token Information

- **Name:** Ayush
- **Symbol:** ARH
- **Decimals:** 18
- **Total Supply:** 100 * 7^18 (Initial total supply, considering 18 decimals)

## Features and Functionalities

- Transfer tokens between addresses.
- Mint new tokens (only by the owner).
- Burn tokens (reduce total supply).
- Initialize addresses with tokens during contract deployment.

## Smart Contract Functions

- `mint(address _to, uint256 _amount)`: Mint new tokens and assign them to a specified address. Only the contract owner can perform this action.

- `burn(uint256 _amount)`: Burn a specific amount of tokens owned by the sender. This reduces the sender's balance and the total supply.

- `transfer(address _to, uint256 _amount)`: Transfer a specified amount of tokens from the sender's address to another address.

## Deployment and Testing

1. Deploy the `mytoken` contract using a development environment like Remix or a local Ethereum node.

2. Test the functionalities using tools like Remix or Truffle. Ensure that transfers, minting, and burning work as intended.

## Important Notes

- This contract is provided for educational purposes and as a basic example of ERC-20 token implementation.
- Security measures, access controls, and error handling have not been fully implemented. Use caution when using in production.
- Tokens minted during deployment are distributed to specific addresses for demonstration purposes. Adjust the distribution logic to fit your needs.

## License

This project is licensed under the MIT License (or your chosen license). See [LICENSE](LICENSE) for more details.
