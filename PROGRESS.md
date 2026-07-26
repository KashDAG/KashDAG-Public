# KashDAG public progress

Last updated: 2026-07-26

## Operational public-testnet foundation

The following public-beta milestones have been completed:

- A signed RC9 testnet release is installed across three validator identities.
- Linux x86_64 and ARM64 release artifacts have reproducible checksums and an
  operator signature.
- Three-host quorum finalizes matching checkpoints, state roots, and validator
  snapshots.
- Restart, quorum-loss, partition/rejoin, and state-recovery trials passed
  within the defined public-beta scope.
- Validator services persist across host restarts and use restricted
  networking and loopback-only application interfaces.
- Automated validator health checks, off-host backups, and PostgreSQL backups
  are active.
- The PostgreSQL finalized-state indexer is synchronized with public RPC state.
- The branded explorer serves finalized checkpoints, accounts, validators, and
  receipts.
- The self-custody wallet reads live finality, stores its key in an encrypted
  local vault, signs locally, and completed a finalized end-to-end testnet
  transfer.
- The controlled faucet passed concurrency and allocation qualification and is
  publicly disabled.
- Public website, wallet PWA, RPC, indexer, explorer, identity agreement, and
  finality progression are checked by an external GitHub-hosted monitor.

## Current operating boundary

KashDAG is a public testnet beta, not a production or mainnet network.

- Testnet balances have no monetary value.
- The faucet is not publicly available.
- Validator participation is presently controlled while operator onboarding is
  prepared.
- Public endpoints are subject to testnet maintenance and capacity limits.
- Smart contracts, staking, governance, production token economics, bridges,
  and advanced interoperability remain gated milestones.
- Independent security review remains required before production or mainnet
  representation.

## Next active work

- Publish operator-focused validator onboarding documentation.
- Expand independently operated validator participation.
- Continue RPC and SDK stabilization.
- Add longer-duration public load and recovery observations.
- Complete production security, legal, economic, and governance review gates.

Progress statements describe completed evidence only; planned capabilities are
not represented as live.
