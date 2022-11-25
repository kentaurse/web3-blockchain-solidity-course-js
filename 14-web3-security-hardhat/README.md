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
    <a href="https://github.com/levblanc/web3-security-hardhat"><img src="https://img.shields.io/badge/challenge%2014-%20Hardhat%20--%20Security%20and%20Auditing%20(lesson%2018)-4D21FC?style=for-the-badge&logo=blockchaindotcom" height="35" alt='challenge-14' /></a>
  </p>

<a href="https://github.com/levblanc/web3-security-hardhat">View Code</a> ·
<a href="https://github.com/levblanc/web3-blockchain-solidity-course-js">Check
My Full Journey</a>

</div>

<br />

<!-- GETTING STARTED -->

## Getting Started

1. Clone the repo

```sh
git clone https://github.com/levblanc/web3-security-hardhat.git
```

2. Install dependencies with `yarn install` or `npm install`

<!-- USAGE EXAMPLES -->

## Usage

### Slither

1. Check and make sure python3 & pip3 are installed

```zsh
$ python3 --version
Python 3.9.9

$ pip3 --version
pip 21.3.1 from /opt/homebrew/lib/python3.9/site-packages/pip (python 3.9)
```

2. Install `solc-select` & set target Solidity version

```zsh
# install solc-select
pip3 install solc-select

# install solidity compiler
solc-select install 0.8.17

# output
Installing '0.8.17'...
Version '0.8.17' installed.

# set solidity version
solc-select use 0.8.17

# output
Switched global version to 0.8.17
```

3. Install `slither-analyzer`

```zsh
pip3 install slither-analyzer

# verify installation
slither --help
```

3. Run command to spin up slither check

```zsh
yarn slither
```

### Eth-Security-Toolbox

Official docs: https://github.com/trailofbits/eth-security-toolbox

1. Install [docker](https://www.docker.com/) on your machine
2. Pull docker image of `eth-security-toolbox`

```zsh
docker pull trailofbits/eth-security-toolbox
```

3. Spin up toolbox shell

```zsh
yarn toolbox
```

4. Run test

```zsh
echidna-test /src/contracts/test/fuzzing/VaultFuzzTest.sol --contract VaultFuzzTest --config /src/contracts/test/fuzzing/config.yaml
```

5. Exit toolbox shell

```zsh
exit
```

## Lint Solidity files

```zsh
# Lint only
yarn lint

# Lint & fix
yarn lint:fix
```

## Code formatting

```zsh
yarn format
```

## Skills

- [![Solidity]](https://soliditylang.org/)
- [![TypeScript]](https://www.typescriptlang.org/)
- [![Hardhat]](https://hardhat.org/)
- [![OpenZeppelin]](https://openzeppelin.com/)
- [![Python]](https://www.python.org/)
- [![Docker]](https://www.docker.com/)
- [![Slither]](https://github.com/crytic/slither)
- [![Echnida]](https://github.com/crytic/echidna)

## Two Most Common Attacks:

- Reentrancy
- Oracle Manipulation

## Before deployment:

1. ALWAYS run `slither`
2. Look MANUALLY for oracle manipulation examples or reentrancy
3. Don't get anything from a centralized location (use Chainlink oracle instead)

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->

[solidity]:
  https://img.shields.io/badge/solidity-1E1E3F?style=for-the-badge&logo=solidity
[hardhat]:
  https://custom-icon-badges.demolab.com/badge/Hardhat-181A1F?style=for-the-badge&logo=hardhat
[typescript]:
  https://img.shields.io/badge/typescript-3178C6?style=for-the-badge&logo=typescript&logoColor=white
[openzeppelin]:
  https://img.shields.io/badge/OpenZeppelin-4E5EE4.svg?style=for-the-badge&logo=OpenZeppelin&logoColor=white
[python]:
  https://img.shields.io/badge/Python-3776AB.svg?style=for-the-badge&logo=Python&logoColor=white
[docker]:
  https://img.shields.io/badge/Docker-2496ED.svg?style=for-the-badge&logo=Docker&logoColor=white
[slither]:
  https://custom-icon-badges.demolab.com/badge/Slither-181B22?style=for-the-badge&logo=slither
[echnida]:
  https://custom-icon-badges.demolab.com/badge/Echnida-181B22?style=for-the-badge&logo=echnida
