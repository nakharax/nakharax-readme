# AGENTS.md

## Scope

This repository (`nakharax/nakharax-readme`) is a **public documentation and brand landing page**, not the protocol runtime, an XpFirm application or an implementation monorepo.

NakharaX is the parent company and ecosystem steward; **XpFirm is a NakharaX product**. The NakharaX public domain is `https://nakharax.com`, and XpFirm's site is `https://xpfirm.com`.

## Content rules

- Write public-facing repository text in English, with clear headings and working links.
- Maintain `README.md`, `assets/` and documentation/editing instructions only.
- Do not add application or infrastructure code here or duplicate upstream implementation docs.
- Do not treat the presence of an app route as proof that a deployed feature works.
- Clearly separate development, local/mock demonstrations, public testnet and production.
- Testnet chain ID is `86137`; mainnet chain ID `86150` is reserved, **not launched**.
- The canonical public RPC address shown by the protocol is `https://rpc.nakharax.com`; verify liveness rather than asserting it from a badge.
- The last operational source document reviewed on 2 October 2026 reported a **failed block-freshness check**. Do not reuse historic passing checks to claim current health.
- Use dated primary implementation/operations evidence for finality, throughput, validator count and marketplace deployment claims.
- Never repoint or advance the `nakharax/` submodule without a separate explicit, reviewed dependency change. The current `.gitmodules` references an older repository location and access may be restricted.
- Preserve LICENSE terms; changes to brand references in a copyright notice require their own review.

## Workflow

1. Inspect the existing README and its referenced local assets.
2. Validate current domain, product relationships and network caveats before updating.
3. Change only necessary documentation or asset files.
4. Check Markdown links, asset paths, branding and status language.
5. Use a topic branch and PR; do not force-push or bypass CI.

No build, package installation, or runtime tests are defined for this landing-page repository. Verify the content and diff instead.
