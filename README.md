<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/cover-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="assets/cover-light.svg">
  <img alt="Lance Reed Dye — Making AI useful, governed, and worth trusting in practice. AI enablement, agent governance, security and systems, writing and builds." src="assets/cover-light.svg" width="100%">
</picture>

I'm Lance. My specialty is **AI enablement, adoption, and agent governance**—turning messy operational data, policies, and day-to-day team workflows into AI systems that organizations can actually adopt, audit, and trust.

Outside of day-to-day strategy and platform work, I serve as a Maintainer and Documentation Lead on the **OWASP Agent Control Standard (ACS)** and contribute to **ISC2** AI security exam development.

### Focus areas

- **AI enablement & adoption** — Moving teams past novelty chat prompts into repeatable workflows, MCP integrations over authoritative data sources, practical training, and operational habits that stick.
- **Agent governance & runtime control** — Clear boundaries between what a model interprets and what software is allowed to execute: pre-tool enforcement hooks, provenance, optimistic concurrency, and reconstructible audit trails.
- **Security, policy & OT risk** — Adversarial review of agent runtimes and protocols, turning dense regulatory frameworks into runnable decision logic, and modeling how enterprise footholds become real-world operational failures.
- **Writing & side builds** — Longer essays and notes at [boguefala.us](https://boguefala.us), plus occasional Rust, Python, or native iOS prototypes when a problem is easier to think through by building it.

### Open-source, standards & selected projects

| Project | What it is |
| :--- | :--- |
| [OWASP Agent Control Standard (ACS)](https://github.com/genai-security-project/agent-control-standard) | **Maintainer & Documentation Lead.** Wire specification and reference runtime for AI agent control—letting a separate Guardian Agent inspect proposed actions and permit, deny, or modify them before execution over an authenticated, auditable channel. Includes signed host enforcement adapters, conformance tests, and spec coverage across OPA/Rego and OCSF. |
| [Runbook Compiler](https://github.com/Lrd0036/google) | Compiles human Markdown operational procedures into a finite, typed execution graph (`RBIR`). Models handle bounded judgment nodes; deterministic code owns permissions, authorization, Action Broker mutations, and verification (`RunbookBench`). |
| [CJIS v6 Compliance](https://github.com/Lrd0036/cjis-secpol-guide) | Open-source decision system, boundary templates, state-level policy research, and agent audit skills (`cjis-compliance-audit`, `is-this-cji`) for evaluating real architectures and evidence against CJISSECPOL v6 instead of treating compliance as a checkbox. |
| [Royal Duke](https://github.com/Lrd0036/SCLC) | Interactive cyber-physical scenario (*When the Brainstem Bleeds*) and optional Docker OT range tracing how an over-trusted vendor session pivots into an engineering enclave, freezes an operator HMI, and trips data-center cooling. |
| [Boguefala](https://boguefala.us) | Essays, research notes, and archived writing on systems, incentives, and cultural memory. |

*Also built on the side: [Timberhold](https://github.com/Lrd0036/timberhold-site) (an iOS/iPadOS lumber RPG prototype in SwiftUI + RealityKit) and occasional local small-business automation.*

"When you don't know what to do, do something." — Jim Fisk

<sub>[Web site](https://lrd0036.github.io/lrd0036/) · [LinkedIn](https://www.linkedin.com/in/lancerdye) · [Cover artwork](design/README.md)</sub>
