# Interactive NFT Marketplace

This interactive NFT marketplace is the open source showcase on how to use 0x v4 nft smart contracts on a production app. Additionally, we are building NFT infrastructure through which artists can deploy interactive NFT marketplace in a easy way. 

On this marketplace you can make offers and listings of ERC721 Tokens on the chains supported by 0x smart contracts, namely: Ethereum, Binance Smart Chain, Polygon, Fantom, Avalanche, Celo and Optimism.

# How to Start

clone this repo

```
git clone https://github.com/lunatic-games-studio/interactive-nft-marketplace.git
```

Install it and run:

```sh
npm install
npm run dev
```

# Contributing

Check [Contributing](CONTRIBUTING.md) for a more in depth way how to contribute.

# Deployment

We recommend Vercel to deploy this app, after you made your changes on the app.json config file, just use the button below:

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2FDexKit%2Fopen-nft-marketplace&env=INFURA_API_KEY)

Note that you need to set up INFURA_API_KEY to Next js be able to generate pages.

# Tech used

Started from [NEXT JS + Material UI+ Typescript + Boilerplat](https://github.com/mui/material-ui/tree/master/examples/nextjs-with-typescript)

Additionally we use trader sdk to handle nft smart contract interactions, react query to handle all http and blockchain requests, format js for internalization, web3 react to handle wallet logic. You can check our requirements [here](REQUIREMENTS.md).

# Roadmap

We will be adding any new evm network that 0x smart contracts will support.

It is also planned to extract all common hooks and state used to interact with the blockchain to a library repo.

# Customization

Connect with us.

# Missing feature?

We are welcome missing features, but take in mind that this is repo is intended to be base app for any dev to start working on, if it is makes sense to have that feature on this base app we will include, if it is considered a premium feature, we will be including on our premium marketplace which uses this one as base.

We at the moment consider premium features as follows:

- [ ] - NFT trading history

- [ ] - Artist page

- [ ] - Cache optimizations

- [ ] - Fetch NFT and token balances via api without the need to import, using Alchemy for instance

- [ ] - Swap ERC20 <-> ERC20 tokens

- [ ] - Collection level stats like orders, max supply, floor price, number of trades

- [ ] - Improved SEO

# Acknowledgements

We would like to thank ZRX project for these amazing tools and ZRX DAO for the support on building this open source app.
