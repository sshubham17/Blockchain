# Blockchain
Blockchain_project: Property_Records_Registarion

Prerequisite:

1. Node Package Manager, or NPM, which
   comes with Node.js.You can see if you have node already installed by
   going to your terminal and typing:
   $ node -v

2. Secondly we need to install Angular by typing the below :
 
   $ npm install @angular/cli

3. Next we need to install the node modules :
  
	$ npm install

  
 4. The next dependency is the Truffle Framework, which allows us to build
    decentralized applications on the Ethereum blockchain. It provides a suite
    of tools that allow us to write smart contacts with the Solidity program-
   ming language. It also enables us to test our smart contracts and deploy
   them to the blockchain. It also gives us a place to develop our client-side
   application.
   You can install Truffle with NPM in your command line like this:
   $ npm install -g truffle
5. The next dependency is Ganache. You can install it by typing the below
   in your terminal :
   $ npm install -g ganache-cli
   It will give us 10 external accounts with addresses on our local Ethereum
   blockchain. Each account is preloaded with 100 fake ether.
6. The next dependency is the Metamask extension for browser. In order
   to use the blockchain, we must connect to it. We’ll have to install a spe-
   cial browser extension in order to use the Ethereum block chain. 

How to RUN:
 1. First, run the ganache by typing “ganache-cli” in your terminal.
 2. Now let’s compile and run our migrations from the command line like this:
    $ truffle compile
    $ truffle migrate

 3. Copy the contract address to “web3.service.ts”.
 4. Open the terminal the Dapp folder and run it by typing “ng serve”. Open
    the browser and the dapp will be running in http://localhost:4200 by default.
 
