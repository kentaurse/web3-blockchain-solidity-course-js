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
    <a href="https://github.com/levblanc/web3-lottery-hardhat"><img src="https://img.shields.io/badge/challenge%2004-Hardhat%20--%20Smart%20Contract%20Lottery%20(lesson%209)-4D21FC?style=for-the-badge&logo=blockchaindotcom" height="35" alt='challenge-04' /></a>
  </p>

<a href="https://github.com/levblanc/web3-lottery-hardhat">View Code
(Javascript)</a> ·
<a href="https://github.com/levblanc/web3-lottery-hardhat/tree/typescript">View
Code (Typescript)</a> ·
<a href="https://github.com/levblanc/web3-blockchain-solidity-course-js">Check
My Full Journey</a>

</div>

<br />

<!-- GETTING STARTED -->

## Getting Started

1. Clone the repo

```sh
git clone https://github.com/levblanc/web3-lottery-hardhat.git
```

2. Install dependencies with `yarn install` or `npm install`

3. Create a `.env` file under project's root directory

```.env
PRIVATE_KEY=private_key_of_your_wallet
GOERLI_RPC_URL=rpc_url_from_provider
ETHERSCAN_API_KEY=your_etherscan_api_key
UPDATE_FRONT_END=boolean_of_your_choice
```

<!-- USAGE EXAMPLES -->

## Usage

For local development:

```zsh
# spin up hardhat local node
yarn localhost

# deploy contract
yarn deploy
```

For Goerli testnet:

```zsh
# deploy contract to Goerli
yarn deploy:goerli
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
- [![TypeScript]](https://www.typescriptlang.org/)
- [![Hardhat]](https://hardhat.org/)
- [![Chai]](https://www.chaijs.com/)
- [![Mocha]](https://mochajs.org/)
- [![Chainlink]](https://chain.link/)

<!-- ROADMAP -->

## Roadmap

- [x] Hardhat Setup
- [x] Raffle.sol Setup
- [x] Events in Raffle.sol
- [x] Introduction to Chainlink VRF (Randomness in Web3)
- [x] Hardhat Shorthand
- [x] Implementing Chainlink VRF - The Request
- [x] Implementing Chainlink VRF - The Fulfill
- [x] Introduction to Chainlink Keepers
- [x] Implementing Chainlink Keepers (checkUpKeep)
- [x] Implementing Chainlink Keepers (performUpKeep)
- [x] Enums
- [x] Deploying Raffle.sol & Mock Chainlink VRF Coordinator
- [x] Raffle.sol Unit Tests
- [x] Hardhat Methods & "Time Travel"
- [x] Callstatic
- [x] Raffle.sol Staging Tests
- [x] Testing on a Testnet

#

### [» Check the main repo of my full web3 journey](https://github.com/levblanc/web3-blockchain-solidity-course-js)

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->

[solidity]:
  https://img.shields.io/badge/solidity-1E1E3F?style=for-the-badge&logo=solidity
[javascript]:
  https://img.shields.io/badge/javascript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black
[typescript]:
  https://img.shields.io/badge/typescript-3178C6?style=for-the-badge&logo=typescript&logoColor=white
[hardhat]:
  https://custom-icon-badges.demolab.com/badge/Hardhat-181A1F?style=for-the-badge&logo=hardhat
[chai]: https://img.shields.io/badge/Chai-94161F?style=for-the-badge&logo=Chai
[mocha]:
  https://custom-icon-badges.demolab.com/badge/Mocha-8D6748?style=for-the-badge&logo=mocha&logoColor=white
[chainlink]:
  https://img.shields.io/badge/chainlink-375bd2?style=for-the-badge&logo=chainlink
