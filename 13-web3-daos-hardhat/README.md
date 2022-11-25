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
    <a href="https://github.com/levblanc/web3-daos-hardhat"><img src="https://img.shields.io/badge/challenge%2013-%20Hardhat%20--%20DAOs%20(lesson%2017)-4D21FC?style=for-the-badge&logo=blockchaindotcom" height="35" alt='challenge-13' /></a>
  </p>

<a href="https://github.com/levblanc/web3-daos-hardhat">View Code</a> ·
<a href="https://github.com/levblanc/web3-blockchain-solidity-course-js">Check
My Full Journey</a>

</div>

<br />

<!-- GETTING STARTED -->

## Getting Started

1. Clone the repo

```sh
git clone https://github.com/levblanc/web3-daos-hardhat.git
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

Propose, vote, queue & execute:

```zsh
# In terminal 1: spin up hardhat local node
yarn localhost

# In terminal 2: run propose script
yarn propose:localhost

# Run vote script
yarn vote:localhost

# Run queue-and-execute script
yarn queueAndExecute:localhost
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
- [![OpenZeppelin]](https://openzeppelin.com/)

<!-- ROADMAP -->

## Roadmap

- [x] [What is a DAO](https://www.youtube.com/watch?v=X_QKZzd68ro)?
- [x] Walked thru Compound app's governance process
- [x] Built an on-chain DAO with
  - [x] governance token
  - [x] governor contract (with
        [OpenZeppelin Contracts Wizard](https://docs.openzeppelin.com/contracts/4.x/wizard))
  - [x] timelock contract

Note:

- The governor contract holds all key logics: `propose`, `castVoteWithReason`,
  `queue` and `execute`
- The timelock contract controls the how long we need to wait (`minDelay`)
  before `execute`. Give user time to "get out" if they don't like a governance
  update (the proposal).

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
[openzeppelin]:
  https://img.shields.io/badge/OpenZeppelin-4E5EE4.svg?style=for-the-badge&logo=OpenZeppelin&logoColor=white
