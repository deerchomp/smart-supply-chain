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

> FarmerRole `0x3bcffd43ca559f51587661bc38dd4376ef31cd7c`

> DistributorRole `0x8ea95e403e68fd802d389e8bd418dbf8022b6ae1`

> RetailerRole `0x9eee044daae079f4007fa7b5da863d7cfdd18572`

> ConsumerRole `0xc501eb1a08c906f62ff7e7ec1913e37ad7428c38`

> SupplyChain.sol `0x8c11120b4c15a0d71e17da7c16308529be69d8d4`

# Rinkeby Deployment transactions

[SupplyChain](https://rinkeby.etherscan.io/tx/0x8d40a9f4b8ccbd6a1050bb5ee2c7b3ef8c06640bb8ec8e38387735e4ee164b5d)

[FarmerRole](https://rinkeby.etherscan.io/tx/0x2528afcb3d8095ddd55a26d43fbdd1cc570fbf63599f81cb240bc2c58d35ee2a)

[ConsumerRole](https://rinkeby.etherscan.io/tx/0xb92ccff276b754db970f5071a7d967f45e0b9be82017dc27155214c2f8c12b88)

[RetailerRole](https://rinkeby.etherscan.io/tx/0x2f9a192e0eeb3b86179489ac985aa6e1c21386b80fd148ed128f26b8e7da590e)

[DistributorRole](https://rinkeby.etherscan.io/tx/0x913585d10aaf9967b56fc50d6bb0eae8723dc111a4d4bf42484b62e1195026b7)

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
