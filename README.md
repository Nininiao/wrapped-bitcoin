# wrapped-bitcoin
# Project description

Wrapped Bitcoin Tokens (WBTC) is an ERC20 token fully backed by real BTC. The proof of reserves is on-chain, showing the exact 1:1 ratio between minted WBTC tokens and BTC stored by the custodians.


This is the subgraph, a collection of GraphQL schemas and mappings that parse the events broadcast by this subgraph on the Ethereum blockchain.

The smart contracts can be found here https://etherscan.io/address/0x2260fac5e5542a773aa44fbcfedf7c193bc2c599#code.

# Development
Before you can build, create and deploy this subgraph, you have to execute the following commands in the terminal:

$ yarn install

$ yarn prepare:mainnet

The first command installs all external dependencies, while the latter generates the subgraph.yaml file, which is required by The Graph.

The manual how to Build a Subgraph via Contract on Windows for a Non-Tech Curators you can find here https://ninadrokina.medium.com/how-to-build-a-subgraph-via-contract-on-windows-for-a-non-tech-curator-74d5d9e47e96
