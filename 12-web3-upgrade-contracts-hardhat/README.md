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
    <a href="https://github.com/levblanc/hardhat-upgrade-smart-contracts"><img src="https://img.shields.io/badge/challenge%2012-Smart%20Contract%20Upgrades%20--%20Hardhat%20(lesson%2016)-4D21FC?style=for-the-badge&logo=blockchaindotcom" height="35" alt='challenge-12' /></a>
  </p>

<a href="https://github.com/levblanc/hardhat-upgrade-smart-contracts">View
Code</a> ·
<a href="https://github.com/levblanc/web3-blockchain-solidity-course-js">Check
My Full Journey</a>

</div>

<br />

<!-- GETTING STARTED -->

## Getting Started

1. Clone the repo

```sh
git clone https://github.com/levblanc/hardhat-upgrade-smart-contracts.git
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
# compile contracts
yarn compile

# deploy contract
yarn deploy
```

Try Upgrade:

```zsh
# In terminal 1: spin up hardhat local node
yarn localhost

# In terminal 2: run upgrade script
yarn upgrade:local
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

- [x] Types of Upgrades
  - [x] Parameter
  - [x] Social Migrate
  - [x] Proxy
  - [x] Proxy Gotchas
    - [x] [Function Collisions](https://blog.openzeppelin.com/the-state-of-smart-contract-upgrades/#transparent-proxies)
    - [x] [Storage Collisions](https://blog.openzeppelin.com/the-state-of-smart-contract-upgrades/#unstructured-storage)
  - [x] Metamorphic Upgrades
  - [x] [Transparent](https://blog.openzeppelin.com/the-transparent-proxy-pattern/)
  - [x] [UUPS (Universal Upgradable Proxies)](https://forum.openzeppelin.com/t/uups-proxies-tutorial-solidity-javascript/7786)
  - [x] [Diamond](https://blog.openzeppelin.com/the-state-of-smart-contract-upgrades/#diamonds)

## Worth to Reads

1. [The State of Smart Contract Upgrades](https://blog.openzeppelin.com/the-state-of-smart-contract-upgrades/)
2. [OpenZeppelin - Upgrades Plugins](https://docs.openzeppelin.com/upgrades-plugins/1.x/)

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
