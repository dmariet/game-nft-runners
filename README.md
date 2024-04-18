# Runners NFT Contract

## Overview
This is a Solidity smart contract designed for creating and managing a collection of non-fungible tokens (NFTs) called "Runners" on the Fuji blockchain. The contract leverages Chainlink's Verifiable Random Function (VRF) to generate random values, simulating a running competition where each token's distance and round are determined randomly. Users can mint NFTs representing different characters and track their running progress on-chain.

## Contract Features
- **NFT Minting:** Users can mint NFTs representing various characters, each with its own name, image, distance, and round attributes.
- **VRF Integration:** Utilizes Chainlink's Verifiable Random Function (VRF) to generate random values for simulating the running competition.
- **On-Chain Tracking:** Tracks the distance and round of each runner on-chain, providing transparency and immutability.

## How to Use
To interact with the contract, follow these steps:
1. Deploy the contract on the Fuji blockchain.
2. Configure contract parameters such as VRF settings and subscription ID as needed.
3. Mint NFTs by calling the `safeMint` function, specifying the character ID to mint.
4. Simulate running competitions by calling the `run` function, which triggers the generation of random distance and round values.
5. Monitor the running progress of each runner by querying their attributes using the provided functions.

## Security Considerations
- Ensure proper configuration of VRF settings to maintain randomness and security in the running simulation.
- Implement access controls and authorization mechanisms to restrict minting and running functionalities as needed.
- Thoroughly test and audit the contract code before deploying it in production environments.

## License
This project is licensed under the terms of the MIT license. See the [LICENSE](LICENSE) file for details.

## Disclaimer
This contract is provided as an educational example and should be thoroughly tested and audited before use in production environments. Use at your own risk.
