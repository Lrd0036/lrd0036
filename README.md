<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/cover-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="assets/cover-light.svg">
  <img alt="Lance Reed Dye — I build things to understand how they work. AI and trust; systems and security; code and play; language and memory." src="assets/cover-light.svg" width="100%">
</picture>

I'm Lance. I work across AI runtime security, critical infrastructure / OT, systems code, and web engineering. Most of my projects start from wanting to see how a protocol, failure mode, or policy actually behaves once it hits real constraints.

### What I work on

- **AI & trust** — Runtime policy enforcement, bounded execution graphs, local models, and separating model interpretation from actual authority to act.
- **Systems & security** — Reverse engineering, SecOT / ICS failure paths, compliance evidence, and how enterprise network footholds turn into physical consequences.
- **Code & play** — Rust, native iOS prototypes in SwiftUI and RealityKit, process simulations, and procedural vector tooling.
- **Language & memory** — Essays, cultural archives, and notes on provenance over at [boguefala.us](https://boguefala.us).

### Projects

| Project | What it actually is |
| :--- | :--- |
| [OWASP ACS](https://github.com/genai-security-project/agent-control-standard) | Wire specification and reference implementation for runtime AI agent control. A separate Guardian Agent inspects proposed tool calls over an authenticated channel to permit, deny, or modify them before execution, with a reconstructible JSONL audit log (built on Microsoft's Agent Governance Toolkit with shims for Claude Code and OpenCode). |
| [Runbook Compiler](https://github.com/Lrd0036/google) | TypeScript compiler and runtime that turns Markdown operational procedures into a finite, typed execution graph (`RBIR`). Models handle bounded judgment nodes; deterministic code owns permissions, authorization, Action Broker mutations, and verification (`RunbookBench`). |
| [Royal Duke](https://github.com/Lrd0036/SCLC) | Interactive OT-security documentary (*When the Brainstem Bleeds*) and optional Docker cyber range modeling how a compromised vendor session pivots into an engineering enclave, freezes an HMI at 62 PSI, and drops cooling across 69 Loudoun County data-center halls. |
| [CJIS v6 Compliance](https://github.com/Lrd0036/cjis-secpol-guide) | Open-source decision framework, system-boundary templates, multi-state policy research (AL, IL, TX), and agent audit skills (`cjis-compliance-audit`, `is-this-cji`) for evaluating real architectures and evidence against CJISSECPOL v6. |
| [Boguefala](https://boguefala.us) | Personal site, writing archive, and design portfolio built with static HTML, native Web Components, Cloudflare Pages Functions, D1, and custom ingestion/CLIP workers. |
| [Timberhold](https://github.com/Lrd0036/timberhold-site) | Public site for an isometric lumber tycoon and light RPG prototype for iPhone and iPad built natively in SwiftUI and RealityKit (felling tree sections, hauling logs, and milling planks). |
| [The Shoe Room](https://theshoeroom.com) | Fast, zero-framework static storefront, custom inline SVG neighborhood map, regional Auburn trip/gameday guides, and `/legacy` site archive built with vanilla HTML/CSS/TypeScript and Vite on Cloudflare Pages for a local business. |
| [TaxpayerROI](https://github.com/Lrd0036/taxpayer-roi) | Early case-competition Streamlit app combining federal datasets with county-level fiscal, budget, and equity analytics. |

"When you don't know what to do, do something." — Jim Fisk

<sub>[Web site](https://lrd0036.github.io/lrd0036/) · [Cover artwork & design notes](design/README.md)</sub>
