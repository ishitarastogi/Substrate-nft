# Substrate-nft

# Introducing Substrate Smart Contracts with Ink

ink!: Substrate’s smart contract language

Ink (or ink! as the name is commonly termed in documentation) is Parity’s solution to writing smart contracts for a Substrate based blockchain.

Substrate and Ink is built on top of Rust

# Installation

Rust : 

```
# install rust and update environment
curl https://sh.rustup.rs -sSf | sh
source ~/.cargo/env

# run rust updates and add WebAssembly target support
rustup update nightly
rustup target add wasm32-unknown-unknown --toolchain nightly
```

Substrate:

Install Substrate with the following command:

```
curl https://getsubstrate.io -sSf | bash
```
Wasm utilities:

Ink smart contracts are compiled into WebAssembly before uploaded onto a Substrate chain. In order to do this, we will need to install some utilities:

```
# Ubuntu
apt install binaryen
apt install wabt
cargo install pwasm-utils-cli --bin wasm-prune
```

Ink
```
cargo install --force --git https://github.com/paritytech/ink cargo-contract
```