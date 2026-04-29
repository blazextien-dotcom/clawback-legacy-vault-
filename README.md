# Title
Clawback Legacy Vault

# Description
Clawback Legacy Vault solves the problem of permanently lost crypto assets in non-custodial wallets. When users lose access to their private keys or pass away, their XLM/USDC are locked forever with no recovery mechanism. This project uses a Soroban smart contract on Stellar to implement an automatic inheritance system based on inactivity. The owner deposits assets, sets a beneficiary and timeout, and maintains control through periodic ping transactions. If inactivity exceeds the timeout and grace period, the beneficiary can claim all assets in a single transaction with permanent finality. The owner can cancel and reclaim funds before the claim stage. The system operates fully on-chain and evaluates inactivity rather than verifying death.

# Project Vision
To provide a simple and secure on-chain inheritance solution for crypto assets, ensuring funds are not permanently lost while maintaining full ownership control without intermediaries.

# Features
- Deposit XLM/USDC into the smart contract  
- Set beneficiary and inactivity timeout  
- Periodic ping to confirm activity  
- Owner can cancel and withdraw funds before claim  
- Automatic transition to claimable state after inactivity  
- Single transaction claim by beneficiary  
- Fully on-chain execution  

# Contract
https://stellar.expert/explorer/testnet/contract/CAEMPURHF44WYGEZVXYLEO5CMECVFJBR24OBYTNL3Q2JXWUZCFSNNGX7?filter=history  

Contract's screenshot:
<img width="1906" height="900" alt="image" src="https://github.com/user-attachments/assets/64b3483f-22de-4268-bd23-0e207fc2f707" />


# Future scopes
- Support multiple beneficiaries  
- Build simple web UI / frontend  
- Add notification system before timeout  
- Enhance security and audit  
- Multi-token support  

# Profile
Name: Tien  

Skills:
- Blockchain fundamentals  
- Soroban smart contract development  
- Rust programming  
