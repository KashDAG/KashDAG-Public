# KashDAG public progress

Last updated: 2026-08-12

## Operational public-testnet foundation

The following public-beta milestones have been completed:

- Signed RC12 Linux x86_64 and ARM64 testnet validator packages have published checksums, Sigstore bundles, release provenance, and operator verification instructions.
- Three-validator quorum finalizes matching checkpoints, state roots, and validator snapshots.
- Restart, quorum-loss, partition/rejoin, and state-recovery trials passed within the defined public-beta scope.
- Validator services persist across host restarts and use restricted networking and loopback-only application interfaces.
- Automated validator health checks, off-host backups, and PostgreSQL backups are active.
- The finalized-state indexer synchronizes public RPC state and supports bounded pagination and replacement-indexer comparison.
- The branded explorer serves transactions, finalized checkpoints, accounts, validators, receipts, and network status.
- The self-custody wallet reads live finality, stores accounts in an encrypted local vault, signs locally, supports backup and recovery, and completed a finalized end-to-end testnet transfer.
- Mobile wallet layouts and Progressive Web App behavior have been improved for public beta testing.
- The controlled faucet passed concurrency and allocation qualification and remains publicly disabled.
- Public website, wallet PWA, RPC, indexer, explorer, identity agreement, and finality progression are covered by external monitoring.

## Protocol v2 engineering milestone

The Protocol v2 engineering milestone is complete. Its scope includes validator economics, delegation and unbonding, deterministic reward accounting, validator accountability, governance and treasury controls, fungible and non-fungible assets, deterministic WASM contract execution, and the associated protocol, storage, RPC, indexer, SDK, explorer, and wallet integration boundaries.

Protocol v2 is not yet active on the public testnet. Protocol v1 remains authoritative until the versioned activation manifest, migration and rollback qualification, approved parameters, matching multi-validator execution evidence, release artifacts, and required independent reviews complete.

## Current operating boundary

KashDAG is a public testnet beta, not a production or mainnet network.

- Testnet balances have no monetary value.
- The faucet is not publicly available.
- Validator participation is presently controlled while independent-operator onboarding is qualified.
- Public endpoints are subject to testnet maintenance and capacity limits.
- Protocol v2 smart contracts, staking, governance, and economics remain inactive until the coordinated activation gate completes.
- Bridges and advanced interoperability remain later gated milestones.
- Audit-readiness work does not mean an independent audit has been completed.
- Independent security review remains required before production or mainnet representation.

## Next active work

- Qualify and execute the coordinated Protocol v2 public-testnet activation process.
- Collect longer-duration public load, WebSocket, synchronization, and recovery evidence.
- Complete live onboarding with a truly independent validator operator.
- Finish physical-device wallet testing and independent wallet review.
- Complete independent protocol, economics, runtime, and infrastructure audits and remediation confirmation.
- Freeze approved production economic, governance, legal, and operational policies before any mainnet decision.

Progress statements describe completed evidence only; planned or inactive capabilities are not represented as live.
