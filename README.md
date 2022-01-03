# Basic Sample Hardhat Project

The ChainID should be 1337, and you may need to delete a localhost configuration if you already have that set up.

## Run locally

1. Clone this repo


2. Install the dependencies

```sh
npm install 

# or

yarn
```

3. Start the local test node

```sh
npx hardhat node
```

4. Deploy the contract

```sh
npx hardhat run scripts/deploy.js --network localhost
```

5. Update __src/App.js__ with the values of your contract addresses (`greeterAddress` and `tokenAddress`)

6. Run the app

```sh
npm start
```

Try running some of the following tasks:

```shell
npx hardhat accounts
npx hardhat compile
npx hardhat clean
npx hardhat test
npx hardhat node
node scripts/sample-script.js
npx hardhat help
```
