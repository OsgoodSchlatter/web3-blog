# Web3 blog

This is web3 blog using Next.js, Solidity, ReactJs, IPFS and Hardhat.

It's taken from this [tutorial](https://dev.to/dabit3/the-complete-guide-to-full-stack-web3-development-4g74).

## How to locally set up :

### Cloning repo

`git clone https://github.com/OsgoodSchlatter/web3-blog.git`

### Deploying contract

`npx hardhat node`

And in another terminal :

`npx hardhat run scripts/deploy.js --network localhost`

### Metamask

After enabling test networks on Metamask, you need to switch to the Localhost 8545. Then, select import account and copy the first address listed in the terminal where your run `npx hardhat node` and past it in Metamask.

### Running it on local host

`npm run dev`

Then connect to Metamask and you can add posts using the local testnet.
