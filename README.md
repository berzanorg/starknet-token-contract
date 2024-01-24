# Starknet Token Contract

This repository contains the source code of an ERC20 smart contract.

This project is licensed under [GPL](https://www.gnu.org/licenses/gpl-3.0.en.html).

I use [Cairo](https://www.cairo-lang.org), [Scarb](https://docs.swmansion.com/scarb) and [Starkli](https://book.starkli.rs/introduction) for developing the contract.

You can find detailed information about [Cairo](https://www.cairo-lang.org), [Scarb](https://docs.swmansion.com/scarb) and [Starkli](https://book.starkli.rs/introduction) below.

The source code of the smart contract is at https://github.com/BerzanOrg/starknet-token-contract.

## Cairo

Cairo is a programming language for writing provable programs.

Cairo is Rust-inspired, allowing developers to write [Starknet](https://www.starknet.io/en) smart contracts in a safe and convenient manner.

## Scarb

Scarb is the project management tool for the Cairo language. 

Scarb manages your dependencies, compiles your projects and works as an extensible platform assisting in development.

## Starkli

Starkli is a command line tool for interacting with [Starknet](https://www.starknet.io/en), powered by [starknet-rs](https://github.com/xJonathanLEI/starknet-rs).

Starkli allows you to query [Starknet](https://www.starknet.io/en) and make transactions with ease. It's fast, easy to install, and intuitive to use.

## Documentation

https://book.cairo-lang.org

https://docs.swmansion.com/scarb

https://book.starkli.rs/introduction

## Usage

### Build

```shell
$ scarb build
```

### Declare

```shell
$ starkli declare target/dev/token_Token.contract_class.json
```

### Deploy

```shell
$ starkli deploy <CLASS_HASH> <TOKEN_NAME> <TOKEN_SYMBOL> <TOKEN_SUPPLY> <TOKEN_RECIPIENT>
```

## Note

Built with love, sweat and tears by [Berzan](https://berzan.org).
