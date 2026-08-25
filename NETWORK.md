# KashDAG Control Mainnet

## Identity

| Field | Value |
| --- | --- |
| Chain ID | `kashdag-mainnet` |
| Protocol version | `2` |
| Active validator identities | `3` |
| Independent onboarding release | `mainnet-v0.2.0-rc8.6-linux` |
| Native asset | `KDG` |
| Display precision | 9 decimal places |
| Account identity | Ed25519 public key |
| Finality model | Validator-certified checkpoints |

## Public endpoints

| Purpose | Endpoint |
| --- | --- |
| RPC base | `https://rpc.kashdag.com/rpc` |
| Redundant RPC base | `https://rpc2.kashdag.com/rpc` |
| RPC health | `https://rpc.kashdag.com/rpc/health` |
| RPC status | `https://rpc.kashdag.com/rpc/status` |
| Indexer base | `https://indexer.kashdag.com/api/indexer` |
| Redundant indexer base | `https://indexer2.kashdag.com/api/indexer` |
| Explorer | `https://explorer.kashdag.com` |
| Wallet | `https://wallet.kashdag.com` |

Only documented routes are supported. Endpoint availability, data retention,
rate limits, and response formats follow the published compatibility policy.

## Finality

Transaction submission is not finality. A transaction should be represented as
finalized only after its receipt is present in a certified finalized
checkpoint and is visible through the authoritative RPC/indexer data path.

Protocol v2 is reconciled across all three canonical validator hosts using
matching finalized checkpoints, state roots, and validator snapshots. A new
operator starts as an isolated observer candidate and is not a voting validator
until a finalized atomic lifecycle transition updates both registry and next
snapshot.

## Safety

- Never share wallet passwords, private keys, or recovery material.
- Verify that links use the `kashdag.com` domain before interacting.
- Verify the signed release, checksum manifest, chain ID, and guardian-approved
  checkpoint before starting an independent node.
