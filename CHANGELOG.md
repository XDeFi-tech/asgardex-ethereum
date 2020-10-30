# v.0.2.0 (2020-10-06)

-## Add:

- `setVault`
- `vaultTx`
- `normalTx`
- `erc20Tx`
- `estimateNormalTx`
- `estimateGasERC20Tx`
- `getERC20Balance`
- `getTransactionCount`
- Optional `vault?: string` parameter of constructor

## Breaking changes:

- Remove `get address` in favour of `getAddress`
- Remove `get balance()` in favour of using `getBalance` only
- Remove `init()`
- `ethers` has been moved from `dependencies` to `peerDependencies`

## Misc.:

- Update for using latest `ethers@5x`

# v.0.1.0 (2020-05-28)

First release
