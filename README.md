# IPCNet: Empowering Decentralized Applications

## Overview

IPCNet is a revolutionary platform that simplifies the deployment and management of Inter-Process Communication (IPC) subnets for decentralized applications. Our platform empowers developers and users to create custom subnets tailored to their specific use cases, enabling faster transactions and unlocking the full potential of IPC and Future Virtual Machine (FVM) technology.

## Features

- **Easy Deployment**: Deploy IPC subnets in just a few clicks, eliminating the need for complex configuration and setup.
- **Scalability**: Scale your decentralized applications effortlessly by deploying multiple IPC subnets and connecting them seamlessly.
- **Security**: Ensure the security and integrity of your transactions with built-in encryption and tamper-proofing mechanisms.
- **Interoperability**: Interact with other blockchain networks and legacy systems through seamless integration and interoperability features.
- **Developer-Friendly**: Access comprehensive documentation, tutorials, and developer tools to streamline the development process.

## Use Cases

- **Decentralized Finance (DeFi)**: Deploy smart contracts for lending, borrowing, and decentralized exchanges with sub-second transactions.
- **Supply Chain Management**: Track and trace goods across supply chains transparently and efficiently using blockchain technology.
- **Digital Identity**: Create decentralized identity solutions for secure and portable identity verification, reducing reliance on centralized authorities.
- **Tokenization of Assets**: Tokenize real-world assets such as real estate, art, and commodities for increased liquidity and fractional ownership.
- **Microtransactions**: Enable IoT devices to transact with each other seamlessly for services like metered utility usage and automated supply reordering.

## Getting Started

- Clone the repository 

### Start the backend

- run `cd backend`
- run `pnpm install`
- replace the path of ipc-cli from `/workspaces/filecoin-data-economy/ipc/target/release/ipc-cli` to your current path (preferrably use absolute path) in `index.js`
- run `node index.js`

### Start the frontend

- run `cd frontend`
- run `yarn`
- run `yarn dev`
- open `http://localhost:3000` in your browser to access ipcnet
