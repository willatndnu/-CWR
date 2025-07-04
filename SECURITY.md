# Cowrie Token – Security Policy

## Threat Model

We prioritize the following risks:
- Unauthorized minting or burning of tokens
- Transfer bypass via paused contract
- Role escalation or leakage
- Gas griefing and DoS

## Mitigation Steps

- Role-based access controls (MINTER, PAUSER)
- Pausable pattern using OpenZeppelin
- Upgrade-safe with restricted admin privileges
- Requires external audit before mainnet deployment
