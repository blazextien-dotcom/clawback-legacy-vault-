# Title
Legacy Vault

# Description
Clawback Legacy Vault addresses the problem of permanently lost crypto assets when users lose access to their private keys or pass away, as non-custodial systems provide no recovery mechanism or third-party intervention. This project uses a Soroban smart contract on Stellar to implement an automatic inheritance mechanism based on user inactivity: the owner deposits assets, sets a beneficiary and inactivity period, and maintains control through periodic ping transactions. If inactivity exceeds the defined timeout and grace period, the contract becomes claimable and the beneficiary can transfer all assets in a single transaction. The system operates entirely on-chain and evaluates inactivity rather than verifying death, ensuring a simple, secure, and trustless solution.

# Project Vision
The goal of this project is to provide a simple and secure on-chain inheritance mechanism for crypto assets, ensuring that funds are not permanently lost while maintaining full ownership control without relying on intermediaries.

# Features
- Deposit XLM/USDC into smart contract  
- Set beneficiary and inactivity timeout  
- Ping to confirm activity  
- Owner can cancel and withdraw funds before claim  
- Automatic claim after inactivity  
- Single transaction claim by beneficiary  
- Fully on-chain execution  

# Contract
https://stellar.expert/explorer/testnet/contract/CAEMPURHF44WYGEZVXYLEO5CMECVFJBR24OBYTNL3Q2JXWUZCFSNNGX7?filter=history
Contract's screenshot:

# Future scopes
- Support multiple beneficiaries  
- Add simple user interface (UI)  
- Add notification before timeout  
- Improve security mechanisms  

# Profile
Name: Tien 

Skills:
- Blockchain fundamentals  
- Soroban smart contract development  
- Rust programming  