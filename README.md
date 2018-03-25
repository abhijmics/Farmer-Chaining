#      Farmer Chain

---


## A blockchain based collaborative pool-farming system and self-financing platform

FarmerChain is  an attempt to provide a solution to the stinging problem of lack of organised banking in the rural sector.


## Dummy Accounts

Our prototype uses [truffle](http://truffleframework.com/) framework for it's blockchain implementation. Since truffle is limited to 10 accounts, no more accounts can be created on our platform. Some dummy accounts have been provided for you to test the project.


The Application itself is divided into three parts.

1. Farmer Bank
2. Pool Farming
3. Cart Farming


---

# Farmer Bank

---
Banking in rural sector has always been haphazard. Farmers in India historically have depended on the indigenous banking system consisting of shroffs, money lenders and tenders, charging absurdly high amounts of interest, for meeting their short term and long term credit requirements. One of the main reasons organised banking hasn't penetrated rural india is mainly due to absence of collateral security. The highier operating costs and lower margins kept these bank outside making it a monopoly of the money lenders who are sucking the ordinary farmer dry reducing them to pitful conditions

Farmer Bank aims to solve the problem with a smart contract built for managing a pool of money contributed by a group of members and processing loan requests from the members. Currently, Farmer Bank processes loan requests based on the following criteria:

1. Only members can add funds or request loan 
2. A member can request twice the amount he put in.
3. The maximum loan that is issued half the total amount in the pool


This is done to prevent the pool from getting drained and promote sustenance. As with most blockchain based solutions, Farmer Bank derives its powersfrom a large set of users.

# Pool Farming 

---
Pool Farming is a platform based on shared economy facilitating exchange of three different types of services: Hand, Machine and storage

# Cart Farming 

---

Cart Farm is a platform for requesting and outsourcing the need for bringing and delivering supplies. Going to town? You can collect requests from others and bring them their required goods in exchange for a small commission. 

You Can even pay for the purchase directly on the platform also powered by blockchain technology!


---

# Running a local instance 

* Clone the repo ``` git clone  ```
*  ``` cd Farmer-Chain ```
* Edit ``` .env ``` file with firebase configuration
* Start truffle blockchain using ``` truffle develop ``` 
* In the truffle console, ``` compile ``` then ``` migrate ```

* Open a new terminal and cd into the folder, then run ``` npm run build ```
*  Navigate to ``` localhost:5020 ```


---

# Tech Stack

---
## Front End

--- 

1. [React Js](https://reactjs.org/)
2. HTML5
3. CSS3
4. [Web3](https://github.com/ethereum/web3.js/)



# Back End 
---

1. [Truffle](http://truffleframework.com/)
2. [Webpack](https://webpack.js.org/)
3. [NodeJS](https://nodejs.org/en/)
4. [Ethereum Solidity](https://github.com/ethereum/solidity)



