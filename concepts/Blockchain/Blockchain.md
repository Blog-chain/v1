---
title: Blockchain
description: 블록체인 기술의 기본 개념과 구조, 그리고 다양한 응용 사례를 다룹니다.
aliases: [blockchain, distributed ledger, decentralized ledger]
tags: [technology, blockchain, distributed systems]
date: 2024-07-22
---

# Component

- [[Block]]

# ⛓️ Blockchain

- a public database that is updated and shared across many computers in a network
- [intro-to-ethereum/#what-is-a-blockchain](https://ethereum.org/en/developers/docs/intro-to-ethereum/#what-is-a-blockchain)
- A database of transactions, duplicated and shared on all computers in the network, ensuring data cannot be altered retroactively.
- [glossary/#blockchain](https://ethereum.org/en/glossary/#blockchain)

A blockchain is a database of transactions that is updated and shared across many computers in a network. Every time a new set of transactions is added, its called a “block” - hence the name blockchain. Public blockchains like Ethereum allow anyone to add, but not remove, data. If someone wanted to alter any of the information or cheat the system, they’d need to do so on the majority of computers on the network. That is a lot! This makes decentralized blockchains like Ethereum highly secure.

[https://ethereum.org/en/what-is-ethereum/](https://ethereum.org/en/what-is-ethereum/)

a cryptographically secured, time-stamped, public and distributed database of every
[[transaction]] that has ever occurred on the network.

“Distributed” here means that the information in the blockchain is broadcast to and recorded by every node in the network. There is no one central database. Any user can refer to this list of transactions and check exactly what how many bitcoins have ever belonged to any specific [https://bitcoinwiki.org/wiki/bitcoin-address](https://bitcoinwiki.org/wiki/bitcoin-address) at any point in time. This way the system is transparent, double-spending is prevented, and there is no need for a trusted central authority.

The bitcoin blockchain is supported by the efforts of many miners: users who put computing power to the task of solving a mathematical problem that will reward them with bitcoins, while at the same time producing the hashes that secure the blocks of data in the chain. The hashes are cryptographically produced strings of data that make the info in the blockchain virtually impossible to tamper with. | [https://bitcoinwiki.org/wiki/blockchain](https://bitcoinwiki.org/wiki/blockchain) |

### 👝 Digital Wallet _(_`Wallet` _in Blockchain)_

- An electronic device, online service, or software program that allows one party to make electronic transactions with another party bartering digital currency units for goods and services.

- A digital wallet, also known as an e-wallet or mobile wallet, is an electronic device, online service, or software program that allows one party to make electronic transactions with another party bartering digital currency units for goods and services.

[https://en.wikipedia.org/wiki/Digital_wallet](https://en.wikipedia.org/wiki/Digital_wallet)

- Money can be deposited in the digital wallet prior to any transactions or, in other cases, an individual's bank account can be linked to the digital wallet.

## Network

### 🌐 Mainnet

- deploy and service

### ☑️ Testnet

- develop, test and debug

## Blockchain

### Summary

`Blockchain`은 탈중앙화를 지향하는 공개 분산 원장 시스템입니다. 이는 트랜잭션 데이터가 블록 단위로 기록되고, 이 블록들이 체인 형태로 연결되어 있는 구조를 가지고 있습니다.

### Description

`Blockchain` 기술은 **투명성과 보안**을 보장하는 탈중앙화 원장 시스템입니다. 각 블록은 이전 블록의 암호화 해시, 타임스탬프 및 트랜잭션 데이터를 포함하여 불변의 체인을 형성합니다. 탈중앙화된 블록체인 기술은 데이터를 여러 노드에 분산시켜 조작과 사기에 **강력한 저항력**을 가집니다.

블록체인의 구조는 다음과 같은 요소로 구성됩니다:

1. **블록 (Block)**: 트랜잭션 데이터를 포함하는 데이터 구조입니다. 각 블록은 이전 블록의 해시 값을 포함하여 체인 형태로 연결됩니다.
2. **노드 (Node)**: 블록체인 네트워크를 구성하는 개별 컴퓨터로, 모든 트랜잭션을 검증하고 블록을 생성 및 전파하는 역할을 합니다.
3. **타임스탬프 (Timestamp)**: 각 블록이 생성된 시간을 기록하여 블록의 순서를 보장합니다.
4. **해시 (Hash)**: 블록의 데이터를 암호화한 고유 값으로, 블록 간의 연결과 데이터 무결성을 보장합니다.

블록체인은 다양한 응용 사례에서 사용될 수 있습니다. 예를 들어:


- **암호화폐 (Cryptocurrency)**: Bitcoin과 Ethereum 같은 암호화폐는 블록체인을 기반으로 하여 탈중앙화된 금융 거래를 가능하게 합니다.
- **공급망 관리**: 블록체인은 제품의 생산부터 배송까지의 모든 과정을 투명하게 추적할 수 있습니다.
- **디지털 신원 인증**: 블록체인은 개인의 디지털 신원을 안전하게 관리하고 검증할 수 있습니다.
- **투표 시스템**: 블록체인은 투표 과정의 투명성과 무결성을 보장하여 부정 투표를 방지할 수 있습니다.

[https://en.wikipedia.org/wiki/Distributed_ledger](https://en.wikipedia.org/wiki/Distributed_ledger)


### References

- [Blockchain 기술 개요](https://m.upbitcare.com/academy/education/blockchain/64)
- [블록체인의 탈중앙화 원리](https://builtin.com/blockchain)
- [블록체인 트랜잭션 검증](https://www.blockchain-council.org/blockchain/how-blockchain-transaction-works/)
- [블록체인의 응용 사례](https://www.ibm.com/blockchain/use-cases)

### Related Keywords

- [[Block]]
- [[Timestamp]]
- [[Node]]
- [[Archive Node]]
- [[Merkle Tree]]
- [[Smart Contract]]
- [[Bitcoin]]
- [[Ethereum]]
- [[Mainnet]]
- [[Testnet]]
- 