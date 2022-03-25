# RD-Blockchain-Marketplace

Follow the steps below to download, install, and run this project.

## Dependencies
Install these prerequisites :-
- NPM: https://nodejs.org
- Truffle: https://github.com/trufflesuite/truffle
- Ganache: http://truffleframework.com/ganache/
- Metamask: https://metamask.io/


## Step 1. Clone the project
`git clone https://github.com/Rajdeep-nagar08/RD-Blockchain-Marketplace/tree/master`

## Step 2. Install dependencies
```
$ cd marketplace
$ npm install
```
## Step 3. Start Ganache
Open the Ganache GUI client that you downloaded and installed. This will start your local blockchain instance.


## Step 4. Compile & Deploy Marketplace Smart Contract
`$ truffle migrate --reset`
You must migrate the marketplace smart contract each time your restart ganache.

## Step 5. Configure Metamask
See free video tutorial for full explanation of these steps:
- Unlock Metamask
- Connect metamask to your local Etherum blockchain provided by Ganache.
- Import an account provided by ganache.

## Step 6. Run the Front End Application
`$ npm run dev`
Visit this URL in your browser: http://localhost:3000
