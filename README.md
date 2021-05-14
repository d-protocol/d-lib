# d-protocol library

This library of Ethereum smart contracts which allow anyone to create decentralized P2P identities. 

## Using in your project

### As a node package

```
npm install @d-protocol/d-lib --save
```
or
```
yarn add @d-protocol/d-lib
```

`yarn build` will generate this file and save it to `dist/d-lib.js`

### running D-lib locally

if get gyp issues when running locally delete node_modules and run below and try again

```
sudo rm -rf $(xcode-select -print-path)
xcode-select --install
```
