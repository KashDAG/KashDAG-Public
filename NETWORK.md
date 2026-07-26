# KashDAG public testnet

## Identity

| Field | Value |
| --- | --- |
| Chain ID | `dag-l1-testnet-2` |
| Protocol version | `1` |
| Native test asset | `KDG` |
| Display precision | 9 decimal places |
| Account identity | Ed25519 public key |
| Finality model | Validator-certified checkpoints |

## Public endpoints

| Purpose | Endpoint |
| --- | --- |
| RPC base | `https://rpc.testnet.kashdag.com/rpc` |
| RPC health | `https://rpc.testnet.kashdag.com/rpc/health` |
| RPC status | `https://rpc.testnet.kashdag.com/rpc/status` |
| Indexer base | `https://indexer.testnet.kashdag.com/api/indexer` |
| Explorer | `https://explorer.kashdag.com` |
| Wallet | `https://wallet.kashdag.com` |

Only documented routes are supported. Endpoint availability, data retention,
rate limits, and response formats may change during public-testnet development.

## Finality

Transaction submission is not finality. A transaction should be represented as
finalized only after its receipt is present in a certified finalized
checkpoint and is visible through the authoritative RPC/indexer data path.

## Safety

- Never send real assets to KashDAG testnet addresses.
- Never treat KDG testnet balances as investments or monetary instruments.
- Never share wallet passwords, private keys, or recovery material.
- Verify that links use the `kashdag.com` domain before interacting.
