<div align="center">

<img src="https://bridgelet.vercel.app/logo.png" alt="Bridgelet" width="120" />

# Bridgelet

**Ephemeral accounts for onboarding non-crypto users into Stellar**

[![Frontend CI](https://github.com/bridgelet-org/bridgelet/actions/workflows/frontend-ci.yml/badge.svg)](https://github.com/bridgelet-org/bridgelet/actions/workflows/frontend-ci.yml)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://github.com/bridgelet-org/bridgelet/blob/main/LICENSE)
[![Website](https://img.shields.io/badge/Website-bridgelet.vercel.app-1e2327?logo=vercel)](https://bridgelet.vercel.app/)

</div>

---

## What is Bridgelet?

Bridgelet is an open-source infrastructure SDK that lets organizations send payments to recipients who don't have crypto wallets yet. It creates secure, single-use Stellar accounts that automatically bridge recipients into permanent wallets when they claim funds — no seed phrases, no upfront wallet setup, no friction.

It's built for mass payment scenarios: payroll, aid disbursements, airdrops, and remittances, where requiring recipients to understand crypto concepts upfront just doesn't work.

**The problem:** Mass payments fail when recipients don't have wallets or understand seed phrases.
**The solution:** Temporary accounts recipients can claim without any crypto knowledge, with funds auto-swept to a permanent wallet.

## Key Features

- ✅ Single-use ephemeral Stellar accounts
- ✅ No seed phrase management for recipients
- ✅ Automatic sweep to permanent wallets
- ✅ Time-based expiration with fund recovery
- ✅ Composable with existing payment platforms (e.g. Stellar Disbursement Platform)

## Our Repositories

| Repo | Description |
|---|---|
| [**bridgelet-core**](https://github.com/bridgelet-org/bridgelet-core) | Soroban smart contracts (Rust) enforcing on-chain restrictions |
| [**bridgelet-sdk**](https://github.com/bridgelet-org/bridgelet-sdk) | Backend SDK & API (NestJS + TypeScript) |
| [**bridgelet**](https://github.com/bridgelet-org/bridgelet) | Reference UI (Next.js 16+, TypeScript, Tailwind CSS) + docs |

## Status

🚧 **Early Development** — building core primitives. Current phase: MVP implementation.

Check out the [Public Roadmap](https://github.com/bridgelet-org/bridgelet/blob/main/ROADMAP.md) for what's next.

## Get Involved

We welcome contributors! Areas of interest:

- Soroban smart contract development
- Financial infrastructure for emerging markets
- Developer experience & SDK design

See [CONTRIBUTING.md](https://github.com/bridgelet-org/bridgelet/blob/main/CONTRIBUTING.md) and our [Code of Conduct](https://github.com/bridgelet-org/bridgelet/blob/main/CODE_OF_CONDUCT.md) to get started.

## Links

- 🌐 [Website](https://bridgelet.vercel.app/)
- 📋 [Issues](https://github.com/bridgelet-org/bridgelet/issues)
- 💬 [Discussions](https://github.com/bridgelet-org/bridgelet/discussions)
- 📧 [aminubabafatima8@gmail.com](mailto:aminubabafatima8@gmail.com)

---

<div align="center">
Built for the Stellar ecosystem 🌟
</div>
