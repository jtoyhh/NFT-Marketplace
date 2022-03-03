# Building an NFT marketplace 
### Refer to [How to Build a Full Stack NFT Marketplace](https://dev.to/dabit3/building-scalable-full-stack-apps-on-ethereum-with-polygon-2cfb)

### Prerequisites
- node.js : 16.14.0
- Metamask wallet extension

### The Stack
- Next.js
- Hardhat
- IPFS
- Ethers.js



To run this project locally, follow these steps.

1. Clone the project locally, change into the directory, and install the dependencies:

```sh
git clone https://github.com/jtoyhh/NFT-Marketplace.git

cd NFT-Marketplace

# install using NPM or Yarn
npm install

# or

yarn
```

2. Start the local Hardhat node

```sh
npx hardhat node
```

3. With the network running, deploy the contracts to the local network in a separate terminal window

```sh
npx hardhat run scripts/deploy.js --network localhost
```

4. Start the app

```
npm run dev
```
