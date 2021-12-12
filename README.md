# eth-todo-list

-   Blockchain Todo App Tutorial Powered by Ethereum Smart Contracts

## Prerequisite

-   Nodejs
-   Truffle: A world class development environment, testing framework and asset pipeline for blockchains using the Ethereum Virtual Machine (EVM), aiming to make life as a developer easier.
-   Ganache: A personal blockchain for Ethereum development you can use to deploy contracts, develop your applications, and run tests.

## To Set up the Project

```bash
# Install Truffle in globally
$ npm install -g truffle@5.0.2

# Install Ganache
$ brew install --cask ganache

# Setup the Project
$ truffle init

# Compile Contracts
$ truffle Compile

# Deploy Smart Contracts to Blockchain
$ truffle migrate

# Check the Smart Contracts in Truffle Console
$ truffle console

$ todoList = await TodoList.deployed()
$ todoList.address
'0x4C5a2E7F9690c9DdB0f3F2Ab4cE2C122Cd6D6F98'

$ todoList.taskCount()
BN { negative: 0, words: [ 0, <1 empty item> ], length: 1, red: null }

$ taskCount = await todoList.taskCount()
$ taskCount.toNumber()
0
```
