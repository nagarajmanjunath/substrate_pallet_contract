# Substrate-pallet-contract

The node template with pallet_contract which is built on top of polkadot substrate blockchain.

## Prerequisite

- [Git](https://git-scm.com/downloads)

- [Rust](https://www.rust-lang.org)

### Compiling the code

- Follow these steps to compile and build node-template:

```bash
git clone https://github.com/nagarajmanjunath/substrate_pallet_contract.git

cd substrate_pallet_contract

cargo build --release

```

This will be compile `node-template` binary in your machine.
Make sure node template is properly compiled in your machine: ` ./target/release/node-template`

- Run the Node Locally in development mode.

```
 ./target/debug/node-template --dev
```

Note: Its in the development mode, which run on aura and grandpa consensus.
