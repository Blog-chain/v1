---
title: Block
description: 블록체인에서 블록의 개념, 구조, 및 역할을 다룹니다.
aliases: [block, blockchain block]
tags: [technology, blockchain, block]
date: 2024-07-22
---

## Block

### Summary

`Block`은 블록체인의 구성 요소로, 트랜잭션 데이터를 포함하고 이전 블록의 해시 값을 연결하여 체인을 형성합니다.

### Description

`Block`은 블록체인의 기본 단위로, 트랜잭션 데이터를 포함하는 데이터 구조입니다. 각 블록은 다음과 같은 주요 요소로 구성됩니다:

1. **블록 헤더 (Block Header)**: 블록 헤더는 블록의 메타데이터를 포함합니다. 여기에는 이전 블록의 해시, 타임스탬프, 난이도, 논스 등이 포함됩니다. 예를 들어, Bitcoin 블록체인의 블록 헤더는 80바이트 크기로 고정되어 있습니다.
2. **트랜잭션 리스트 (Transaction List)**: 블록에 포함된 모든 트랜잭션의 목록입니다. Ethereum 블록체인에서는 이 리스트가 더 복잡한 스마트 계약과 함께 작동합니다.
3. **머클 루트 (Merkle Root)**: 트랜잭션 리스트의 해시 값을 트리 형태로 요약한 값으로, 블록 내 트랜잭션의 무결성을 보장합니다. Merkle Tree를 사용하여 트랜잭션의 무결성을 효율적으로 검증할 수 있습니다.

블록은 이전 블록의 해시 값을 포함하여 체인 형태로 연결되며, 이는 블록체인의 **불변성**과 **보안성**을 보장합니다. 새로운 블록이 생성될 때마다, 해당 블록은 블록체인의 끝에 추가되어 전체 원장의 최신 상태를 유지합니다.

- Block height
    - The block number and length of the blockchain (in blocks) on creation of the current block
- Timestamp
    - The time at which a block was proposed
- Transactions
    - The number of transactions included within the block
- Fee recipient
    - The address that received gas fee tips from transactions
- Block Reward
	- The amount of ETH awarded to the validator who proposed the block
- Size
	- The size of the data within the block (measured in bytes)
- Gas used
	- The total units of gas used by the transactions in the block
- Gas limit
	- The total gas limits set by the transactions in the block
- Base fee per gas
	- The minimum multiplier required for a transaction to be included in a block
- Burnt fees
	- How much ETH is burned in the block
- Extra data
	- Any extra data the miner has included in the block

### Advanced data

- Hash
	- The cryptographic hash that represents the block header (the unique identifier of the block)
- Parent hash
	- The hash of the block that came before the current block
- StateRoot
	- The root hash of Merkle trie which stores the entire state of the system

[https://ethereum.org/en/developers/docs/data-and-analytics/block-explorers/#execution-data](https://ethereum.org/en/developers/docs/data-and-analytics/block-explorers/#execution-data) |


### References

- [블록의 개념과 역할](https://bitcoinwiki.org/wiki/block)
- [Ethereum 블록의 구조](https://ethereum.org/en/developers/docs/blocks/)
- [블록 헤더의 구성 요소](https://www.investopedia.com/terms/b/block-bitcoin-block.asp)
- [블록체인의 불변성 원리](https://www.investopedia.com/news/what-genesis-block-bitcoin-terms/)

### Related Keywords

- [[Blockchain]]
- [[Timestamp]]
- [[Node]]
- [[Merkle Tree]]
- [[Bitcoin]]
- [[Ethereum]]
---
title: Block
description: 블록체인에서 블록의 개념, 구조, 및 역할을 다룹니다.
aliases: [block, blockchain block]
tags: [technology, blockchain, block]
date: 2024-07-22
---

## Block

### Summary

`Block`은 블록체인의 구성 요소로, 트랜잭션 데이터를 포함하고 이전 블록의 해시 값을 연결하여 체인을 형성합니다.

### Description

`Block`은 블록체인의 기본 단위로, 트랜잭션 데이터를 포함하는 데이터 구조입니다. 각 블록은 다음과 같은 주요 요소로 구성됩니다:

1. **블록 헤더 (Block Header)**: 블록 헤더는 블록의 메타데이터를 포함합니다. 여기에는 이전 블록의 해시, 타임스탬프, 난이도, 논스 등이 포함됩니다. 예를 들어, Bitcoin 블록체인의 블록 헤더는 80바이트 크기로 고정되어 있습니다.
2. **트랜잭션 리스트 (Transaction List)**: 블록에 포함된 모든 트랜잭션의 목록입니다. Ethereum 블록체인에서는 이 리스트가 더 복잡한 스마트 계약과 함께 작동합니다.
3. **머클 루트 (Merkle Root)**: 트랜잭션 리스트의 해시 값을 트리 형태로 요약한 값으로, 블록 내 트랜잭션의 무결성을 보장합니다. Merkle Tree를 사용하여 트랜잭션의 무결성을 효율적으로 검증할 수 있습니다.

블록은 이전 블록의 해시 값을 포함하여 체인 형태로 연결되며, 이는 블록체인의 **불변성**과 **보안성**을 보장합니다. 새로운 블록이 생성될 때마다, 해당 블록은 블록체인의 끝에 추가되어 전체 원장의 최신 상태를 유지합니다.

### References

- [블록의 개념과 역할](https://bitcoinwiki.org/wiki/block)
- [Ethereum 블록의 구조](https://ethereum.org/en/developers/docs/blocks/)
- [블록 헤더의 구성 요소](https://www.investopedia.com/terms/b/block-bitcoin-block.asp)
- [블록체인의 불변성 원리](https://www.investopedia.com/news/what-genesis-block-bitcoin-terms/)

### Related Keywords

- [[Blockchain]]
- [[Timestamp]]
- [[Node]]
- [[Merkle Tree]]
- [[Bitcoin]]
- [[Ethereum]]
