<div align="center">

<img src="assets/nakharax_brand.svg" width="420" alt="NakharaX brand" />

# NakharaX

**Building trustworthy infrastructure for verifiable compute and practical AI.**

NakharaX is the parent company and ecosystem steward. **XpFirm is one of its products.**

[![NakharaX](https://img.shields.io/badge/Website-nakharax.com-29F06A?style=flat-square)](https://nakharax.com)
[![XpFirm](https://img.shields.io/badge/Product-XpFirm-111318?style=flat-square)](https://xpfirm.com)
[![Testnet](https://img.shields.io/badge/Testnet-Chain%2086137-FF7A1A?style=flat-square)](#network-status-and-trust)
[![Mainnet](https://img.shields.io/badge/Mainnet-Not%20launched-555555?style=flat-square)](#network-status-and-trust)
[![License](https://img.shields.io/badge/Docs-MIT-555555?style=flat-square)](LICENSE)

</div>

---

## About the ecosystem

**NakharaX** is the parent company. Its work spans decentralized infrastructure, verifiable computing and AI-enabled products. The company, protocol and products are distinct: a protocol milestone must not be presented as proof that a customer product is production-ready.

| Area | Role | Link |
| :--- | :--- | :--- |
| NakharaX | Parent company and ecosystem | [nakharax.com](https://nakharax.com) |
| NakharaX Protocol | Experimental Layer-1 and decentralized compute infrastructure | [Protocol portal](https://nakharax.com) |
| XpFirm | Trading risk-management and performance workspace; a NakharaX product | [xpfirm.com](https://xpfirm.com) |

The protocol was previously known as **Axionax Protocol**. The native testnet asset is referred to as **tNAK**; use network and token identifiers in their proper context, and do not imply that a mainnet token has launched.

This repository is a **documentation and navigation landing page**, not a production runtime or the complete source tree.

## What the protocol is working toward

NakharaX Protocol explores:

- Distributed compute workers and AI-oriented workload orchestration
- Verification and accounting for compute execution, including PoPC research
- A Layer-1 network and JSON-RPC developer interfaces
- Marketplace, SDK and operator tooling with explicit production-readiness gates

These describe the project's direction and available development surfaces, **not a blanket claim that every feature is available on the public network**. Portal routes, simulated demonstrations, local contract tests and deployed on-chain functionality must be distinguished.

## Network status and trust

| Item | Current documented posture |
| :--- | :--- |
| Public testnet chain ID | `86137` (`0x15079`) |
| RPC endpoint | [rpc.nakharax.com](https://rpc.nakharax.com) |
| Testnet availability | **Verify live** before relying on it; reachability alone is not proof of advancing blocks or finality |
| Mainnet chain ID | `86150` — reserved; **Mainnet not launched** |
| Marketplace | Functionality varies by version and environment; do not equate local fixtures with a public deployment |
| Performance and finality | Benchmarks and assurances require dated, reproducible evidence |

**Evidence boundary:** The protocol's operational-status document was reviewed on **2 October 2026** and recorded a failed read-only liveness check (11 of 12 checks passed; block freshness failed). An older successful sample does not establish the network's state today. Before claiming healthy consensus, live marketplace operation or production readiness, obtain a new dated verification. The protocol's current-status and architecture-gate documents are maintained with the implementation source, which may require repository access.

The public [protocol portal](https://nakharax.com) exposes network tools and interfaces, but the website's labels or demo content are not substitutes for independently checked network evidence.

## Engineering and release posture

- **Testnet:** experimental; operational liveness, validator independence and finality need ongoing qualification.
- **Mainnet:** gated, not live. Do not publish a release date as a commitment.
- **Marketplace and AI workloads:** distinguish live/testnet evidence from local-only, mock and future capabilities.
- **Source of truth:** implementation code, dated operational reports, CI evidence and release gates take precedence over marketing copy and historic roadmap targets.

## Repository guide

```text
nakharax/nakharax-readme
├── README.md                 # This public landing page
├── AGENTS.md                 # Editing guidance
├── .github/                 # Contributor/editor instructions
├── assets/                  # Brand artwork
├── LICENSE                  # License for this repository
├── .gitmodules              # Pinned submodule configuration
└── nakharax/                # Git submodule (pinned revision)
```

The implementation project includes node/consensus and worker components, operator tooling, contracts, SDKs, an OS dashboard and technical documentation. The implementation repository is maintained separately and **may require access**.

**Submodule note:** The existing `nakharax/` gitlink and `.gitmodules` still reference the former `axionaxprotocol/nakharax` location. This README update does **not** silently retarget that dependency or advance its pinned SHA. Maintainers should validate repository access and migrate the submodule in a separately reviewed change.

### Clone this landing repository

```bash
git clone https://github.com/nakharax/nakharax-readme.git
cd nakharax-readme
```

If you have access to the configured source repository and require the pinned checkout:

```bash
git submodule update --init --recursive
```

Submodule initialization may fail for readers without upstream access. That does not affect reading this landing page.

## Contributing

Documentation corrections to this landing page are welcome. For protocol code, deployment changes or test evidence, work in the maintained implementation repository with the appropriate access. Please separate observed facts from proposals, attach dates to network checks and never promote mock or local results into production claims.

## Links

- [NakharaX website](https://nakharax.com)
- [XpFirm product](https://xpfirm.com)
- [Protocol app directory](https://nakharax.com/apps)
- [Public node interfaces](https://nakharax.com/nodes)
- [Landing-page issues](https://github.com/nakharax/nakharax-readme/issues)
- [Landing-page pull requests](https://github.com/nakharax/nakharax-readme/pulls)

## License

The documentation and artwork in **this repository** are distributed under the [MIT license](LICENSE). Implementation repositories and third-party dependencies may use separate licenses; do not infer their license from this landing page.

---

<div align="center">
<sub>NakharaX · Parent company & ecosystem · XpFirm is a product · Documentation review: 25 October 2026</sub>
</div>
