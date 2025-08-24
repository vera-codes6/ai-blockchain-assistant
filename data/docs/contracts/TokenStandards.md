# Ethereum Token Standards

## ERC-20

The most widely used token standard for fungible tokens.

### Key Functions

- **totalSupply()**: Returns the total token supply
- **balanceOf(address)**: Returns the account balance of an address
- **transfer(address, uint256)**: Transfers tokens to a specified address
- **transferFrom(address, address, uint256)**: Transfers tokens from one address to another
- **approve(address, uint256)**: Allows spender to withdraw from your account
- **allowance(address, address)**: Returns the amount which spender is allowed to withdraw

## ERC-721

Standard for non-fungible tokens (NFTs).

### Key Functions

- **balanceOf(address)**: Returns the number of NFTs owned by an address
- **ownerOf(uint256)**: Returns the owner of a specific NFT
- **safeTransferFrom(address, address, uint256)**: Transfers ownership of an NFT
- **approve(address, uint256)**: Grants permission to transfer a specific NFT
- **getApproved(uint256)**: Returns the approved address for a specific NFT
- **setApprovalForAll(address, bool)**: Enables or disables approval for a third party to manage all of the caller's NFTs
- **isApprovedForAll(address, address)**: Returns if an operator is approved by a given owner
