# Sample Hardhat Project: Day10Token (D10T)

## Introduction

Welcome to the Day10Token (D10T) Hardhat project! This repository serves as a basic example of a Hardhat-based Ethereum smart contract project. In this project, we have created a sample ERC20 token named "Day10Token" with the symbol "D10T." The token has a capped total supply of 100 million tokens and an initial supply of 50 million tokens allocated to the owner's account. Additionally, the token is designed to be burnable.

This README will provide you with detailed information on setting up, deploying, and testing the Day10Token contract using Hardhat.

## Prerequisites

Before getting started, make sure you have the following prerequisites installed:

- [Node.js](https://nodejs.org/) (v14 or higher)
- [npm](https://www.npmjs.com/get-npm) (usually comes with Node.js installation)
- [Hardhat](https://hardhat.org/) (installed globally)

## Project Structure

The project structure is organized as follows:

- **contracts**: Contains the Solidity smart contract files.
- **scripts**: Contains deployment scripts for the contract.
- **test**: Contains test scripts for the contract.
- **hardhat.config.js**: The Hardhat configuration file.
- **package.json**: The npm package configuration file.

## Getting Started

Follow these steps to set up and deploy the Day10Token contract:

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/yourusername/day10token-hardhat.git
   cd day10token-hardhat
   ```

2. Install the project dependencies:

   ```bash
   npm install
   ```

## Deploying the Day10Token Contract

To deploy the Day10Token contract to an Ethereum network, you can use the provided deployment script. Make sure you have configured your Ethereum network in the `hardhat.config.js` file.

1. Configure your Ethereum network settings in the `hardhat.config.js` file.

2. Run the deployment script:

   ```bash
   npx hardhat run scripts/deploy.js --network Goerli( A cross-client proof-of-authority testnet for Ethereum.)
   ```


3. The script will deploy the Day10Token contract and display the contract address once the deployment is complete.

## Testing the Day10Token Contract

We have included test scripts to ensure that the Day10Token contract functions as expected. To run the tests, use the following command:

```bash
npx hardhat test
```

This will execute the test scripts located in the `test` directory and provide you with test results.

## Usage

The Day10Token contract can be used as a sample ERC20 token. You can interact with it using various Ethereum wallet applications and libraries. Please refer to the [ERC20 standard](https://eips.ethereum.org/EIPS/eip-20) for information on how to use ERC20 tokens.

## Contract Details

- **Name**: Day10Token (D10T)
- **Symbol**: D10T
- **Total Supply**: 100,000,000 tokens (capped)
- **Initial Supply**: 50,000,000 tokens
- **Burnable**: Yes

## Contributing

If you would like to contribute to this project, please follow the [contributing guidelines](CONTRIBUTING.md).

## Acknowledgments

- Thanks to the Hardhat and Ethereum communities for their valuable tools and resources.

## Contact

If you have any questions or need assistance, please reach out to me.

Feel free to explore, modify, and use this project as a foundation for your own Ethereum smart contract development. Happy coding with Day10Token and Hardhat! 🚀🌐
