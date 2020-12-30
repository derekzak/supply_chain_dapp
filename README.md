# Supply chain & data auditing

This repository containts an Ethereum DApp that demonstrates a Supply Chain flow between a Seller and Buyer. The user story is similar to any commonly used supply chain process. A Seller can add items to the inventory system stored in the blockchain. A Buyer can purchase such items from the inventory system. Additionally a Seller can mark an item as Shipped, and similarly a Buyer can mark an item as Received.

The DApp User Interface when running should look like...

![truffle test](images/ftc_product_overview.png)

![truffle test](images/ftc_farm_details.png)

![truffle test](images/ftc_product_details.png)

![truffle test](images/ftc_transaction_history.png)

## UML Diagrams

### Activity Diagram

![Activity Diagram](./uml_diagrams/Supply%20Chain%20Dapp%20-%20Activity%20Diagram.png)

### Sequence Diagram

![Sequence Diagram](./uml_diagrams/Supply%20Chain%20Dapp%20-%20Sequence%20Diagram.png)

### State Diagram

![State Diagram](./uml_diagrams/Supply%20Chain%20Dapp%20-%20State%20Diagram.png)

### Class Diagram

![Class Diagram](./uml_diagrams/Supply%20Chain%20Dapp%20-%20Class%20Diagram.png)

## Libraries Used

* Node v10.18.1
* Truffle v5.1.56
* Solidity v0.5.16
* Web3 v1.3.1
* Truffle Assertions v0.9.2
* Lite Server v2.6.1

## IPFS

IPFS was not used for this project.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

Please make sure you've already installed ganache-cli, Truffle and enabled MetaMask extension in your browser.

```
Give examples (to be clarified)
```

### Installing

A step by step series of examples that tell you have to get a development env running

Clone this repository:

```
git clone https://github.com/udacity/nd1309/tree/master/course-5/project-6
```

Change directory to ```project-6``` folder and install all requisite npm packages (as listed in ```package.json```):

```
cd project-6
npm install
```

Launch Ganache:

```
ganache-cli -m "spirit supply whale amount human item harsh scare congress discover talent hamster"
```

Your terminal should look something like this:

![truffle test](images/ganache-cli.png)

In a separate terminal window, Compile smart contracts:

```
truffle compile
```

Your terminal should look something like this:

![truffle test](images/truffle_compile.png)

This will create the smart contract artifacts in folder ```build\contracts```.

Migrate smart contracts to the locally running blockchain, ganache-cli:

```
truffle migrate
```

Your terminal should look something like this:

![truffle test](images/truffle_migrate.png)

Test smart contracts:

```
truffle test
```

All 10 tests should pass.

![truffle test](images/truffle_test.png)

In a separate terminal window, launch the DApp:

```
npm run dev
```

## Built With

* [Ethereum](https://www.ethereum.org/) - Ethereum is a decentralized platform that runs smart contracts
* [IPFS](https://ipfs.io/) - IPFS is the Distributed Web | A peer-to-peer hypermedia protocol
to make the web faster, safer, and more open.
* [Truffle Framework](http://truffleframework.com/) - Truffle is the most popular development framework for Ethereum with a mission to make your life a whole lot easier.


## Authors

This Dapp application was developed as part of the Blockchain Nanodegree with [Udacity](http://www.udacity.com).
See also the list of [contributors](https://https://github.com/derekzak/supply_chain_dapp/graphs/contributors) who participated in this project.

## Acknowledgments

* Solidity
* Ganache
* Truffle
* IPFS

### License

This Dapp application is released under [AGPL](http://www.gnu.org/licenses/agpl-3.0-standalone.html)
