# Introduction to Ethereum Virtual Machine (EVM)?

Ethereum Virtual Machine (EVM) is designed as the runtime environment for smart contracts in Ethereum. It is sandboxed and isolated from the other parts of the system. This means that any operation on EVM should not affect your data or programs in any way, no matter how many times you call a particular function on it.

- An EVM is the runtime environment that executes Ethereum smart contracts.
- Ethereum contains its own Turing-complete scripting language, called Solidity, and with this comes a need to execute this code. 
- A program called the Ethereum Virtual Machine (EVM) can do this task.
- It runs on top of the Ethereum network, meaning that all nodes reach a consensus about what code should be executed at every given time.

## Purpose of EVM
The Ethereum Virtual Machine (EVM) is a Turing complete programmable machine, which can execute scripts to produce arbitrary outcomes. It has been built with the purpose of being a “world computer” and has immense power.

- It is the computer that stores data on blockchain, like bitcoin, but it also executes code in smart contracts on the Ethereum network.
- The machine is made to be able to run any kind of Crypto-contract that can be built on Ethereum’s blockchain. It does this by using a programming language called Solidity, which is compiled into the EVM for execution.
- The intention behind writing code on the Ethereum network is to create smart contracts and programs that automatically execute things when certain conditions are met. If a terms or condition is not met, the system can execute it in an “exit” function as well. 
- For example, if an account has been hacked, the hacker cannot steal money from the system, because they don’t have the budget or authority to do so.

## How Does EVM Works?
Ethereum Virtual Machine (EVM) is a program which executes scripts used to implement certain operations usually in Ethereum blockchain. 
The Ethereum Virtual Machine makes the process of creating new tokens on Ethereum Blockchain easy. Here, script means a set of instructions or an algorithm which tells the computer what it needs to do in order for something to work properly. The EVM requires that one has access over any network node so as to be able to execute the desired commands and create new tokens on the blockchain without any difficulties.

- In Ethereum, there is something called a smart contract. These contracts have some computer code which facilitates the exchange of money and information. 
- These contracts are predefined by the creator of the smart contract, in order to ensure that a certain outcome will happen based on either what happens or doesn’t happen. 
- Ethereum Virtual Machine provides Turing complete environment for execution of scripts and smart contracts. This means that anything that can be implemented with a computer can be run on EVM.

In the Ethereum ecosystem, EVM plays a vital role by providing a platform for decentralized applications (DApps) to be built on top of it. 
Ethereum Virtual Machine ensures that all transactions and smart contracts made on the Ethereum blockchain are executed in correct and expected manner as desired by the smart contract code. It serves as a platform for applications to be executed on.
In simple words, it can be said that Ethereum Virtual Machine facilitates DApp creation and execution on the blockchain.

## Ethereum Virtual Machine (EVM) has two parts:

EVM (the part that runs solidity source code): The EVM is written in C++ and uses LLVM as its compiler. It is a full-featured virtual machine with all the features that you would want in a general purpose Smart Contract Virtual Machine, such as support for multiple programming languages, security features, runtime environments and more. It also allows you to write custom EVM bytecode .
Uncles: These are small pieces of smart contracts or data stored on the blockchain. This is a useful feature because it allows for you to store metadata about your program. EVM Assembly: This is the bytecode of EVM, which you can use as your programming language.
These are small pieces of smart contracts or data stored on the blockchain. This is a useful feature because it allows one to store metadata about the program.

- Actions: These are basic operations that one can perform on assets stored in memory (and not on the blockchain), such as multiplication, addition, and so on.
Balance: This is the amount of Ether that one have at any time. So, if there is a balance of 100 Ether and spend 10 Ether, the balance would be 90 Ether. Note that this is not actually a variable, it’s just a part of memory where EVM stores the data. This means that whenone tries to modify or read from it, it will return execution with an error.
- Block: This is an immutable storage for all actions and transactions related to Ethereum in its lifetime up until this block in particular. These blocks can be only 65,000 so this is not going to change.
- Blockhash: This is a hash of the block in question. So, if you are looking at stored on the blockchain under another name, this would be a hash of the data stored there.
- Block Number: This is a number indicating which block this particular blockhash belongs to. It always starts from zero and increases every time there’s a new block added to the chain. Note that blocks have timestamps associated with them so you can tell how much time passed between two blocks.
- Code: This is code executed in EVM that determines what action is going to be taken when an input happens (such as transferring money).
- CodeHash: This is a hash of the code itself. If one looks at a contract on Etherscan, the CodeHash is what one will see. When functions are executed on EVM, this number changes because the code itself changes based on the input.
- CodeSize: This is the actual size of the code in bytes.
- GasLimit: This is a part of EVM that allows for users to specify how much gas they are willing to spend in order to execute something. If this number is zero, then nothing will happen (this rarely happens).

## How Does Gas Relate To Performance Of EVM?

Gas is a measure of computational power. It determines how much time each transaction and contract takes to execute. 
Because there is so much code already in the system, it uses a limited amount of Gas to run all of this code. It sets the default gas limit to 250,000 gas units. 
In general, the more complicated your transaction, the more gas it takes to execute.

## Benefits of EVM

- Execute untrusted code without risking data: One can execute untrusted code without putting the data at risk. EVM guarantees that its computations will not interfere with anything else happening in the system or with the personal files.
- Can run complex smart contracts: One can run complex smart contracts in EVM without worrying about how they interact with each other. One can write them once and then run them on multiple platforms, which allows for the creation of a single contract that runs on multiple computing environments.
- Deterministic processing: Smart contracts written on EVM have access to all of Ethereum’s states at any given time, allowing for processing to happen in a deterministic way and giving more guarantees about their correctness. For example, one cannot make an infinite loop in EVM by calling the same function twice. It would stop executing and return a finite value.
- Distributed consensus: One of the potential applications of Ethereum is to allow for distributed consensus where everyone is running the same program but from their own computers. 
- Robust against failure: This is a complex process because the network needs to be able to come to a consensus at any given time. This way, the system becomes more robust against failures of individual nodes and you can update several nodes simultaneously without worrying that they might end up disagreeing with each other because of how code was written.
- Easy to write stateful contracts: From a developer perspective, EVM is designed for writing smart contracts as well as for creating DApps (decentralized applications), which are programs running on distributed networks in a way that ensures all of them are seeing the same version. It also makes it incredibly easy to write stateful contracts, which need access to some kind of persistent storage.

## Downsides of EVM
- High cost of storing data: First is gas, which is what you need to use in order to pay the fee to run a smart contract, and the other is the high cost of storing data on the blockchain, which could take up more than 3TB
- High gas cost: In Ethereum, all transactions require a fee to execute. These fees are called “gas”, and are paid in ETH tokens. Gas is priced at the moment of execution, and depends on the complexity of executing a transaction. The more difficult the computation for a transaction, the higher its gas cost will be.
- High gas price during network congestion: During times when there is high network congestion due to many transactions being pushed onto the blockchain, gas prices rise because there are fewer transactions that can go through (the same amount of computational power has to service more transactions).
- Technical expertise required: Writing smart contracts and using EVM requires technical expertise. It’s a Turing-complete system, which allows programmers to write scripts in any programming language they wish. This can be excellent or disastrous, depending on the intention behind the code being written. Programming languages are not inherently good or bad in their nature; it all depends on who is using them and for what purpose. The downside of this technology is that it could create a lot of complicated problems because with more power comes more responsibility for the writer of code.