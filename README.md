# Dexcanary Web3 Package

![Custom badge](https://img.shields.io/endpoint?logo=github&url=https%3A%2F%2Fkorntimaroon.github.io%2Fhexa_code_api.github.io%2FdexcanaryPackage.json)

Dexcanary Web3 Package Version 0.0.1

## Installation

**Install Syntax**
```sh
npm install dexcanaryWeb3
```
***
**Import Syntax**
```js
const dexcaWeb3 = require("dexcanaryWeb3")
```
***

## Version & Package Information Syntaxes

**Output the package version**
```js
dexcaWeb3.getCheckVersion()
```
**Output the package information**
```js
dexcaWeb3.getPackageInfo()
```

## Syntaxes
**Generate Ethereum Cryptocurrency Account**
```js
dexcaWeb3.getCreateAccount(rpc)
```
**Count the transaction on a given cryptocurrency network**
```js
dexcaWeb3.getCheckTransactionCount(publicKey,rpc)
```
**Convert Wei(Unit) to Ethers(Unit)**
```js
dexcaWeb3.getConvertWeiEthers(number)
```
**Convert Ethers(Unit) to Wei(Unit)**
```js
dexcaWeb3.getConvertEthersWei(number)
```
**Get Balance in a given cryptocurrency network(Ethers Unit)**
```js
dexcaWeb3.getBalance(account,rpc)
```
**Get Balance in a given cryptocurrency network(Wei Unit)***
```js
dexcaWeb3.getBalanceInWei(account,rpc)
```
**Check the network in a given RPC_URL**
```js
dexcaWeb3.getCheckNetwork(rpc)
```

## Usage
***
