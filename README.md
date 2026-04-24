# Blockchain Crowdfunding Marketplace DApp

A decentralized crowdfunding marketplace built with smart contracts and a Next.js frontend.

## Overview

This DApp allows project creators to publish fundraising campaigns on-chain and lets contributors fund campaigns directly from their wallets.

Core blockchain characteristics:
- Transparent campaign and contribution records
- Wallet-based authentication and transactions
- Smart contract-driven campaign logic
- Decentralized value transfer without intermediaries

## Tech Stack

- Solidity (smart contracts)
- Hardhat (development and deployment tooling)
- Ethers.js and Web3Modal (wallet + blockchain interaction)
- Next.js + React (frontend)
- Tailwind CSS (styling)

## Project Structure

- `contracts/` - Solidity contracts
- `scripts/` - deployment scripts
- `Context/` - blockchain integration and app context
- `Components/` - reusable UI components
- `pages/` - Next.js routes
- `styles/` - global styles

## Getting Started

### Prerequisites

- Node.js (18.x recommended)
- npm

### Install Dependencies

```bash
npm install
```

### Run Development Server

```bash
npm run dev
```

The application will run at `http://localhost:3000`.

## Smart Contract Workflow

1. Write or update Solidity contracts in `contracts/`.
2. Configure network and compiler settings in `hardhat.config.js`.
3. Deploy contracts using scripts in `scripts/`.
4. Connect deployed contract data to the frontend context in `Context/`.

## Available Scripts

- `npm run dev` - start local development server
- `npm run build` - build production application
- `npm run start` - run production server
- `npm run lint` - run lint checks

## Use Cases

- Community-driven fundraising
- Transparent campaign tracking
- Direct peer-to-peer contribution flows
- On-chain contribution history and verification
