# Cowrie Token (CWR)

**Cowrie (CWR)** is an asset-backed, community-first ERC-20 token designed to serve underrepresented and low-bandwidth communities with secure, transparent, and equitable access to digital finance.

## 🔐 Smart Contract Overview

- **Token Standard**: ERC-20
- **Symbol**: `CWR`
- **Supply Model**: Mintable/Burnable (Role-gated)
- **Governance**: Multisig + Timelocked functions
- **Emergency**: Pausable fallback mechanism

## 📂 Project Structure

- `/contracts`: Solidity smart contracts
- `/scripts`: Deployment scripts (Hardhat)
- `/test`: Unit and integration tests
- `SECURITY.md`: Risk surface and mitigation strategy
- `audit-summary.md`: Placeholder for audit response

## 🚀 Deployment

Deploy to testnet using Hardhat:

```bash
npx hardhat run scripts/deploy.js --network sepolia
```

## ✅ Next Steps

1. Finalize multisig integration
2. Add Oracle/Bridge integration for asset backing (off-chain reference)
3. Request audit from Blocksecur.io
