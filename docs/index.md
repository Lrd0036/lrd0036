---
title: Profile
hide:
  - navigation
  - toc
---

<div class="lrd-masthead" role="doc-subtitle">
  <span>LRD0036 &nbsp;/&nbsp; SYSTEMS, SECURITY &amp; CODE</span>
  <span class="lrd-masthead__motto">BUILD &middot; BREAK &middot; UNDERSTAND</span>
</div>

<section class="lrd-hero" aria-labelledby="lrd-hero-title">
  <div class="lrd-hero__copy">
    <h1 id="lrd-hero-title" class="lrd-hero__title">Lance<br>Reed Dye.</h1>
    <span class="lrd-hero__rule" aria-hidden="true"></span>
    <p class="lrd-hero__lead">I build things to understand how they work.</p>
    <p class="lrd-hero__note">I work across AI runtime security, critical infrastructure / OT, systems code, and web engineering &mdash; usually starting from how a protocol, failure mode, or policy behaves once it hits real constraints.</p>
  </div>
  <div class="lrd-hero__art">
    <img src="assets/hero-machine-light.svg#only-light" width="680" height="480" alt="Orbital diagram connecting a telemetry compass, isometric terminal block, central globe, fountain-pen nib, and verification shield.">
    <img src="assets/hero-machine-dark.svg#only-dark" width="680" height="480" alt="Orbital diagram connecting a telemetry compass, isometric terminal block, central globe, fountain-pen nib, and verification shield.">
  </div>
</section>

<section class="lrd-section" aria-labelledby="lrd-pillars-heading">
  <div class="lrd-section__head">
    <h2 id="lrd-pillars-heading">What I work on</h2>
    <span class="lrd-eyebrow">01 &mdash; 04</span>
  </div>
  <div class="lrd-pillars">
    <article class="lrd-pillar" data-accent="orange">
      <span class="lrd-pillar__num">01</span>
      <h3 class="lrd-pillar__title">AI &amp; trust</h3>
      <p class="lrd-pillar__body">Runtime policy enforcement, bounded execution graphs, local models, and separating model interpretation from actual authority to act.</p>
    </article>
    <article class="lrd-pillar" data-accent="gold">
      <span class="lrd-pillar__num">02</span>
      <h3 class="lrd-pillar__title">Systems &amp; security</h3>
      <p class="lrd-pillar__body">Reverse engineering, SecOT / ICS failure paths, compliance evidence, and how enterprise network footholds turn into physical consequences.</p>
    </article>
    <article class="lrd-pillar" data-accent="sage">
      <span class="lrd-pillar__num">03</span>
      <h3 class="lrd-pillar__title">Code &amp; play</h3>
      <p class="lrd-pillar__body">Rust, native iOS prototypes in SwiftUI and RealityKit, process simulations, and procedural vector tooling.</p>
    </article>
    <article class="lrd-pillar" data-accent="orange">
      <span class="lrd-pillar__num">04</span>
      <h3 class="lrd-pillar__title">Language &amp; memory</h3>
      <p class="lrd-pillar__body">Essays, cultural archives, and notes on provenance over at <a href="https://boguefala.us">boguefala.us</a>.</p>
    </article>
  </div>
</section>

