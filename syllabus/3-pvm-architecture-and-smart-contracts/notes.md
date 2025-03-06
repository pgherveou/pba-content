dule 3: PVM Architecture & Smart Contracts

## Resources

Alex Contracts on Asset Hub:
- https://docs.google.com/document/d/15qmVto_fq0aPuA1yZqFMV1wQmJB_k1Pv_91gSFsBYXA/edit?tab=t.0#heading=h.kefs2tafvuan
- https://forum.polkadot.network/t/contracts-on-assethub-roadmap/9513/27

Alex's presentation on pallet-revive (sub0):
https://www.youtube.com/watch?v=ahtBhzwmjY4&t=1221s

Alex's PBA Buenos Aires
https://www.youtube.com/watch?v=YZp1-w1956U

Cyrill's presentation on revive (sub0):
https://www.youtube.com/watch?v=GPuTt10dxKI

Jan's polkavm pba presentation:
https://www.youtube.com/watch?v=MwLNgVPtvA8&t=3926s

## Schedule


1. History of Smart Contracts
  - Smart Contract vs Wasm runtime model
  -  Permission vs Permissionless deployment
  - Synchronous state vs shared state & asynchronous composition

2. Future of Smart Contracts on Polkadot
  - Native contracts on Asset Hub
  - History of Contracts on Substrate
    Frontier -> pallet-contracts -> pallet-revive
    Ink! -> EVM ABI contracts

2. PVM:
  - Innovations
  - Why not (no longer) Wasm
  - Revive compiler

2. Pallet-revive architecture
  - Differences with EVM
    - Address mapping
    - Gas vs Weight
    - gas estimation and encoding in lower digits
- EVM compatibility layer
- Lifecycle of a contract
  - Deployment
  - Execution
  - Contracts call & Solidity ABI
  - Interfacing with other pallets through precompiles

3. Building a contract
- The hard way: Raw contract with Rust + uapi crate (can also be practical already)
- Tooling: Remix, Foundry,
- Libs (ethers, viem, web3, ...)


4. Hackathon: Building a contract

