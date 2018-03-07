# 0xAgriChain (Decentralised Application For Agriculture Supply Chain Management)

## Problem  
Supply chain is defined as the line of various points involved in producing and delivering goods, from the procurement stage to the end customer. While agriculture is the most significant sector in rural areas and provides a livelihood for 70 per cent of the world’s poor, it is also the industry that provides the biggest disconnect between supplier and retailer. Moreover, due to the lack of transparency, buyers and customers cannot be sure of the true value of the products or services. It is hard to investigate the accountability of illegal events. Because of these challenges, today the world faces problems of counterfeiting, forced labor, and poor working conditions. A more direct link with consumers would ensure fair payments for their produce and enabling retailers to verify that they are getting what they’ve paid for.

## Solution  
Blockchain Technology based on the concepts of Transparency, Decentralisation and Security is proposed solution for fixing agriculture supply chains.
A typical agricultural supply chain is replete with malpractices and monopoly, especially in non- developed economies. It is a well-known fact that farmers do not get a fair price most of the time and distributors play spoilsport by skewing the demand and supply to influence artificial price variations.
Blockchain will be useful in the agriculture sector in terms of understanding the source and journey of produce. This is vital for both Farmers and Consumers: it allows farmers to negotiate better prices throughout the supply chain, while giving consumers confidence in the knowledge of exactly where produce they buy comes from. This is key aspect when considering the growing lack of trust in the sourcing of produce sold in markets.
Blockchain will streamline co-operative operations by putting a simple Distributed Crypto Ledger into the hand of every small farmer.
It could revolutionize agriculture supply chain operations through:
1. Automating the purchase process
2. Improving Transaction Flow
3. Securing the Supply Chain
4. Ensuring Integral Traceability
5. Being more Reactive
6. Ensuring Asset Security

## Impact on Agriculture Supply Chains:  
* Transparent Transactions: Supply chain managers are generally big, downstream companies. Smaller upstream players in the chain are outgunned by the bigger players. Improved chain transparency and visibility would help them gain bargaining power.  
* Smart Contracts: Geography and longstanding relationships will be less of issue. Higher up on the supply chain a Farmer can function with very need for capital as they are paid quickly and efficiently by the consumer generating the order.  
* Data Monitoring: Record the journey taken by produce through the supply chain by utilising the power of a shared secure ledger.    
* Produce Tracking: Commodity buyers are able to deal with their supplier directly and transfer payment  
* Tracing Origin of Products: Registration, payment, and transport of crops or other agricultural produce, buyers can also verify that the product they are receiving is exactly what they paid for.  
* Fair Pricing: Suppliers in rural areas are able to determine what their harvest is currently worth and sell it to distributors at a price that reflects global market conditions.  

Demo Video Of DAPP - https://youtu.be/VWS_scOZbD4

### Tech Stack
![TechStack](https://github.com/pushkalkatara/0xAgriChain/blob/master/Presentation/11.png)

### DApp Strato Architecture
![Architecture](https://github.com/pushkalkatara/0xAgriChain/blob/master/Presentation/22.png)
* Bloc API: User/Account Management and Smart-contracts management
* STRATO API: Blockchain API for blocks and transactions.
* Cirrus: Index and search smart-contracts.
* STRATO Management Dashboard (SMD): Web based UI for your Private Ethereum Blockchain.

### DApp Flow Diagram  
![Flow Diagram](https://github.com/pushkalkatara/0xAgriChain/blob/master/Presentation/33.png)

### Blockchain Management Over Strato Node
![Blockchain Management](https://github.com/pushkalkatara/0xAgriChain/blob/master/Presentation/44.png)

## Procedure To Install:
This application requires a [BlockApps STRATO](http://blockapps.net/blockapps-strato-blockchain-application-development/) node. Follow the instruction in the [STRATO getting started guide](https://github.com/blockapps/strato-getting-started) to install a local instance.
```
npm i  # Dapp Dependencies

cd ui
npm i  # UI Dependencies
```

### Deploying on Localhost

#### Uploading the smart contracts.
From root folder of the project
```
npm run deploy
```
Windows users should run
```
set "SERVER=localhost" & npm run deploy-windows
```
#### Launching the API
From the project root (Linux, Mac and Windows):
```
npm run start
```
#### Launching the UI
```
cd ui
npm run start
```
On Windows:
```
cd ui
set "REACT_APP_API_URL=http://localhost:3031" & set "PORT=3030" & npm run start-windows
```
### [DApp Working Demo](https://youtu.be/VWS_scOZbD4) - 
Insights:  
Here is a small working demo video of the app - https://youtu.be/VWS_scOZbD4
![1](https://github.com/pushkalkatara/0xAgriChain/blob/master/Presentation/p.png)

