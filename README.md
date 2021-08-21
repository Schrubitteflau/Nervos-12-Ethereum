# DApp Token Farm

From the video : https://youtu.be/CgXQC4dbGUE

Original Github repository : https://github.com/dappuniversity/defi_tutorial

# Installation

## Dependencies

```bash
npm install
npm install -g truffle@5.1
https://user-images.githubusercontent.com/45637360/130334637-e57d425c-d294-4d1e-aed7-6af97ca96276.mp4


## Compile the contracts (src/contracts)

```bash
truffle compile
```

### Development

Start ganache, the first account is the one who deployed the contracts, so he initially owns the `totalSupply` of `DaiToken` and `DappToken`.

The second account will receive `100 mDAI`.

See ![Demo video](media/demo.mp4)

https://user-images.githubusercontent.com/45637360/130334647-b533889f-7484-4a55-8242-d7e9bf760268.mp4

## Deploy the contracts

```bash
truffle migrate --reset
```
