<a name="readme-top"></a>

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
    <a href="https://github.com/levblanc/solidity-hardhat-advanced"><img src="https://img.shields.io/badge/challenge%2003-Hardhat%20Fund%20Me%20(Lesson%207)-4D21FC?style=for-the-badge&logo=blockchaindotcom" height="35" alt='challenge-02' /></a>
  </p>

<a href="https://github.com/levblanc/solidity-hardhat-advanced">View Code</a> ·
<a href="https://github.com/levblanc/web3-blockchain-solidity-course-js">Check
My Full Journey</a>

</div>

<br />

<!-- GETTING STARTED -->

## Getting Started

1. Clone the repo

```sh
git clone https://github.com/levblanc/solidity-hardhat-advanced.git
```

2. Install dependencies with `yarn install` or `npm install`

3. Create a `.env` file under project's root directory

```.env
PRIVATE_KEY=private_key_of_your_wallet
GOERLI_RPC_URL=rpc_url_from_provider
ETHERSCAN_API_KEY=your_etherscan_api_key
```

<!-- USAGE EXAMPLES -->

## Usage

For local development:

```zsh
# spin up hardhat local node
yarn localhost

# deploy contract
yarn deploy

# Run `fund` function
yarn fund:local

# Run `withdraw` function
yarn withdraw:local
```

For Goerli testnet:

```zsh
# deploy contract to Goerli
yarn deploy:goerli

# Run `fund` function
yarn fund:goerli

# Run `withdraw` function
yarn withdraw:goerli
```

Run tests

```zsh
# Run unit tests
yarn test

# Run staging tests (on Goerli testnet)
yarn test:staging
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

<!-- ROADMAP -->

## Roadmap

- [x] Hardhat Setup
- [x] Contracts Linting
- [x] Hardhat Deploy
- [x] Mocking & helper-hardhat-config
- [x] Solidity Style Guide
- [x] Testing Fund Me Contract
- [x] Breakpoints & Debugging
- [x] Solidity console.log & Debugging
- [x] Storage in Solidity
- [x] Gas Optimizations using storage knowledge
- [x] Staging Tests
- [x] Running Scripts on a Local Node
- [x] Adding scripts to your package.json

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
