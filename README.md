# Random raffle contract

## About

This code is to create a proveably random lottery contract lottery.

## What do we want it to do?
1. Users can enter by buying a ticket
    1. The ticket fees will go to the winner during the draw
2. After x period of time the draw will automatically pick a winner
    1. This will occur programatically
3. We will utilise Chainlink VRF & Chainlink automation
    1. Chainlink VRF = Randomness
    2. Chainlink automation = Time based trigger

## Tests!

1. Writw some deploy scripts
2. Write our tests
    1. Work on a local chain
    2. Forked testnet
    3. Forked mainnet

## For those not familiar with the Foundry Dev environment

Foundry consists of:

-   **Forge**: Ethereum testing framework (like Truffle, Hardhat and DappTools).
-   **Cast**: Swiss army knife for interacting with EVM smart contracts, sending transactions and getting chain data.
-   **Anvil**: Local Ethereum node, akin to Ganache, Hardhat Network.
-   **Chisel**: Fast, utilitarian, and verbose solidity REPL.

## Documentation

https://book.getfoundry.sh/

## Usage

### Build

```shell
$ forge build
```

### Test

```shell
$ forge test
```

### Format

```shell
$ forge fmt
```

### Gas Snapshots

```shell
$ forge snapshot
```

### Anvil

This will simulate a local chain and provide virtual wallet addresses with Eth Sepolia

```shell
$ anvil
```

### Deploy

```shell
$ forge script script/Counter.s.sol:CounterScript --rpc-url <your_rpc_url> --private-key <your_private_key>
```

### Cast

```shell
$ cast <subcommand>
```

### Help

```shell
$ forge --help
$ anvil --help
$ cast --help
```

### Running foundry

Once Foundry is installed and you are ready to go, run the environment using:
```bash
$ foundryup
```

This will set the environment up and will also pull any updates.