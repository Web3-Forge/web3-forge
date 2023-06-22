# Components of Ethereum Network

## Overview :

- Vitalik Buterin, a programmer, proposed Ethereum in 2013. The network went live in 2015, with an initial supply of 72 million coins, after being crowdfunded in 2014.
- The Ethereum Virtual Machine (EVM) can run decentralized programs and execute scripts. Ethereum is used for decentralized banking, the production and distribution of non-fungible tokens (NFTs), and many ICOs.
- After Bitcoin, Ethereum is quoted as the second most prevalent crypto-currency. Unlike Bitcoin, Ethereum is proposed to be much more than simply a means of exchange or a store of value.
- Ethereum, on the other hand, refers to itself as a decentralized computer network based on blockchain technologies. Ethereum is built on top of a blockchain network. A blockchain is a transparent, distributed public ledger that verifies and records all transactions. Everyone on the Ethereum network has an exact copy of this ledger, which allows them to view all previous transactions.
- The Ethereum network allows users to build and run apps, smart contracts, and other transactions. These features are not available in Bitcoin.
- It is only used as a medium of exchange and a store of cash. There is no boundary on how much Ether tokens can be produced while Bitcoin can only deliver 21 million coins.
- All, regardless of context or location, have access to digital money and data-friendly resources thanks to Ethereum. It’s the technology that powers the ether (ETH) and thousands of other apps available today.
- The Ethereum Virtual Machine (EVM) is run by Ethereum clients, which may be built in any popular programming language.

## Benefits of Ethereum client implementations :
There are several benefits to having so many Ethereum client implementations, including the following as follows.

- It strengthens the network’s bug resistance.
- It keeps development resources from being centralized.
- In general, team contests aid in the discovery of the best solutions to common and difficult problems.
- In mining, prototyping, DApp development, and other areas, each customer may have a distinctive emphasis, strength, and weakness. DApp developers and private Ethereum blockchain operators may pick and choose which ones best suit their purposes.

## Components of Ethereum Network :

### Component-1 : 
<b> Nodes – </b>

There are two types of nodes in an Ethereum network. They are as follows.

- Mining Node – These nodes are responsible for writing all the transactions that have occurred in the Ethereum network in the block.
 
- Ethereum Virtual Machine Node – These are the nodes in the Ethereum network in which Smart Contracts (it is a type of contract between supporter and developer in which there are a set of rules based on which both the parties agree to interact with each other. The agreement will be automatically executed when the pre-defined rules are met.) are implemented. By default, this node utilizes a 30303 port number for the purpose of communication among themselves.

### Component-2 :  
<b> Ether – </b>

- Ether is a type of cryptocurrency used in the Ethereum network just like a bitcoin is used in a blockchain network. It is a peer-to-peer currency, similar to Bitcoin. It tracks and promotes each transaction in the network.
- It is the second-largest cryptocurrency in the world. The first one is Bitcoin. Other cryptocurrencies can be used to get ether tokens, but vice versa is not true.
- It means that ether tokens can’t be interchanged by other cryptocurrencies to render computing power for Ethereum transactions. Ether is paid as a commission for any execution that affects the state in Ethereum.
- It is used in the Ethereum algorithm as an incentive for miners who connect blocks to the blockchain using a proof-of-work method.
- It is the only currency that can be used to pay transaction costs, which go to miners as well. The block reward, as well as transaction fees, provide miners with an opportunity to keep the blockchain rising.
- Aside from paying for transactions, ether is often used to purchase gas, which is used to pay for the computation of any transaction on the Ethereum network.

### Component-3 : 
<b> Gas – </b>

- Gas is an internal currency of the Ethereum network. We need gas to run applications on the Ethereum network, much as we need gas to run a vehicle.
- To complete every transaction on the Ethereum network, a consumer must first make a payment—send out ethers—and the intermediate monetary value is known as gas.
- Gas is a unit of measurement on the Ethereum network for the computing power used to execute a smart contract or a transaction.
- The price of gas is very low compared to Ether. The execution and resource utilization costs are predetermined in Ethereum in terms of Gas units, called gwei. 

### Component-4 : 
<b> Ethereum Accounts – </b>

There are two types of Ethereum accounts. They are as follows.

- Externally owned account – These accounts are used to store transactions.
 
- Contract account – As the name itself suggests, these accounts store the details of Smart Contracts.

### Component-5 : 
<b> Nonce – </b>

- For externally owned accounts, nonce means the number of transactions via this account. For a contract account, nonce means the number of contracts generated via this account.

### Component-6 : 
<b> Storage Root – </b>
- It is the main root node of a Merkle tree. Hash of all details of the account is stored here. The root of the Merkle tree is the verification of all transactions. 

### Component-7 :  
<b> Ethash – </b>

- The intended PoW algorithm for Ethereum 1.0 is Ethash. It’s the most recent version of Dagger-Hashimoto, however, it’s no longer proper to call it that because many of the algorithms’ initial characteristics have been dramatically altered in the previous month of study and development. The original version may be found here.

<b> Algorithm :</b>

The algorithm follows the following general path as follows.

- There is a seed for each block that may be determined by reading over the block headers till that point.
- A 16 MB pseudo-random cache may be computed from the seed. The cache is saved by light clients.
- We can construct a 1 GB dataset from the cache, with the condition that each item in the dataset is dependent on just a few cache items. The dataset is stored by full clients and miners. The dataset expands linearly over time.
- Taking random slices of the dataset and hashing them together is what mining is all about. Verification may be done with little memory by utilizing the cache to renew just the parts of the dataset that you require, requiring just the cache to be stored.