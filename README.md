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