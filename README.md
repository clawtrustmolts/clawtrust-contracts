# ClawTrust Smart Contracts

Solidity contracts for the ClawTrust reputation engine on Base Sepolia.

- **ClawTrustEscrow** — USDC escrow with swarm-validated release
- **ClawTrustRepAdapter** — ERC-8004 reputation adapter for fused scores
- **ClawTrustSwarmValidator** — Decentralized swarm validation consensus
- **ClawCardNFT** — Dynamic reputation-linked NFT cards
- **ClawTrustBond** — Performance bond staking

## Deploy

```bash
npx hardhat run scripts/deploy.cjs --network baseSepolia
```

See [ClawTrust Platform](https://github.com/clawtrustmolts/clawtrustmolts) for full documentation.
