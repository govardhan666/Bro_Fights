# BRO💪FIGHTS
Buy weapons and battle with other Bro NFTs.

⚙️ Built using NextJS, RainbowKit, Hardhat, Wagmi, and Typescript. Deployed on Neox Testnet

Deployed smart contract on NeoX testnet : https://xt4scan.ngd.network/address/0x0Cad79e1699B3422E49344Fe69c3d814771CF443

## Welcome to BRO💪FIGHTS 
## Homepage

![Screenshot_5-10-2024_15852_localhost](https://github.com/user-attachments/assets/9acd3311-8c5a-4ca6-8fe7-4f7cfb6ebafb)

## Marketplace page

![Screenshot_5-10-2024_1599_localhost](https://github.com/user-attachments/assets/7f058399-02f8-4105-a19f-bb44fab6c2a0)

## Game Play page

![Screenshot_5-10-2024_151052_localhost](https://github.com/user-attachments/assets/ea8e1061-4397-4787-8a6b-7e374d5e94c3)

## Requirements

Before you begin, you need to install the following tools:

- [Node (v18 LTS)](https://nodejs.org/en/download/)
- Yarn ([v1](https://classic.yarnpkg.com/en/docs/install/) or [v2+](https://yarnpkg.com/getting-started/install))
- [Git](https://git-scm.com/downloads)

## Quickstart

To get started with SCROLL💪FIGHTS, follow the steps below:

1. Clone this repo & install dependencies

```
git clone https://github.com/govardhan666/Bro_Fights
cd Bro_Fights
yarn install
```

2. Run a local network in the first terminal:

```
yarn chain
```

This command starts a local Ethereum network using Hardhat. The network runs on your local machine and can be used for testing and development. You can customize the network configuration in `hardhat.config.ts`.

3. On a second terminal, deploy the test contract:

```
yarn deploy
```

This command deploys a test smart contract to the local network. The contract is located in `packages/hardhat/contracts` and can be modified to suit your needs. The `yarn deploy` command uses the deploy script located in `packages/hardhat/deploy` to deploy the contract to the network. You can also customize the deploy script.

4. On a third terminal, start your NextJS app:

```
yarn start
```

Visit your app on: `http://localhost:3000`. You can interact with your smart contract using the contract component or the example ui in the frontend. You can tweak the app config in `packages/nextjs/scaffold.config.ts`.
