# Feedback App using NES.TECH SDK from The Binary Holdings

![image](https://github.com/Harshkumar62367/TBH-hackathon-feedback-app/assets/72465090/32cb64c3-de8f-4819-9947-44e4e9fc2de3)


### Tech Stacks Used👨‍💻

Reactjs: Install React from https://vitejs.dev/guide/

Solidity: Refer to Solidity docs

Hardhat: Refer to Hardhat docs

EtherJs: Refer to EtherJs docs

Metamask: Metamask is a browser extension that allows users to interact with the Ethereum blockchain. It allows users to connect to the Ethereum network and interact with smart contracts.

NEST SDK: SDKs available in every language, smart contracts, tools, and infrastructure for web3 development.

### Prerequisites 👨‍💻
1. Install Node JS. Refer to https://nodejs.org/en/ to install nodejs

2. Clone the project into local using the command :
```
git clone https://github.com/Harshkumar62367/TBH-hackathon-feedback-app.git
```
3. Install all the npm packages. Go into the root folder as well as in the client and type the following command to install all npm packages
```
npm install
```
4. Run the following commands into the `client` folder to install the NEST SDK :
```
npm config set //gitlab.com/api/v4/packages/npm/:_authToken=glpat-q7B7KpRiCQqugJVzG7vE
```
```
npm config set @nest25:registry https://gitlab.com/api/v4/packages/npm/
```
```
npm i @nest25/evm-chains-lib
```
5. Change the private key into the `client/src/contractErc20.js` file to deploy your own contract and mint your own tokens.
  
6. Change the private key,contract address and receiver address into the transfer tokens function present into `client/src/components/Buy.jsx` file.
  
7. And Type the following command in the client folder of the project, to run the server
```
npm run dev
```

The Client Runs on http://127.0.0.1:5173/
