# Fair Trade Coffee Supply Chain and Data Auditing DAPP
Udacity Blockchain Developer Project 3: Smart supply chain management using smart contracts.

Fair Trade Coffee is a decentralized application to track assets along the supply chain from field to cup. Partners of FTC can utilize the blockchain to trustlessly prove the authenticity of their product by utilizing smart contracts at different points in the supply chain.

# Individual Roles in the Supply Chain
There are four roles represented in the supply chain: **Farmer, Distributor, Retailer, and Consumer**. All four are able to view the previous item events recorded onto the blockchain.

## Farmer
The farmer is responsible for the initial state of moving items through the supply chain. The responsibilities of the the farmer are harvesting, processing, packing, and shipping. Each step is actively called using the respective method in the smart contract to update the status of the item. The farmer has no further responsibility once the product is shipped.

## Distributor
The distributor is able to purchase product from the farmer. In real world usage, this is typically a large scale purchaser. The distributer is allowed to purchase coffee from farmers.

## Retailer
The retailer will provide product in smaller scale to the consumer. The main role of the retailer is to receive product from the distributor and provide it for sale to the consumer.

## Consumer
Consumers represent the end stage of the supply chain. The consumer can purchase from the retailer, marking the terminal endpoint of the item. Consumers are interested in verifying the authenticity of their product before consumption.


# Screenshots

![truffle test](images/ftc_product_overview.png)

![truffle test](images/ftc_farm_details.png)

![truffle test](images/ftc_product_details.png)

![truffle test](images/ftc_transaction_history.png)

# UML Diagrams

![activity](document/activity_diagram.jpeg)

![data_model](document/data_model.jpeg)

![sequence](document/sequence_diagram.jpeg)

![state](document/state_diagram.jpeg)

# Rinkeby Contract Deployment

> FarmerRole `0x50aa3c09ee8e46bc0c13fce7e42dae9ce4822c98`

> DistributorRole `0x6bb532cc3bcd255b95774a35887b8570c27bafaf`

> RetailerRole `0xa64d9f8d7c3fa2b574b6bc0bfbea33748be8e35e`

> ConsumerRole `0x318d31d102d1e73e1379a141bf0347e1e6978c0a`

> SupplyChain.sol `0xed73fc0a9ca0c0c0f48d3227e41b42133e1ba8b9`

# Rinkeby Deployment transactions

[SupplyChain](https://rinkeby.etherscan.io/tx/0xe83c8bf29dd65cfca92d4c5d397155315074b27ed662879f17978a0268ad4961)

[FarmerRole](https://rinkeby.etherscan.io/tx/0x2406098997061340a8943ffe52ec81d2cbd00d05f74e5a50d633b3d475bd6fca)

[ConsumerRole](https://rinkeby.etherscan.io/tx/0xde545eb5673a979c4937bf268ec124265ed73edfbe74ceea4d11413aef70799b)

[RetailerRole](https://rinkeby.etherscan.io/tx/0x74b839525f1aecaac65ff4b49eba46821d19f6ddd6d4f44da8501e49f4d4e092)

[DistributorRole](https://rinkeby.etherscan.io/tx/0x4aa846d14185f3a47e3435e915806d2ef3409b33c18f786b3a4bcfafb1236ead)

# Contract Deployer

[0x472E413e40425Ae08f14F0D710625098dc52A04f](https://rinkeby.etherscan.io/address/0x472e413e40425ae08f14f0d710625098dc52a04f)

## Additional Libraries
* NodeJS v16.3.0
* Truffle v4.1.14
* web3@1.2.1
* truffle-hdwallet-provider@1.0.17

## IPFS Setup

IPFS is not used for this project.

## Version

Version 1.0
