# Secure Aadhaar Composer Application
This repository contains the code for the composer application. This smart contract generated from this code defines the behaviour of the blockchain.

## File Structure

* `models/org.alpha.secureaadhaar`: Contains the model definitions
* `logic.js`: Contains the business logic for the transactions.
* `permissions.acl`: Contains the access control rules.
* `queries.qry`: Contains the query definitions.

## Running the application

The application can be run by either deploying it to a fabric blockchain network or using the `composer-playground`.

For running using either of these methods, one needs to create the business network definition file.
```bash
composer archive create -t dir -n .
```

This generates a `secure-aadhaar.bna` file which can then be deployed to:

* A Hyperledger Fabric Blockchain using [this guide](https://hyperledger.github.io/composer/tutorials/deploy-to-fabric-single-org)
* Composer Playground using [this guide](https://hyperledger.github.io/composer/tutorials/playground-tutorial)

## Prequisites
You need to have Hyperledger Composer and Hyperledger Fabric installed in order to run this application. Instructions for the same can be found [here](https://hyperledger.github.io/composer/installing/development-tools.html).