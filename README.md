# **[EmeraldCoin](https://www.linkedin.com/in/mdnabeelemerald/)**.  

> 🔒 **For interview and portfolio purposes only. All rights reserved.**
> This project is publicly visible but **not licensed** for reuse, modification, or distribution without explicit written permission.

A minimal blockchain implementation in Rust, built to demonstrate core concepts such as:
- Wallet creation & key management
- UTXO-based balances
- Block mining with proof-of-work
- Transaction validation

---

## 🚀 Quick Start

### Requirements
- [Rust](https://www.rust-lang.org/tools/install)

### Run
```bash
cargo run


emeraldcoin 0.1.0

USAGE:
    emeraldcoin <SUBCOMMAND>

FLAGS:
    -h, --help       Prints help information
    -V, --version    Prints version information

SUBCOMMANDS:
    createblockchain    Create a new blockchain
    createwallet        Create a new wallet
    getbalance          Get the wallet balance of the target address
    help                Prints this message or the help of the given subcommand(s)
    listaddresses       Print local wallet addresses
    printchain          Print all blocks in the blockchain
    reindexutxo         Rebuild UTXO index set
    send                Send coins and optionally mine a new block
    startnode           Start a node


    ## 📜 License
    All rights reserved. See [`LICENSE`](./LICENSE) for details.