<section class="lrd-section" aria-labelledby="lrd-projects-heading">
  <div class="lrd-section__head">
    <h2 id="lrd-projects-heading">Projects</h2>
    <span class="lrd-eyebrow">WHAT IT ACTUALLY IS</span>
  </div>
  <div class="lrd-projects">
    <a class="lrd-project" href="https://github.com/genai-security-project/agent-control-standard">
      <div class="lrd-project__meta">
        <span class="lrd-project__tag">OWASP &middot; Wire Spec &amp; Runtime</span>
        <span class="lrd-project__arrow" aria-hidden="true">&#8599;</span>
      </div>
      <h3 class="lrd-project__title">OWASP ACS</h3>
      <p class="lrd-project__desc">Wire specification and reference implementation for runtime AI agent control. A separate Guardian Agent inspects proposed tool calls over an authenticated channel to permit, deny, or modify them before execution, with a reconstructible JSONL audit log (built on Microsoft&rsquo;s Agent Governance Toolkit with shims for Claude Code and OpenCode).</p>
    </a>

    <a class="lrd-project" href="https://github.com/Lrd0036/google">
      <div class="lrd-project__meta">
        <span class="lrd-project__tag">TypeScript &middot; RBIR &amp; RunbookBench</span>
        <span class="lrd-project__arrow" aria-hidden="true">&#8599;</span>
      </div>
      <h3 class="lrd-project__title">Runbook Compiler</h3>
      <p class="lrd-project__desc">Compiler and runtime that turns Markdown operational procedures into a finite, typed execution graph (<code>RBIR</code>). Models handle bounded judgment nodes; deterministic code owns permissions, authorization, Action Broker mutations, and verification.</p>
    </a>

    <a class="lrd-project" href="https://github.com/Lrd0036/SCLC">
      <div class="lrd-project__meta">
        <span class="lrd-project__tag">SecOT &middot; Docker Cyber Range</span>
        <span class="lrd-project__arrow" aria-hidden="true">&#8599;</span>
      </div>
      <h3 class="lrd-project__title">Royal Duke</h3>
      <p class="lrd-project__desc">Interactive OT-security documentary (<em>When the Brainstem Bleeds</em>) and optional Docker cyber range modeling how a compromised vendor session pivots into an engineering enclave, freezes an HMI at 62 PSI, and drops cooling across 69 Loudoun County data-center halls.</p>
    </a>

    <a class="lrd-project" href="https://github.com/Lrd0036/cjis-secpol-guide">
      <div class="lrd-project__meta">
        <span class="lrd-project__tag">CJISSECPOL v6 &middot; Agent Audit Skills</span>
        <span class="lrd-project__arrow" aria-hidden="true">&#8599;</span>
      </div>
      <h3 class="lrd-project__title">CJIS v6 Compliance</h3>
      <p class="lrd-project__desc">Open-source decision framework, system-boundary templates, multi-state policy research (AL, IL, TX), and agent audit skills (<code>cjis-compliance-audit</code>, <code>is-this-cji</code>) for evaluating real architectures and evidence against CJISSECPOL v6.</p>
    </a>

    <a class="lrd-project" href="https://boguefala.us">
      <div class="lrd-project__meta">
        <span class="lrd-project__tag">boguefala.us &middot; Web Components &amp; D1</span>
        <span class="lrd-project__arrow" aria-hidden="true">&#8599;</span>
      </div>
      <h3 class="lrd-project__title">Boguefala</h3>
      <p class="lrd-project__desc">Personal site, writing archive, and design portfolio built with static HTML, native Web Components, Cloudflare Pages Functions, D1, and custom ingestion/CLIP workers.</p>
    </a>

    <a class="lrd-project" href="https://github.com/Lrd0036/timberhold-site">
      <div class="lrd-project__meta">
        <span class="lrd-project__tag">SwiftUI + RealityKit &middot; iOS / iPadOS</span>
        <span class="lrd-project__arrow" aria-hidden="true">&#8599;</span>
      </div>
      <h3 class="lrd-project__title">Timberhold</h3>
      <p class="lrd-project__desc">Public site for an isometric lumber tycoon and light RPG prototype for iPhone and iPad built natively in SwiftUI and RealityKit &mdash; felling tree sections, hauling logs, and milling planks.</p>
    </a>

    <a class="lrd-project" href="https://theshoeroom.com">
      <div class="lrd-project__meta">
        <span class="lrd-project__tag">theshoeroom.com &middot; Vite &amp; Inline SVG</span>
        <span class="lrd-project__arrow" aria-hidden="true">&#8599;</span>
      </div>
      <h3 class="lrd-project__title">The Shoe Room</h3>
      <p class="lrd-project__desc">Zero-framework static storefront, custom inline SVG neighborhood map, regional Auburn trip/gameday guides, and <code>/legacy</code> site archive built with vanilla HTML/CSS/TypeScript and Vite on Cloudflare Pages.</p>
    </a>

    <a class="lrd-project" href="https://github.com/Lrd0036/taxpayer-roi">
      <div class="lrd-project__meta">
        <span class="lrd-project__tag">Python &middot; Streamlit</span>
        <span class="lrd-project__arrow" aria-hidden="true">&#8599;</span>
      </div>
      <h3 class="lrd-project__title">TaxpayerROI</h3>
      <p class="lrd-project__desc">Early case-competition Streamlit app combining federal datasets with county-level fiscal, budget, and equity analytics.</p>
    </a>
  </div>
</section>

<footer class="lrd-colophon">
  <blockquote class="lrd-quote">
    <p>&ldquo;When you don&rsquo;t know what to do, do something.&rdquo;</p>
    <cite>&mdash; Jim Fisk</cite>
  </blockquote>
  <p class="lrd-colophon__links">
    <a href="design/">Cover artwork &amp; visual tokens</a> &middot; <a href="https://github.com/Lrd0036">GitHub (@Lrd0036)</a>
  </p>
</footer>
