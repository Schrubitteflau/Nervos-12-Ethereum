# DApp Token Farm

From the video : https://youtu.be/CgXQC4dbGUE

Original Github repository : https://github.com/dappuniversity/defi_tutorial

# Installation

## Dependencies

```bash
npm install
npm install -g truffle@5.1.39
```

## Compile the contracts (src/contracts)

```bash
truffle compile
```

### Development

Start ganache, the first account is the one who deployed the contracts, so he initially owns the `totalSupply` of `DaiToken` and `DappToken`.

The second account will receive `100 mDAI`.

See ![Demo video](media/demo.mp4)

## Deploy the contracts

```bash
truffle migrate --reset
```