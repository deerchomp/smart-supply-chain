# Supply chain & data auditing
Udacity Blockchain Developer Project 3: Smart supply chain management using smart contracts.

Fair Trade Coffee is a decentralized application to track assets along the supply chain from field to cup. Partners of FTC can utilize the blockchain to trustlessly prove the authenticity of their product by utilizing smart contracts at different points in the supply chain.

## Individual Roles in the Supply Chain
There are four roles represented in the supply chain: **Farmer, Distributor, Retailer, and Consumer**. All four are able to view the previous item events recorded onto the blockchain.

### Farmer
The farmer is responsible for the initial state of moving items through the supply chain. The responsibilities of the the farmer are harvesting, processing, packing, and shipping. Each step is actively called using the respective method in the smart contract to update the status of the item. The farmer has no further responsibility once the product is shipped.

### Distributor
The distributor is able to purchase product from the farmer. In real world usage, this is typically a large scale purchaser. The distributer is allowed to purchase coffee from farmers.

### Retailer
The retailer will provide product in smaller scale to the consumer. The main role of the retailer is to receive product from the distributor and provide it for sale to the consumer.

### Consumer
Consumers represent the end stage of the supply chain. The consumer can purchase from the retailer, marking the terminal endpoint of the item. Consumers are interested in verifying the authenticity of their product before consumption.


## Screenshots

![truffle test](images/ftc_product_overview.png)

![truffle test](images/ftc_farm_details.png)

![truffle test](images/ftc_product_details.png)

![truffle test](images/ftc_transaction_history.png)

## UML Diagrams
![activity](document/activity_diagram.jpeg)

![data_model](document/data_model.jpeg)

![sequence](document/sequence_diagram.jpeg)

![state](document/state_diagram.jpeg)

## Rinkeby Contract Deployment
> FarmerRole `0x50aa3c09ee8e46bc0c13fce7e42dae9ce4822c98`

> DistributorRole `0x6bb532cc3bcd255b95774a35887b8570c27bafaf`

> RetailerRole `0xa64d9f8d7c3fa2b574b6bc0bfbea33748be8e35e`

> ConsumerRole `0x318d31d102d1e73e1379a141bf0347e1e6978c0a`

> SupplyChain.sol `0xed73fc0a9ca0c0c0f48d3227e41b42133e1ba8b9`



## Additional Libraries
* NodeJS v16.3.0
* Truffle v4.1.14
* web3@1.2.1
* truffle-hdwallet-provider@1.0.17



## IPFS Setup

IPFS is not used for this project.



## Version

Version 1.0