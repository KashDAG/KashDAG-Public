# KashDAG public roadmap

The roadmap is evidence-driven. Dates are not promised until the relevant technical, operational, security, economic, legal, and governance gates are satisfied.

## Phase 1 — Foundation

**Status: completed for public-beta scope**

- Deterministic Layer-1 protocol foundation
- Canonical transactions and Ed25519 identities
- DAG execution and checkpoint finality
- Persistent node state and recovery boundaries
- Wallet PWA and explorer foundation
- Signed multi-architecture release pipeline

## Phase 2 — Distributed public testnet

**Status: active public beta**

- Three-validator quorum
- Public RPC, finalized-state indexer, wallet, and explorer
- Signed RC12 Linux x86_64 and ARM64 operator packages
- Restart, partition/rejoin, quorum-loss, and recovery qualification
- Monitoring, bounded public access, and off-host backups
- Controlled faucet qualification
- Public progress and network reporting

**Remaining gates:** longer-duration public load and WebSocket evidence, live replacement and recovery rehearsals, and continued service-stability observations.

## Phase 3 — Developer and operator expansion

**Status: active and gated**

- Public validator package and verification instructions published
- RPC, SDK, pagination, history, subscription, and fee-estimation stabilization in progress
- Independent-operator acceptance and expanded independently operated infrastructure pending
- Additional integration documentation and examples planned
- Physical-device wallet qualification and independent wallet review pending

## Phase 4 — Protocol expansion

**Status: development candidates built; public activation closed**

Candidate work covers:

- Validator economics, delegation, unbonding, rewards, and slashing accounting
- Governance, treasury, and snapshot-bound voting
- Fungible and non-fungible asset foundations
- Deterministic WASM contract execution
- Read-only indexer, SDK, explorer, and wallet audit surfaces

These candidates are not active on the public testnet. Activation requires explicit protocol versioning, migration and rollback rules, approved parameters, multi-validator adversarial trials, and independent security and economic review.

## Phase 5 — Production and mainnet

**Status: not launched; gates remain closed**

Mainnet requires, at minimum:

- Independent protocol, wallet, runtime, economics, and infrastructure security audits
- Confirmed remediation and retesting
- Long-duration public-testnet evidence
- Independent validator participation
- Frozen production protocol, economic, governance, and operational parameters
- Production legal and regulatory review
- Mature incident response and disaster recovery
- Reproducible production genesis ceremony
- Explicit KashDAG launch authorization

Public-testnet progress does not satisfy or bypass these mainnet gates.
