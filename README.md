# ⚡ Solidity-Foundry-FundWithdraw

<div align="center">

[![GitHub stars](https://img.shields.io/github/stars/MBoreham/Solidity-Foundry-FundWithdraw?style=for-the-badge)](https://github.com/MBoreham/Solidity-Foundry-FundWithdraw/stargazers)

[![GitHub forks](https://img.shields.io/github/forks/MBoreham/Solidity-Foundry-FundWithdraw?style=for-the-badge)](https://github.com/MBoreham/Solidity-Foundry-FundWithdraw/network)

**A simple Ethereum contract for managing a fund with deposit and withdrawal functionalities, built using Solidity and Foundry.**

</div>

## 📖 Overview

This project implements a basic Ethereum smart contract using Solidity. The contract allows users to deposit and withdraw Ether (ETH) from a central fund.  It's designed for educational purposes and demonstrates fundamental Solidity concepts within the Foundry testing framework.

## ✨ Features

- **Fund Deposit:** Users can deposit ETH into the contract's fund.
- **Fund Withdrawal:** Owner can withdraw ETH from the contract's fund.  (Further access controls would be needed in a production environment).

## 🛠️ Tech Stack

- **Solidity:** Smart contract language.
- **Foundry:**  Testing and development environment for Solidity contracts.

## 🚀 Quick Start

### Prerequisites

- Foundry:  Ensure Foundry is installed on your system.  Follow the instructions at [https://book.getfoundry.sh/getting-started/installation](https://book.getfoundry.sh/getting-started/installation).
- Node.js (if using the Makefile for additional tasks)


### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/MBoreham/Solidity-Foundry-FundWithdraw.git
   cd Solidity-Foundry-FundWithdraw
   ```

2. **Install dependencies (optional - only if using Makefile):**
   This repository primarily uses Foundry's built-in dependency management, so this step is optional if you're only working with Foundry directly.  The Makefile may require some Node.js tools.

3. **Compile and Test:**
   ```bash
   forge build
   forge test
   ```

## 📁 Project Structure

```
Solidity-Foundry-FundWithdraw/
├── Makefile             # (Optional) Makefile for various tasks.
├── foundry.toml         # Foundry configuration file.
├── lib/                 # Library files (currently empty).
├── script/              # Scripts directory (currently empty).
├── src/                 # Source code directory.
│   └── FundWithdraw.sol # Main Solidity contract file.
├── test/                # Test contracts and scripts.
└── README.md            # This file.
```


## ⚙️ Configuration

The contract itself does not have extensive configuration options.  The `foundry.toml` file contains settings for Foundry's build process and testing environment.

## 🧪 Testing

Foundry provides the testing framework. The `forge test` command executes all tests within the `test` directory.

```bash
forge test
```

## 📄 License

This project is licensed under the [MIT License](LICENSE).


---

<div align="center">

**⭐ Star this repo if you find it helpful!**

</div>



## Foundry

**Foundry is a blazing fast, portable and modular toolkit for Ethereum application development written in Rust.**

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
