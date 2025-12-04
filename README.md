# ERC-20-Token

# MyToken (MTK)

## Overview
MyToken is a simple ERC-20 compatible token built on Ethereum for learning purposes.

## Token Details
- **Name**: MyToken
- **Symbol**: MTK
- **Decimals**: 18
- **Total Supply**: 1,000,000 MTK

## Features
- ✅ Standard ERC-20 implementation
- ✅ Transfer tokens between addresses
- ✅ Approve and transferFrom functionality
- ✅ Event emission for transparency
- ✅ Balance tracking

## How to Deploy
1. Open RemixIDE: https://remix.ethereum.org  
2. Create a new file named `MyToken.sol`  
3. Paste the smart contract code  
4. Compile using Solidity 0.8.x  
5. Deploy the contract with your chosen total supply  

## How to Use

### Check Balance
```solidity
balanceOf(address) → returns uint256
```

### Transfer Tokens
```solidity
transfer(address to, uint256 amount) → returns bool
```

### Approve Spending
```solidity
approve(address spender, uint256 amount) → returns bool
```

### Transfer on Behalf
```solidity
transferFrom(address from, address to, uint256 amount) → returns bool
```
