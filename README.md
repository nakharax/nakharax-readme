<div align="center">

<img src="assets/nakharax_brand.svg" width="420" alt="nakharax.io" />

<br />

# nakharax.io

A unified protocol ecosystem for verifiable compute, parallel execution, and decentralized AI infrastructure.

[![Website](https://img.shields.io/badge/Website-nakharax.io-29F06A?style=flat-square)](https://nakharax.io)
[![XpFirm](https://img.shields.io/badge/Product-xpfirm.com-111318?style=flat-square&logo=github&logoColor=white)](https://xpfirm.com)
[![Testnet](https://img.shields.io/badge/Testnet-86137-29F06A?style=flat-square)](#network)
[![Status](https://img.shields.io/badge/Status-Active%20Public%20Testnet-FF7A1A?style=flat-square)](#network)
[![License](https://img.shields.io/badge/License-MIT-FF7A1A?style=flat-square)](LICENSE)

</div>

---

## Overview

This repository is the public landing page and navigation hub for the nakharax ecosystem. NakharaX is the parent company, and XpFirm (`xpfirm.com`) is one of its products.

It is intentionally a documentation-first entry point. The actual implementation work lives in the upstream monorepo:

- `axionaxprotocol/nakharax` — core protocol, worker services, SDK, web applications, and deployment tooling

This repository helps visitors understand the mission, find the correct codebase, and track the public status of the project without duplicating upstream implementation work.

> This repository is not the runtime codebase. For protocol implementation, apps, and SDK development, work in the upstream repo and open issues or pull requests there.

---

## Why nakharax

nakharax is designed for verifiable, large-scale workloads across compute-intensive and AI-oriented operations.

The protocol combines:

- a trust layer for settlement and accounting
- a distributed worker layer for compute supply
- probabilistic verification through Proof of Probabilistic Checking (PoPC)
- JSON-RPC and developer-facing interfaces for integrations and tooling

The project intentionally keeps a single monorepo architecture so the protocol, apps, and SDK evolve in sync.

---

## What this repository does

This repo serves as the project front door and organizational reference point. It includes:

- project overview and positioning
- upstream navigation and contribution guidance
- public network and milestone status
- branding and ecosystem identity
- Git submodule tracking for the active monorepo

### Repository structure

```text
axionaxprotocol/nakharax-readme
├── README.md
├── LICENSE
├── AGENTS.md
├── assets/
├── .github/
├── .gitmodules
└── nakharax/      ← submodule: axionaxprotocol/nakharax
```

---

## Project at a glance

- Parent company: NakharaX
- Product: XpFirm (`xpfirm.com`)
- Ecosystem site: `nakharax.io`
- Native token: `NAK`
- Network posture: public testnet active
- Consensus model: `PoPC`
- Core stack: Rust, Python, TypeScript, Next.js, Docker

### Network

- Chain ID: `86137`
- Public RPC: `https://rpc.nakharax.io`
- Status: active public testnet workstream

### Mainnet

- Planned chain ID: `86150`
- Status: roadmap and launch preparation

---

## Architecture map

The project is structured around a single implementation monorepo:

```text
axionaxprotocol/nakharax
├── apps/
│   ├── web/              # public dApp and marketplace experience
│   └── os-dashboard/     # self-hosted node operating interface
├── services/
│   └── core/            # blockchain core and DeAI worker services
├── packages/
│   └── sdk/             # shared TypeScript client and tooling
├── docs/
│   └── ...              # architecture and project documentation
├── scripts/
│   └── ...              # operational tooling
└── README.md
```

This makes it easier to understand where implementation belongs:

- compute and protocol logic → `services/core`
- web and product experiences → `apps`
- developer integrations → `packages`
- cross-cutting product guidance → `docs` and `scripts`

---

## Upstream monorepo

The active development repository is:

- https://github.com/axionaxprotocol/nakharax

It contains the complete system architecture, including:

- `apps/` — web and dashboard apps
- `services/core/` — blockchain core and worker services
- `packages/` — shared SDK and typed clients
- `docs/` — architecture and project documentation
- `scripts/` — deployment and operational tooling

### Clone with submodule

```bash
git clone --recurse-submodules https://github.com/axionaxprotocol/nakharax-readme.git
cd nakharax-readme
```

If you already cloned without submodules:

```bash
git submodule update --init --recursive
```

---

## Brand and identity

The parent company is NakharaX. The project is presented under the `nakharax` brand, and XpFirm (`xpfirm.com`) is one of its products.

| Area | Name |
| :--- | :--- |
| Parent company | NakharaX |
| Product | XpFirm |
| Ecosystem site | nakharax.io |
| Product site | xpfirm.com |
| Former project name | Axionax Protocol |
| Native token | NAK |

---

## Roadmap

| Phase | Focus | Status |
| :--- | :--- | :---: |
| 1 | Foundation and protocol scaffolding | Done |
| 2 | Optimization and hardening | Done |
| 3 | Launch preparation and brand alignment | In progress |
| 4 | Mainnet rollout | Planned |

Project milestones continue to be tracked in the upstream repo and referenced from this landing page.

---

## Quick links

- Website: https://nakharax.io
- Product (XpFirm): https://xpfirm.com
- Upstream repo: https://github.com/axionaxprotocol/nakharax
- Issues: https://github.com/axionaxprotocol/nakharax/issues
- Pull requests: https://github.com/axionaxprotocol/nakharax/pulls
- Docs: https://nakharax.io

---

## Contributing

This landing repo is not where protocol implementation occurs. If you want to contribute to:

- blockchain logic and validator code → `nakharax/services/core`
- web or product UI work → `nakharax/apps`
- shared SDK work → `nakharax/packages`
- deployment or operational tooling → `nakharax/scripts`

please work in the upstream repository and open a pull request there.

---

## License

This repository is distributed under the MIT license. See [LICENSE](LICENSE) for the full text.

The upstream implementation repo is maintained separately and may carry project-specific licensing terms by subtree or module.

---

<div align="center">

[![Website](https://img.shields.io/badge/nakharax.io-29F06A?style=for-the-badge&logo=googlechrome&logoColor=white)](https://nakharax.io)
[![XpFirm](https://img.shields.io/badge/xpfirm.com-111318?style=for-the-badge&logo=github&logoColor=white)](https://xpfirm.com)

<sub>Landing page for nakharax.io · parent company NakharaX · product XpFirm (xpfirm.com) · maintained as a documentation and navigation entry point.</sub>

</div>
