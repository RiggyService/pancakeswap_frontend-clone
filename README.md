# 🥞 Pancake Frontend

[[ContactUs]](https://trustbusiness.web.app)

This project contains the main features of the pancake application.

## Development


### Install dependencies

```bash
npm install
```


### Usage (using Truffle)

Open the Truffle console

```bash
npm run truffle:console
```


#### Compile

```bash
npm run truffle:compile
```


#### Test

```bash
npm run truffle:test
```


### Usage (using Hardhat)

Open the Hardhat console

```bash
npm run hardhat:console
```


#### Compile

```bash
npm run hardhat:compile
```


#### Test

```bash
npm run hardhat:test
```


### Code Coverage

```bash
npm run hardhat:coverage
```


## Linter

Use Solhint

```bash
npm run lint:sol
```

Use ESLint

```bash
npm run lint:js
```

Use ESLint and fix

```bash
npm run lint:fix
```

## Analysis

Note: it is better to analyze the flattened code to have a bigger overview on the entire codebase. So run the flattener first.

### Generate Report

Edit `scripts/analyze.sh` to add your contracts

```bash
npm run analyze
```

## License

If you want to contribute, please refer to the [contributing guidelines](./CONTRIBUTING.md) of this project.
