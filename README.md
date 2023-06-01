# ERC721 Staking App 🖼
## Introduction

This example demonstrates a use of several thirdweb tools to create an NFT Staking application. In this example, users can stake their ERC721 NFTs and earn ERC20 tokens as a reward. It combines:

- [NFT Drop contract](https://thirdweb.com/thirdweb.eth/DropERC721): To create a collection of NFTs that users can stake.
- [Token contract](https://thirdweb.com/thirdweb.eth/TokenERC20): To create a token that users can earn as a reward for staking.
- [NFT Staking contract](https://thirdweb.com/thirdweb.eth/NFTStake): To create a contract that users can stake their NFTs in, and earn tokens as a reward.

## Demo
https://erc721-staking.vercel.app 🌍

## Using This Template

Create a project using this example:

```bash
npx thirdweb create --template nft-staking-app
```

- Create an [NFT Drop](https://thirdweb.com/thirdweb.eth/DropERC721) contract using the dashboard.
- Create a [Token](https://thirdweb.com/thirdweb.eth/TokenERC20) contract using the dashboard.
- Create an [NFT Staking](https://thirdweb.com/thirdweb.eth/NFTStake) contract using the dashboard.
- Approve the NFT Staking contract to transfer your tokens.
- Deposit the tokens into the NFT Staking contract.

## Update the information in the [contractAddresses.ts](./consts/contractAddresses.ts) file to

```bash
export const nftDropContractAddress =
  "0x54AA440e192706081BefBa609b9f8A4bF65C722d";
export const tokenContractAddress =
  "0x054D17DF0372E71981EA0886Fb5cFB2eD537Ce3C";
export const stakingContractAddress =
  "0xBB7Ecdaf78330FAD592274e6dea212301Ad4b688";
```

## Join our Discord!

For any questions, suggestions, join our discord at [https://discord.gg/thirdweb](https://discord.gg/thirdweb).
