<div align="center">

<img src="assets/nakharax_brand.svg" width="420" alt="nakharax.com" />

<br />

# nakharax.com

A single, unified protocol ecosystem for compute, verification, and decentralized AI infrastructure.

[![Website](https://img.shields.io/badge/Website-nakharax.com-29F06A?style=flat-square)](https://nakharax.com)
[![XPfirm](https://img.shields.io/badge/Parent-xpfirm.com-111318?style=flat-square&logo=github&logoColor=white)](https://xpfirm.com)
[![Testnet](https://img.shields.io/badge/Testnet-86137-29F06A?style=flat-square)](#network)
[![License](https://img.shields.io/badge/License-MIT-FF7A1A?style=flat-square)](LICENSE)

</div>

---

## Overview

This repository is the organization and project landing page for nakharax.com, operated under the broader xpfirm.com ecosystem.

It is intentionally a documentation and navigation repository. The actual implementation work lives in the upstream monorepo:

- `axionaxprotocol/nakharax` — Rust core, Python worker services, TypeScript SDK, web apps, and deployment tooling

This repo helps visitors understand the project, connect to the right codebase, and track the public status of the initiative.

> This repository is not the runtime codebase. For implementation work, clone the upstream repo and open issues or pull requests there.

---

## What nakharax is

nakharax.com is a decentralized compute network designed for large-scale, verifiable parallel workloads such as scientific compute, AI inference, and distributed job execution.

The design combines:

- a blockchain settlement layer for trust and accounting
- a distributed worker network for compute supply
- verification through Proof of Probabilistic Checking (PoPC)
- an on-chain / JSON-RPC interface designed for modern tooling and integrations

The project is built around a single monorepo architecture to keep the protocol, applications, and SDK aligned.

---

## Repository role

This repository serves as the project landing page and organizational entry point. It includes:

- project overview and roadmap
- status updates and navigation to the real implementation repo
- public-facing branding and domain references
- the Git submodule pointer to the upstream monorepo

### Structure

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

## Upstream monorepo

The active development repository is:

- https://github.com/axionaxprotocol/nakharax

The upstream monorepo contains the complete system architecture, including:

- `apps/` — web and dashboard applications
- `services/core/` — blockchain core and worker services
- `packages/` — shared SDK and typed clients
- `docs/` — architecture and project documentation
- `scripts/` — operational tooling

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

The project is presented under the nakharax brand, with xpfirm.com as the broader organization and operating umbrella.

Key naming details:

| Area | Name |
| :--- | :--- |
| Product site | nakharax.com |
| Organization site | xpfirm.com |
| Former project name | Axionax Protocol |
| Token | NAK |

---

## Network status

### Testnet

- Chain ID: `86137`
- Public RPC: `https://rpc.nakharax.io`
- Primary product status: active public testnet workstream

### Mainnet

- Planned mainnet chain ID: `86150`
- Current posture: roadmap and launch preparation

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

- Product: https://nakharax.com
- Organization: https://xpfirm.com
- Upstream repo: https://github.com/axionaxprotocol/nakharax
- Issues: https://github.com/axionaxprotocol/nakharax/issues
- Pull requests: https://github.com/axionaxprotocol/nakharax/pulls
- Docs: https://nakharax.com

---

## Contributing

This landing repo is not where protocol implementation occurs. If you want to contribute to:

- blockchain logic and validator code → `nakharax/services/core`
- web or dashboard work → `nakharax/apps`
- shared SDK work → `nakharax/packages`
- deployment or operational tooling → `nakharax/scripts`

please work in the upstream repository and open a pull request there.

---

## License

This repository is distributed under the MIT license. See [LICENSE](LICENSE) for the full text.

The upstream implementation repo is separately maintained and may carry project-specific licensing terms by subtree or module.

---

<div align="center">

[![Website](https://img.shields.io/badge/nakharax.com-29F06A?style=for-the-badge&logo=googlechrome&logoColor=white)](https://nakharax.com)
[![XPfirm](https://img.shields.io/badge/xpfirm.com-111318?style=for-the-badge&logo=github&logoColor=white)](https://xpfirm.com)

<sub>Organization landing page for nakharax.com under xpfirm.com · maintained as a documentation and navigation entry point.</sub>

</div>
