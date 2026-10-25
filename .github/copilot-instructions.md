# Copilot Instructions — NakharaX landing repository

## Repository purpose

`nakharax/nakharax-readme` is a public README/branding and navigation repository. Do not implement application, protocol, AI agent or blockchain features here. It is not an independently deployed runtime.

**Brand hierarchy**
- **NakharaX** — parent company and ecosystem steward, https://nakharax.com
- **NakharaX Protocol** — experimental Layer-1/decentralized compute initiative under NakharaX
- **XpFirm** — trading risk-management and performance product under NakharaX, https://xpfirm.com
- **Axionax Protocol** — former name of the protocol initiative; retain only for historical continuity

Do not use `xpfirm.com` as the parent-organization name, and do not use the legacy `nakharax.io` address for new public navigation links.

## What may be changed

- `README.md`, contributor instructions under `.github/`, `AGENTS.md` and repository-owned branding assets.
- Keep a brief, scannable English overview and clear public navigation. Prefer static, reliable badges to unverified live-performance counters.
- The `nakharax/` submodule is a pinned source reference. Its `.gitmodules` URL still points at the former `axionaxprotocol/nakharax` location; it may require special access. Do **not** repoint or bump it incidentally when updating documentation.
- Do not modify the copyright/license wording as part of a routine brand sweep.

## Operational truth and public claims

The implementation repository's dated network status and engineering release gates are the authority. Current source review:

- Public testnet chain ID `86137` (`0x15079`)
- Public RPC advertised as `https://rpc.nakharax.com`
- Mainnet `86150` is **reserved and blocked**, not released
- The 2 October 2026 read-only liveness check failed block freshness; it must not be replaced by an older passing observation
- Public marketplace versions, worker execution, proof systems and UI demonstrations have different evidence levels. Mark local/mock/demo versus deployed functionality clearly

Never claim a green network, working Mainnet, deployed Marketplace V2, verified finality or measured performance without fresh dated operational evidence. Avoid hardcoded validator counts, benchmark numbers, APY and roadmap percentages unless verified against authoritative sources. Public website labels do not by themselves establish on-chain readiness.

PoPC terminology and verification design are evolving; defer to current protocol specification rather than preserving a historical expansion as unquestioned fact.

## Source / code navigation

Implementation work is kept separately and access may be restricted. The maintained code covers Rust node/consensus, Python workers, Solidity contracts, TypeScript SDK, OS dashboard, MCP integration, docs and operator tools. Do not present a stale monorepo layout or the old Git submodule target as a guaranteed current, publicly available source URL.

For protocol code, operators, SDK, deployment or marketplace implementation, redirect to the appropriate maintained repository. For README corrections, use this repository.

## Verification checklist

- Domains: `nakharax.com` and `xpfirm.com`; no outdated `nakharax.io` navigation
- Hierarchy: NakharaX parent, XpFirm product
- Testnet vs Mainnet and mock vs deployed distinguished
- No broken local assets or invented claims of network liveness
- README clone URL points to `nakharax/nakharax-readme`
- Any inaccessible submodule is described without silently modifying its pointer
- Change confined to documentation and assets; inspect PR diff before merge

Last guidance refresh: 25 October 2026.
