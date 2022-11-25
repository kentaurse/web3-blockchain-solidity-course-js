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
    <a href="https://github.com/levblanc/web3-nft-hardhat"><img src="https://img.shields.io/badge/challenge%2008-Hardhat%20--%20NFTs%20(lesson%2014)-4D21FC?style=for-the-badge&logo=blockchaindotcom" height="35" alt='challenge-08' /></a>
  </p>

<a href="https://github.com/levblanc/web3-nft-hardhat">View Code</a> ·
<a href="https://github.com/levblanc/web3-blockchain-solidity-course-js">Check
My Full Journey</a>

</div>

<br />

<!-- GETTING STARTED -->

## Getting Started

1. Clone the repo

```sh
git clone https://github.com/levblanc/web3-nft-hardhat.git
```

2. Install dependencies with `yarn install` or `npm install`

3. Create a `.env` file under project's root directory

```.env
PRIVATE_KEY=private_key_of_your_wallet
ETHERSCAN_API_KEY=your_etherscan_api_key
GOERLI_RPC_URL=rpc_url_from_provider
PINATA_API_KEY=pinata_api_key
PINATA_API_SECRET=pinata_api_secret
UPLOAD_TO_PINATA=boolean_of_your_choice
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
- [![Chainlink]](https://chain.link/)
- [![Pinata]](https://www.pinata.cloud/)

<!-- ROADMAP -->

## Roadmap

- [x] What is an NFT?
- [x] Basic NFT contract & tests
- [x] Creating an ERC20 Token with Openzeppelin
- [x] Random IPFS NFT - Mapping Chainlink VRF Requests
- [x] Random IPFS NFT - Creating Rare NFTs
- [x] Random IPFS NFT - Setting the NFT Image & Mint Price
- [x] Deployment scripts
- [x] Uploading Token Images & Token URIs (metadata) with Pinata
- [x] Unit tests for all NFTs
- [x] Base64 encoding / decoding
- [x] EVM opcodes, ABI encoding functions & call functions directly from
      contract

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
[chainlink]:
  https://img.shields.io/badge/chainlink-375bd2?style=for-the-badge&logo=chainlink
[pinata]:
  https://custom-icon-badges.demolab.com/badge/Pinata-350462?style=for-the-badge&logo=pinata
