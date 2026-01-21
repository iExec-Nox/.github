# Nox - Confidential Protocol

[![DOCS](https://img.shields.io/badge/DOCS-03BE09)](#)
[![DISCORD](https://img.shields.io/badge/DISCORD-purple)](https://discord.gg/66px3TjtGT)
[![X](https://img.shields.io/badge/X-000000)](https://x.com/iEx_ec)

> **Nox** is a **multichain confidential execution protocol for DeFi**.

Nox Protocol builds the first truly on-chain composable privacy layer for DeFi, multichain, multi-privacy. Gas-efficient confidential computation at blockchain speed: like HTTPS made secure connections invisible, Nox makes privacy the default. 
Seamless for users, effortless for builders who can develop and monetize their own confidential functions, auditable for regulators.

## 🔐 How Nox Works

- Smart contracts manipulate **handles** instead of plaintext values
- Sensitive data is processed inside Runners (**attested TEEs**)
- A **threshold KMS** ensures no single party can decrypt data
- **On-chain ACLs** make permissions explicit, auditable, and revocable

## 🧩 Protocol Architecture

- **Registry (on-chain):** tracks attested protocol components in TEE
- **Handle Gateway (TEE):** encrypts, decrypts, and manages handles
- **KMS (threshold):** distributed key management & re-encryption
- **Orchestrator & Ingestor:** assign confidential tasks
- **Runners (TEE):** execute confidential computations

## 💡 What You Can Build With Nox


- Yield with Confidential Vault
- cRWA with confidential Tokenized Equity on-chain
- Confidential value transfers
- Privacy-preserving DeFi primitives
- Tokens with hidden balances & amounts
- Selective disclosure workflows (audit, compliance)
- Institutional-grade DeFi & RWAs

## ⚡ Product Quick Start - Confidential Token

> This quick start focuses on the **first Nox-based product**: a **Confidential ERC-20** compliant with **OpenZeppelin's ERC-7984** standard.
> It demonstrates how the Nox protocol can be used in practice, without requiring you to understand or operate the full protocol stack.

With this quick start, you will:

- Wrap a standard ERC-20 into a **confidential token**
- Execute **private transfers** (hidden balances & amounts)
- Grant **viewing permissions** via on-chain ACL
- Interact with confidential data using the Nox SDK

## 💻 Dev Tools

> Developer tooling to interact with the Nox protocol and its products.

| Tool                 | Description                                                     |
| -------------------- | --------------------------------------------------------------- |
| Nox Solidity Library | Interfaces and helpers to interact with confidential primitives |
| Nox SDK              | Encrypt inputs, request confidential compute, decrypt outputs   |
| Nox Smart Contracts  | Core protocol contracts                                         |
| Examples & Starters  | Reference integrations and demos                                |

## 🔗 Useful Links

| Link         | Description                              |
| ------------ | ---------------------------------------- |
| Docs         | Protocol concepts, guides, SDK reference |
| Specs        | Protocol & smart contract specifications |
| Architecture | System design & workflows                |
| Roadmap      | Upcoming milestones                      |

---

### Get Started

- Start with the **Confidential Token Quick Start** to experience Nox in action
- Dive deeper into **protocol concepts** once familiar
- Join the **Nox chan** in iExec Discord for support and updates

> **Nox is the foundation. Products are just the beginning.**
