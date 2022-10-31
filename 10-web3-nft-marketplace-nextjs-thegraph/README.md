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
    <a href="https://github.com/levblanc/web3-nft-marketplace-nextjs-thegraph"><img src="https://img.shields.io/badge/challenge%2010-NFT%20Marketplace%20--%20Next.js%20&%20the%20graph%20(lesson%2015)-4D21FC?style=for-the-badge&logo=blockchaindotcom" height="35" alt='challenge-10' /></a>
  </p>

<a href="https://github.com/levblanc/web3-nft-marketplace-nextjs-thegraph">View
Code</a> ·
<a href="https://github.com/levblanc/web3-blockchain-solidity-course-js">Check
My Full Journey</a>

</div>

<br />

<!-- GETTING STARTED -->

## Getting Started

1. Clone the repo

```sh
git clone https://github.com/levblanc/web3-nft-marketplace-nextjs-thegraph.git
```

2. Install dependencies with `yarn install` or `npm install`

3. Deploy contracts in
   [web3-nft-marketplace-hardhat](https://github.com/levblanc/web3-nft-marketplace-hardhat)

```zsh
# under web3-nft-marketplace-hardhat project directory

# deploy locally
yarn deploy

# deploy to goerli testnet
yarn deploy:goerli
```

3. Update contract address in `constants/contractAddresses.json`

```zsh
{
  "5": {
    "NFTMarketplace": "goerli_nft_marketplace_address",
    "DynamicNFT": "goerli_dynamic_nft_address"
  },
  "31337": {
    "NFTMarketplace": "localhost_nft_marketplace_address",
    "DynamicNFT": "localhost_dynamic_nft_address"
  }
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
- [![TheGraph]](https://thegraph.com/en/)
- [![ApolloGraphQL]](https://www.apollographql.com/)
- [![GraphQL]](https://graphql.org/)
- [![Rainbow]](https://www.rainbowkit.com/)
- [![Wagmi]](https://wagmi.sh/)
- [![Antd]](https://ant.design/)

<!-- ROADMAP -->

## Roadmap

- [x] Setup NextJS to work with the graph queries and marketplace/dynamicNFT
      contracts
- [x] Query subgraph and display contract data with GraphQL & Apollo client
- [x] Use RainbowKit for wallet connection
- [x] Use Wagmi to interact with smart contracts
- [x] Build separate pages for displaying, minting and listing NFTs
- [x] Customize UI/UX with Ant Design Components & Tailwind Styling

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
[thegraph]:
  https://custom-icon-badges.demolab.com/badge/TheGraph-0C0A1C?style=for-the-badge&logo=thegraph&logoColor=white
[apollographql]:
  https://img.shields.io/badge/Apollo%20GraphQL-311C87.svg?style=for-the-badge&logo=Apollo-GraphQL&logoColor=white
[graphql]:
  https://img.shields.io/badge/GraphQL-E10098.svg?style=for-the-badge&logo=GraphQL&logoColor=white
[rainbow]:
  https://custom-icon-badges.demolab.com/badge/Rainbowkit-032463?style=for-the-badge&logo=rainbow
[wagmi]:
  https://custom-icon-badges.demolab.com/badge/Wagmi-1C1B1B?style=for-the-badge&logo=wagmi
[antd]:
  https://img.shields.io/badge/Ant%20Design-0170FE.svg?style=for-the-badge&logo=Ant-Design&logoColor=white
