A contract template for Metis chain

## Setup

```
Check if you have yarn installed with: yarn --version
    If it is not installed: npm install --global yarn

(yarn init) <- not sure if necessary

yarn install
```

## .env.example

```
Set up your environment variables
```

## Test

```
yarn hardhat test
```

## Deploy

```
yarn hardhat --network stardust deploy
```

## Find it

```
The new SmartContract will be under deployments/[Network]
```

## Verify

```
yarn hardhat --network stardust etherscan-verify
```

## Check your current progress
```
Note to self if life made me wait with continuing this project: 
cd smartcontract-deployer
npx hardhat test
```