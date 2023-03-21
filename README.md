# Introduction
This is a Land Registry project that is build on Hyperledger Fabric - Private Blockchain network.

# Description

It is a Full Stack Project built using React JS, Node JS, MongoDB and Hyperledger Fabric. Primarily, three type of organizations logins are defined in the blockchain network : SRO, Revenue and Bank. It allows SRO user to add, edit and update land record data in blockchain. It also alows to transfer the land and delete the land record from Hyperledger fabric world state. Bank user can incorporate mortgage on a land in blockchain which prevent the land transfer. Revenue user will update the land taxation details. 

# Technologies 
* React JS: 18.2
* Fabric network : 2.2.8
* MUI
* React-Bootstrap
* Sweetalert
* Express JS
* Node JS
* Mongo DB
* Mongoose

# Setup

Fabric network need to made up for running this project. 

Front end can be run using below commands :
```
cd landRegistryFrontend
npm install
npm start
```

Back end can be run using below commands :
```
cd landRegistryBackend
npm install
node index.js
```
