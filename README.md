# Pet Shop Tutorial

This is a DApp Demo - an adoption tracking system for a pet shop!

## Setting up the development environment

```bash
$ npm install -g truffle
$ npm install -g ganache-cli
```

## Directory structure

The default Truffle project directory structure contains the following:

- `contracts/`: Contains the Solidity source files for our smart contracts. There is an important contract in here called Migrations.sol, which we'll talk about later.

- `migrations/`: Truffle uses a migration system to handle smart contract deployments. A migration is an additional special smart contract that keeps track of changes.

- `test/`: Contains both JavaScript and Solidity tests for our smart contracts.

- `truffle.js`: Truffle configuration file.

> `src/`: the directory for website.

## How to run

You should launch `Ganache` app, or execute `ganache-cli -p 7545 -i 5777` in terminal before.

```bash
$ cd [project-directory]
$ npm install      # install Dependent libraries
$ truffle compile  # compile contracts
$ truffle migrate  # deploy contracts to network
$ truffle test     # do contracts test
$ npm run dev      # serves the front-end on http://localhost:3000
```

## License

MIT