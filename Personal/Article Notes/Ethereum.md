
## Ethereum

Date: 2022-05-03
Author:
Tags: #ethereum #blockchain 
Links: https://ethereum.org/en/developers/docs/


---

#### Summary + Notes

- Blockchain is a public database that is updated and shared across many computers in a network.
- **Ether (ETH)** is the native cryptocurrency of Ethereum.
- At a very basic level, you can think of a smart contract like a sort of vending machine: a script that, when called with certain parameters, performs some actions or computation if certain conditions are satisfied.
- The Ethereum Virtual Machine is the global virtual computer whose state every participant on the Ethereum network stores and agrees on. Any participant can request the execution of arbitrary code on the EVM; code execution changes the state of the EVM.
- Gas fees are dependent on the amount of computing power required and the network demand at that time.
- A decentralized application (dapp) is an application built on a decentralized network that combines a [smart contract](https://ethereum.org/en/developers/docs/smart-contracts/) and a frontend user interface.
- Denial-of-service attacks not possible. Also users cannot flood ethereum network with fake requests as each request requires GAS fees and users will eventually run out of it.

| Benefits of DAPPS     | Drawbacks of DAPPS                       |
| --------------------- | ---------------------------------------- |
| No downtime           | Maintenance - because they are immutable |
| No censorship         | Performance overhead                     |
| Privacy               | Network congestion                       |
| Date integrity        | User experience                          |
| Trustless computation | Centralization                           |

- Web3 Dapps allow people to participate without monetizing their personal data.
- Ethereum is turing-complete, meaning you can pretty much program anything.
- Gas is a reference to the computation required to process the transaction by a miner. Users have to pay a fee for this computation. The `gasLimit`, and `maxPriorityFeePerGas` determine the maximum transaction fee paid to the miner.
- Your transaction will receive "confirmations". The number of confirmations is the number of blocks created since the block that included your transaction. The higher the number, the greater the certainty that the network processed and recognized the transaction.
- Proof-of-work means the following:
	- Mining nodes have to spend a variable but substantial amount of energy, time, and computational power to produce a “certificate of legitimacy” for a block they propose to the network. This helps protect the network from spam/denial-of-service attacks, among other things, since certificates are expensive to produce.
	-   Other miners who hear about a new block with a valid certificate of legitimacy must accept the new block as the canonical next block on the blockchain.
	-   The exact amount of time needed for any given miner to produce this certificate is a random variable with high variance. This ensures that it is unlikely that two miners produce validations for a proposed next block simultaneously; when a miner produces and propagates a certified new block, they can be almost certain that the block will be accepted by the network as the canonical next block on the blockchain, without conflict (though there is a protocol for dealing with conflicts as well in the case that two chains of certified blocks are produced almost simultaneously).
- 

