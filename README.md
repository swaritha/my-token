MyToken (MTK) 
A Simple ERC-20 Token for Learning & Blockchain Development
Overview 
MyToken (MTK) is a custom ERC-20 compatible token deployed on Ethereum using Solidity. 
This project demonstrates essential token mechanics such as transferring, approving spenders, and 
enforcing balance + allowance rules. 
It is built entirely for hands-on learning and understanding decentralized token standards. 
# MyToken (MTK) 
## Overview 
MyToken is a simple ERC-20 compatible token built on Ethereum for learning purposes. 
## Token Details - **Name**: MyToken - **Symbol**: MTK - **Decimals**: 18 - **Total Supply**: 1,000,000 MTK 
## Features -    -    -    -    -    
Standard ERC-20 implementation 
Transfer tokens between addresses 
Approve and transferFrom functionality 
Event emission for transparency 
Balance tracking 
## How to Deploy 
1.  Open  Remix IDE 
2 Create a new file named MyToken.sol 
3  Paste the smart contract code 
4 Select Solidity 0.8.x compiler & compile 
5 Go to Deploy & Run Transactions 
6 Choose JavaScript VM 
7 Enter constructor value 
8 Click Deploy 
## How to Use 
Check Balance 
balanceOf(address) 
Transfer Tokens 
transfer(receiverAddress, 1000000000000000000) // 1 token 
Approve Spending for Another Account 
approve(spenderAddress, 1000000000000000000) // Allow 1 token 
Spend Tokens on Behalf (transferFrom) 
transferFrom(fromAddress, toAddress, 1000000000000000000
