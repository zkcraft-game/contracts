# Arbitrum Sepolia

zkCraft NFT Contract
0x5FE1965687d6eB53C74bB143Fd8f11c34F73f0Cf

# FEVM Calibration Network

## Cloning the Repo

ERC6551 Registry Contract

0xFCb286eE16977AaccF090139e374fcbEC1F9990b

ERC6551 Account Contract

0x027EaEa51DD9de494D9A82f3C8a7cB54967dA4D6

zkCraft NFT Contract

0xB5f051231832B15002838BB7e11db437771E5e61


```
git clone --recurse-submodules https://github.com/zkcraft-game/contracts
cd contracts
yarn install
```


This will clone the FVM Contracts onto your computer, switch directories into the newly installed FVM Contracts, and install the dependencies the contracts needs to work.


## Get a Private Key

You can get a private key from a wallet provider [such as Metamask](https://metamask.zendesk.com/hc/en-us/articles/360015289632-How-to-export-an-account-s-private-key).


## Add your Private Key as an Environment Variable

Add your private key as an environment variable by running this command:

 ```
export PRIVATE_KEY='abcdef'
```

If you use a .env file, don't commit and push any changes to .env files that may contain sensitive information, such as a private key! If this information reaches a public GitHub repository, someone can use it to check if you have any Mainnet funds in that wallet address, and steal them!


## Get the Deployer Address

Run this command:
```
yarn hardhat get-address
```

## Fund the Deployer Address


## Deploy the Contracts

Type in the following command in the terminal to deploy all contracts:

 ```
yarn hardhat deploy
```

This will compile all the contracts in the contracts folder and deploy them to the Calibrationnet test network automatically!
