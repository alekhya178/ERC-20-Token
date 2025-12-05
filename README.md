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

## Screenshots

1.Compilation Success

![compilation](https://github.com/user-attachments/assets/e2361553-eb78-4bc9-97ab-44d8bedd61dd)

2.Deployment

![Deployment](https://github.com/user-attachments/assets/b99bf0e5-7a75-4293-8070-3f6735ae8774)

3.Token Info

![Token_info](https://github.com/user-attachments/assets/ce07788e-e7dd-4f58-9258-57b2cc4009c1)

4.Transfer Test- Senders Balance and Receivers Balance

![senders_balance](https://github.com/user-attachments/assets/f17fcb1e-186b-424a-848f-5817952279d6)


![receivers_balance](https://github.com/user-attachments/assets/3a6a34f3-c567-4dc9-9c3f-02b612647ac7)

5.Events - Approval

![approve](https://github.com/user-attachments/assets/915ab3c9-5340-4644-9bee-36fa8baf9396)



## Learning Outcomes

- How to write and deploy a smart contract in Solidity

- The core components of the ERC-20 token standard

- How balance tracking, allowances, and transfers work internally

- Using Remix IDE to compile, deploy, and test contracts

- The importance of validation checks and event emission

- How token decimals and total supply are represented on Ethereum

This project gave me a clear foundation in smart contract development and practical blockchain concepts.

