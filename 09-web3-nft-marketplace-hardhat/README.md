<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/levblanc/web3-blockchain-solidity-course-js">
    <img src="../images/blockchain.svg" alt="Logo" width="100" height="100">
  </a>

  <h2 align="center">Web3, Full Stack Solidity, Smart Contract & Blockchain development with JavaScript</h2>

  <p align="center">
    My Web3 full stack Solicity smart contract & blockchain development journey along with 
    <br />
    <a href="https://youtu.be/gyMwXuJrbJQ"> » this course from Patrick Collins</a>
  </p>
</div>

<br />

<div align="center">
  <p align="center">
    <a href="https://github.com/levblanc/web3-nft-marketplace-hardhat"><img src="https://img.shields.io/badge/challenge%2009-NFT%20Marketplace%20--%20Hardhat%20(lesson%2015)-4D21FC?style=for-the-badge&logo=blockchaindotcom" height="35" alt='challenge-09' /></a>
  </p>

<a href="https://github.com/levblanc/web3-nft-marketplace-hardhat">View Code</a>
· <a href="https://github.com/levblanc/web3-blockchain-solidity-course-js">Check
My Full Journey</a>

</div>

<br />

<p align="center">
  <a href='https://web3-nft-marketplace-lime.vercel.app'><img src="https://img.shields.io/badge/-%3E%3E%20View%20the%20NFT%20Marketplace%20DApp%20Live%20in%20Action%20%3C%3C-B362FF" height="30" alt='view marketplace app in action' /></a>
</p>

<br />

<!-- GETTING STARTED -->

## Getting Started

1. Clone the repo

```sh
git clone https://github.com/levblanc/web3-nft-marketplace-hardhat.git
```

2. Install dependencies with `yarn install` or `npm install`

3. Create a `.env` file under project's root directory

```.env
PRIVATE_KEY=private_key_of_your_wallet
ETHERSCAN_API_KEY=your_etherscan_api_key
GOERLI_ALCHEMY_URL=rpc_url_from_provider
GOERLI_INFURA_URL=rpc_url_from_provider
PINATA_API_KEY=pinata_api_key
PINATA_API_SECRET=pinata_api_secret
UPLOAD_TO_PINATA=boolean_of_your_choice
UPDATE_FRONT_END=boolean_of_your_choice
```

<!-- USAGE EXAMPLES -->

## Usage

For local development:

```zsh
# spin up hardhat local node
yarn localhost

# deploy contract
yarn deploy:local

# Run `mint` function
yarn mint:local
```

For Goerli testnet:

```zsh
# deploy contract to Goerli
yarn deploy:goerli

# Run `mint` function
yarn mint:goerli
```

Run tests

```zsh
# Run unit tests
yarn test
```

Check tests coverage

```zsh
yarn coverage
```

[Optional] Generate converage report

```js
// hardhat.config.js
module.exports = {
  // ... other configs
  gasReporter: {
    enabled: true, // set to true when needs a report
  },
};
```

Lint Solidity files

```zsh
# Lint only
yarn lint

# Lint & fix
yarn lint:fix
```

Code formatting

```zsh
yarn format
```

## Skills

- [![Solidity]](https://soliditylang.org/)
- [![JavaScript]](https://developer.mozilla.org/fr/docs/Web/JavaScript)
- [![Hardhat]](https://hardhat.org/)
- [![Chai]](https://www.chaijs.com/)
- [![Mocha]](https://mochajs.org/)
- [![Pinata]](https://www.pinata.cloud/)

<!-- ROADMAP -->

## Roadmap

- [x] Creating a marketplace for ERC721 NFTs
- [x] Concept of 'Pull Over Push' when sending ETH
- [x] Ins & outs of Reentrancy attack
- [x] Solidity Events with indexed params
- [x] Solidity modifiers - review and application on marketplace
- [x] Unit tests for all NFTs
- [x] Scripts to interact with contract functions

#

### [» Check the main repo of my full web3 journey](https://github.com/levblanc/web3-blockchain-solidity-course-js)

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->

[solidity]:
  https://img.shields.io/badge/solidity-1E1E3F?style=for-the-badge&logo=solidity
[javascript]:
  https://img.shields.io/badge/javascript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black
[hardhat]:
  https://custom-icon-badges.demolab.com/badge/Hardhat-181A1F?style=for-the-badge&logo=hardhat
[chai]: https://img.shields.io/badge/Chai-94161F?style=for-the-badge&logo=Chai
[mocha]:
  https://custom-icon-badges.demolab.com/badge/Mocha-8D6748?style=for-the-badge&logo=mocha&logoColor=white
[pinata]:
  https://custom-icon-badges.demolab.com/badge/Pinata-350462?style=for-the-badge&logo=pinata
