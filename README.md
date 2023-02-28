# BSC Token

## Environment

```shell
npm install save-dev hardhat
npm install save-dev @openzeppelin-contracts
npm install save-dev dotenv
```

## How to deploy

### prepare env file
Reference > .env.example 


```shell
npx hardhat clean
npx hardhat compile
npx hardhat run scripts/deploy.js --network [mainnet] ethMainnet/bscMainnet/polygonMainnet    [testnet] goerli/bsc/polygon

examples:
> mainnet
npx hardhat run scripts/deploy.js --network ethMainnet

> testnet
npx hardhat run scripts/deploy.js --network goerli
```

## Console
deploy success: 
```
QingLong deployed to 0x7a79509c24309c5216fc12ea6cbe676ff01c46b7
```

verifly contract success:
```
Nothing to compile
Successfully submitted source code for contract
contracts/QingLong.sol:QingLong at 0x7a79509c24309c5216fc12ea6cbe676ff01c46b7
for verification on the block explorer. Waiting for verification result...

Successfully verified contract ZkMoon on Etherscan.
https://testnet.bscscan.com/address/0x7a79509c24309c5216fc12ea6cbe676ff01c46b7
```

