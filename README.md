Compiling your contracts: `truffle compile`  
Running tests: `truffle test`  
Deploy contracts: `truffle migrate --network rinkeby`  

In order to run client application for supply chain decentralized application run command  
`npm run dev`  

Application will run at `localhost:3000`  

deployed contract address: 0x90423749ED9fe1957E312f4087A15152ceC26Dff  
in transaction: 0xac46c8e681aa14edb52265c3fd184373b8d030ea48dab94a29b5836fb79ae79e  

This repository contains UML files which describe logic behind deployed contract and is located in UML folder.  

Truffle v5.3.10 (core: 5.3.10)   - used for compiling contracts, running tests and deployment on ethereum node  
Solidity - 0.8.0 (solc-js)   - programing language in which smart contracts are written  
Node v14.16.0   - javascript runtime environment to handle client  
Web3.js v1.3.6  - lets our application interact with ethereum node  

Third party Libraries:   
truffle-hdwallet-provider version: ^1.0.17  - lets us sign transactions and enables contract deployment to ethereum node  
