# Decentralized Exchange App based on Uniswap V1 - PEPE Exchange App

This repository contains the code for a decentralized exchange (DEX) app based on Uniswap V1. The app allows users to trade PEPE tokens directly from their wallets without the need for a centralized intermediary. It leverages the Uniswap V1 protocol, which is an open-source protocol for automated token exchanges on the Ethereum blockchain.

## Features

The decentralized exchange app offers the following features:

1. Token Swaps: Users can swap any PEPE token for ETH or vice versa directly from their wallets. 

2. Liquidity Provision: Users can add liquidity to token pool in the exchange. By depositing an equal value of two tokens into a liquidity pool, users can earn fees and contribute to the overall liquidity of the exchange.

3. Supported Chains: Sepolia testnet is currently supported.

4. Wallet Integration: The app integrates with popular Ethereum wallets, such as MetaMask, allowing users to connect their wallets seamlessly and interact with the exchange.

Users can access deployed version of the app from here:
[DexPepeApp](https://dex-pepe.vercel.app/)



## Prerequisites

To run the decentralized exchange app, ensure that you have the following prerequisites installed:

1. Node.js (version 12 or higher)
2. Yarn package manager (optional but recommended)

## Installation

Follow these steps to install and set up the decentralized exchange app:

1. Clone this repository to your local machine using the following command:

   ```
   git clone <repository-url>
   ```

2. Navigate to the project directory:

   ```
   cd decentralized-exchange-app
   ```

3. Install the project dependencies using Yarn or npm:

   ```
   yarn install
   ```

4. Configure the app:

   - Create a `.env` file in the project root directory.
   - Add the following variables to the `.env` file:
     ```
     REACT_APP_INFURA_API_KEY=<Your Infura API key>
     REACT_APP_ETHERSCAN_API_KEY=<Your Etherscan API key>
     ```

5. Start the development server:

   ```
   yarn start
   ```

6. The app should now be running locally. Open your browser and visit `http://localhost:3000` to access the decentralized exchange.

## Usage

Once the app is running, you can perform the following actions:

- Connect your Ethereum wallet (e.g., MetaMask) by clicking on the "Connect Wallet" button.
- Explore different ERC-20 tokens and view their information.
- Swap tokens by selecting the token pair and specifying the desired amount to trade.
- Add liquidity by selecting the token pair and providing the appropriate amounts of tokens.
- View your transaction history to track your trades and liquidity additions.

Please note that this app is based on Uniswap V1 and may not have the latest features or improvements available in newer versions of Uniswap. It is recommended to review the Uniswap V1 documentation for more details on the underlying protocol.

## Contributing

Contributions to this decentralized exchange app are welcome! If you find any issues or would like to suggest enhancements, please open an issue or submit a pull request.

## License

This decentralized exchange app is licensed under the [MIT License](LICENSE). Feel free to use, modify, and distribute the code as per the terms of this license.
