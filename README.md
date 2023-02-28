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
zkMoon deployed to 0x53c567BE1dd4E7116A9Be8C364bE6C5edeC75432
```

verifly contract success:
```
Nothing to compile
Successfully submitted source code for contract
contracts/ZkMoon.sol:ZkMoon at 0x53c567BE1dd4E7116A9Be8C364bE6C5edeC75432
for verification on the block explorer. Waiting for verification result...

Successfully verified contract ZkMoon on Etherscan.
https://goerli.etherscan.io/address/0x53c567BE1dd4E7116A9Be8C364bE6C5edeC75432#code
```

