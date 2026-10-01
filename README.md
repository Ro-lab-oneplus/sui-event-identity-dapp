# Sui Event Identity & Access Control dApp

A production-ready decentralized application for managing digital identity and access control in event management systems using Sui blockchain and EVM smart contracts.

## Project Structure

```
├── contracts/
│   ├── sui/                 # Sui Move smart contracts
│   └── evm/                 # Solidity/Hardhat contracts
├── frontend/                # Next.js + TypeScript + Tailwind
└── docs/                    # Documentation
```

## Quick Start

### Prerequisites
- Node.js >= 18
- pnpm >= 8
- Sui CLI (for Move contracts)
- Hardhat (for EVM contracts)

### Installation

```bash
pnpm install
```

### Development

```bash
# Sui Move contracts
cd contracts/sui
pnpm build

# EVM Contracts
cd contracts/evm
pnpm hardhat compile

# Frontend
cd frontend
pnpm dev
```

## Features

- ✅ Role-Based Access Control (RBAC) using Capability Pattern
- ✅ NFT-based Digital Tickets with restricted transfers
- ✅ zkLogin integration for Web2-to-Web3 authentication
- ✅ QR code generation and scanning
- ✅ Real-time check-in verification
- ✅ Multi-chain support (Sui + EVM)
- ✅ Responsive Dashboard UI

## Security Features

- Capability-based access control (Sui)
- Role-based authorization (EVM)
- Non-reentrant patterns
- Event emission for audit trails
- Signature verification for QR codes
