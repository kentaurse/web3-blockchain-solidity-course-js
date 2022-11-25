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
    <a href="https://github.com/levblanc/web3-lottery-nextjs"><img src="https://img.shields.io/badge/challenge%2005-NextJS%20--%20Smart%20Contract%20Lottery%20(lesson%2010)-4D21FC?style=for-the-badge&logo=blockchaindotcom" height="35" alt='challenge-05' /></a>
  </p>

<a href="https://github.com/levblanc/web3-lottery-nextjs">View Code
(Javascript)</a> ·
<a href="https://github.com/levblanc/web3-lottery-nextjs/tree/typescript">View
Code (Typescript)</a> ·
<a href="https://github.com/levblanc/web3-blockchain-solidity-course-js">Check
My Full Journey</a>

</div>

<br />

<!-- GETTING STARTED -->

## Getting Started

1. Clone the repo

```sh
git clone https://github.com/levblanc/web3-lottery-nextjs.git
```

2. Install dependencies with `yarn install` or `npm install`

3. Deploy contracts in
   [web3-lottery-hardhat](https://github.com/levblanc/web3-lottery-hardhat)

```zsh
# under web3-lottery-hardhat project directory

# deploy locally
yarn deploy

# deploy to goerli testnet
yarn deploy:goerli
```

3. Update contract address in `constants/contractAddresses.json`

```zsh
{
  "31337": ["localhost_contract_address"],
  "5": ["goerli_contract_address"],
}
```

<!-- USAGE EXAMPLES -->

## Usage

Run the development server:

```bash
npm run dev
# or
yarn dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the
result.

## Skills

- [![Solidity]](https://soliditylang.org/)
- [![JavaScript]](https://developer.mozilla.org/fr/docs/Web/JavaScript)
- [![ReactJS]](https://reactjs.org/)
- [![NextJS]](https://nextjs.org/)
- [![Moralis]](https://moralis.io/)
- [![IPFS]](https://ipfs.tech/)

<!-- ROADMAP -->

## Roadmap

- [x] NextJS setup
- [x] Manual Header to understand how `ConnectButton` works
- [x] React Hooks (`useEffect`, `useState`)
- [x] react-moralis hooks & functions (`useMoralis` & `isWeb3Enabled`,
      `useWeb3Contract` & `runContractFunction`)
- [x] Automatic Constant Value UI Updater
- [x] web3uikit for easier UI implementation
- [x] Calling Functions in NextJS
- [x] Reading & Displaying Contract Data
- [x] Tailwind & Styling

#

### [» Check the main repo of my full web3 journey](https://github.com/levblanc/web3-blockchain-solidity-course-js)

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->

[solidity]:
  https://img.shields.io/badge/solidity-1E1E3F?style=for-the-badge&logo=solidity
[javascript]:
  https://img.shields.io/badge/javascript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black
[reactjs]:
  https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB
[nextjs]:
  https://img.shields.io/badge/next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white
[ipfs]: https://img.shields.io/badge/IPFS-0A1B2B?style=for-the-badge&logo=ipfs
[moralis]:
  https://custom-icon-badges.demolab.com/badge/Moralis-2559BB?style=for-the-badge&logo=moralis
