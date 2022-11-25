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
    <a href="https://github.com/levblanc/solidity-hardhat"><img src="https://img.shields.io/badge/challenge%2002-Hardhat%20--%20Simple%20Storage%20(lesson%206)-4D21FC?style=for-the-badge&logo=blockchaindotcom" height="35" alt='challenge-02' /></a>
  </p>

<a href="https://github.com/levblanc/solidity-hardhat">View Code
(Javascript)</a> ·
<a href="https://github.com/levblanc/solidity-hardhat/tree/typescript">View Code
(Typescript)</a> ·
<a href="https://github.com/levblanc/web3-blockchain-solidity-course-js">Check
My Full Journey</a>

</div>

<br />

<!-- GETTING STARTED -->

## Getting Started

1. Clone the repo

```sh
git clone https://github.com/levblanc/solidity-hardhat.git
```

2. Install dependencies with `yarn install` or `npm install`

3. Create a `.env` file under project's root directory

```.env
PRIVATE_KEY=private_key_of_your_wallet
GOERLI_RPC_URL=rpc_url_from_provider
PRIVATE_KEY_PASSWORD=your_password
ETHERSCAN_API_KEY=your_etherscan_api_key
```

<!-- USAGE EXAMPLES -->

## Usage

Spin up a local node with hardhat

```zsh
yarn hardhat node
```

Run tests

```zsh
yarn hardhat test
```

Check tests coverage

```zsh
yarn hardhat coverage
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

Deploy contract to local network

```zsh
yarn hardhat run scripts/deploy.js
```

Deploy contract to Goerli testnet

```zsh
yarn hardhat run scripts/deploy.js --network goerli
```

## Skills

- [![Solidity]](https://soliditylang.org/)
- [![JavaScript]](https://developer.mozilla.org/fr/docs/Web/JavaScript)
- [![TypeScript]](https://www.typescriptlang.org/)
- [![Hardhat]](https://hardhat.org/)
- [![Chai]](https://www.chaijs.com/)
- [![Mocha]](https://mochajs.org/)

<!-- ROADMAP -->

## Roadmap

- [x] Hardhat Setup
- [x] Deploying SimpleStorage from Hardhat
- [x] Networks in Hardhat
- [x] Programmatic Verification
- [x] Interacting with Contracts in Hardhat
- [x] Custom Hardhat Tasks
- [x] Hardhat Localhost Node
- [x] The Hardhat Console
- [x] Running Tests
- [x] Hardhat Gas Reporter
- [x] Solidity Coverage

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
