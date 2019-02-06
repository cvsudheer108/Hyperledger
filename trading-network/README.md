## Hyperledger Fabric & Composer "trading-network" example

This repository defines the source code for a Hyperledger Composer Business Network Definition. The network models a consortium of engine manufacturers and merchants which trace the production, sale and installation of car engines into cars of end customers.

## How to use?

Pre-requisites:

1. Install [pre-requisites for Hyperledger Fabric](http://hyperledger-fabric.readthedocs.io/en/latest/prereqs.html)
2. Install [pre-requisites for Hyperledger Composer](https://hyperledger.github.io/composer/installing/installing-prereqs)
3. Install [Composer and its (dev) tools](https://hyperledger.github.io/composer/installing/development-tools)

The source code is implemented in JavaScript ES6 so it can make use of nice language features such as `async` and `await`, spread/destruct operators and so on.

Working with the repo:

1. Install dependencies and dev-dependencies: `npm install`
2. Run ESlint: `npm run lint`
3. Run unit tests: `npm test`
4. Compile this repository, install network, start netowrk, inport card and ping the network as given in the npm commands in the .json file


For more information on Fabric and Composer and how to deploy `.bna` files to Fabric Networks, please read their development and operations documentation.
