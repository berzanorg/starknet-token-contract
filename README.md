# starknet-token-contract

## Environment Setup

Use [Dev Containers](https://code.visualstudio.com/docs/devcontainers/create-dev-container) to setup a development enviroment quickly.

Or install necessary tools manually by following the instructions in [`.devcontainer/Dockerfile`](/.devcontainer/Dockerfile).


## Developing

Build the project by running the command below.

```shell
scarb build
```

Declare the class hash of the contract by running the command below.

```shell
starkli declare target/dev/token_Token.contract_class.json
```

Deploy an instance of the contract by running the command below.

```shell
starkli deploy <CLASS_HASH> <CONSTRUCTORS...>
```

## License

[GNU GPLv3](https://choosealicense.com/licenses/gpl-3.0/)

Made with ❤️ by [**Berzan**](https://berzan.org).