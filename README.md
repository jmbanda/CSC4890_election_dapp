# Election - DAPP Tutorial
Build your first decentralized application, or Dapp, on the Ethereum Network with this tutorial!

This code is modified from: https://youtu.be/3681ZYbDSSk
In this version you can use Solidity 0.5.0 and the latest version of MetaMask

Follow the steps below to download, install, and run this project.

## Dependencies
Install these prerequisites:
- NPM: https://nodejs.org
- Truffle: https://github.com/trufflesuite/truffle
- Ganache: http://truffleframework.com/ganache/
- Metamask: https://metamask.io/

NOTE: You need to have Metamask Installed, configured and unlocked for this to work. Be sure to import a few accounts to play with. 

## Step 1. Clone the project
`git clone https://github.com/jmbanda/CSC4890_election_dapp`

## Step 2. Install dependencies
```
$ cd election
$ npm install
```
## Step 3. Start Ganache
Open the Ganache GUI client that you downloaded and installed. This will start your local blockchain instance. See free video tutorial for full explanation.


## Step 4. Compile & Deploy Election Smart Contract
`$ truffle migrate --reset`
You must migrate the election smart contract each time your restart ganache.

## Step 6. Run the Front End Application
`$ npm run dev`
Visit this URL in your browser: http://localhost:3000

