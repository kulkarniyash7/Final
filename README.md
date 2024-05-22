
# Certifier Dapp - Decentralized and Secured Certification System using Blockchain

Certifier Dapp is a web application built on the Ethereum blockchain that allows users to issue, update, verify and track the change history of certificates. It is built using Web3, Ethers.js, Truffle, and Solidity for the backend and React.js for the frontend. It demonstrates the power and potential of blockchain technology in the field of certification.

## Features

- Signin with Ethereum Wallet (MetaMask)
- Issue New Certificate
- Update Issued Certificates
- Verify Issued Certificates
- Track Change history of Issued Certificate

## Tech Stack

#### Web3
- [Ethers.js](https://docs.ethers.io)
- [Truffle](https://trufflesuite.com/docs/)
- [Solidity](https://soliditylang.org/)

#### Frontend
- [React.js](https://reactjs.org)
- [React Router](https://reactrouter.com/)
- [React Toastify](https://fkhadra.github.io/react-toastify/)
## Environment Setup

- Download and install the latest node and npm from https://nodejs.org/en/download/
- Download and install Visual Studio Code from https://code.visualstudio.com/
- Download and install Ganache from https://trufflesuite.com/ganache/
    - Create new Workspace
    - Link this project to workspace
    - Update port number to 8545
    - ![Ganache Setup](https://user-images.githubusercontent.com/95211796/201491935-87f8d7cb-254e-40ff-aaae-290d25134be8.png)

- Install Truffle `npm install truffle -g`
- Link Metamask to Local Blockchain network created by Ganache

## Run Locally

Clone the project

```bash
  git clone https://github.com/aachal01/certifier-dapp.git
```

Go to the project directory

```bash
  cd certifier-dapp
```

Install dependencies

```bash
  npm install
```

Deploy Smart Contract locally

```bash
  npm run contract:deploy
```

Start the server

```bash
  npm run start
```





