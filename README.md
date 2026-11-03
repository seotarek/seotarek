<div align="center">
  <img src="./assets/hero-banner.svg" alt="Tarek Mohamed — Principal Software Architect, AI Systems & Security Researcher" width="100%" />
</div>

<br />

<div align="center">
  <a href="https://tarek-mohamed.me.eg"><img src="https://img.shields.io/badge/Website-tarek--mohamed.me.eg-2563eb?style=flat-square&logo=google-chrome&logoColor=white" alt="Website" /></a>
  <a href="https://www.linkedin.com/in/seotarek/"><img src="https://img.shields.io/badge/LinkedIn-seotarek-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="https://doi.org/10.5281/zenodo.22731104"><img src="https://img.shields.io/badge/Research_DOI-10.5281%2Fzenodo.22731104-0d9488?style=flat-square&logo=doi&logoColor=white" alt="DOI" /></a>
  <a href="mailto:seotarek@gmail.com"><img src="https://img.shields.io/badge/Email-seotarek%40gmail.com-10b981?style=flat-square&logo=gmail&logoColor=white" alt="Email" /></a>
</div>

<br />

> **17+ Years** Architecture Experience &nbsp;·&nbsp; **< 0.1 ms** AI Security Latency &nbsp;·&nbsp; **24** Medical AI Skills &nbsp;·&nbsp; **100+** Open Repositories

---

## Flagship Engineering & Research

### 1. [LightGuard-Agent](https://github.com/seotarek/LightGuard-Agent) — AI Agent Security Firewall
Sub-millisecond (`< 0.1 ms`) runtime defense against Indirect Prompt Injection (IPI) and MCP vulnerabilities in tool-calling AI agents. Reached **100.0% mitigation rate** across benchmark suites with zero false positives.
- **Stack:** Python · Model Context Protocol (MCP) · PyPI · CI/CD Action
- **Artifacts:** [DOI: 10.5281/zenodo.22731104](https://doi.org/10.5281/zenodo.22731104) · [PyPI Package](https://pypi.org/project/lightguard-agent/) · [Playground](https://huggingface.co/spaces/seotarek/LightGuard-Agent) · [Docs](https://seotarek.github.io/LightGuard-Agent/)

### 2. [MedOrqis](https://github.com/seotarek/MedOrqis) — Clinical Decision Support Ecosystem
Evidence-grounded medical AI ecosystem built for regulatory alignment (IEC 62304 Class A/B/C). Includes 24 risk-stratified skills and 12 zero-token deterministic clinical calculators (CHA₂DS₂-VA, CKD-EPI 2021, Bedside Schwartz, NEWS2, HAS-BLED, DDI).
- **Stack:** Python · TypeScript · npm · Clinical Informatics
- **Artifacts:** [Live Clinical Catalog](https://seotarek.github.io/MedOrqis/) · [npm Package](https://www.npmjs.com/package/medorqis) · [Verification Report](https://github.com/seotarek/MedOrqis/blob/main/tests/reports/VERIFICATION_REPORT.md)

### 3. [Valorex](https://github.com/seotarek/valorex) & [PhotoCraft Core](https://github.com/storytold/photocraft) — Systems & Graphics in Rust
Memory-safe raster graphics engine on extreme canvases exceeding $2^{30}$ pixels, deterministic Photoshop `.atn` binary parser/recorder, and privacy-first native desktop browser with WebKitGTK and Brave adblocking.
- **Stack:** Rust · WebKitGTK · SIMD · Linux Desktop · Graphics Engine
- **Artifacts:** [Valorex Source](https://github.com/seotarek/valorex) · [PhotoCraft Core](https://github.com/storytold/photocraft)

### 4. [Kashef (كاشف)](https://github.com/seotarek/kashef-scam-shield) — On-Device Scam Shield
Privacy-first fraud and phishing heuristic engine for Android built with Jetpack Compose. Analyzes untrusted SMS and messaging streams locally with zero cloud telemetry.
- **Stack:** Kotlin · Jetpack Compose · Material 3 · Edge Heuristics
- **Artifacts:** [Source Code](https://github.com/seotarek/kashef-scam-shield)

### 5. [OmniCode Studio](https://github.com/seotarek/omnicode-studio) — Enterprise Symbology & Security Seals
Multi-engine barcode and circular security seal generator: pure vector circular barcodes, scalloped notary stamps, 1D/2D symbologies, batch ZIP processing, and REST API microservices.
- **Stack:** TypeScript · React · Vite · Docker · PHP / Laravel · SVG Engine
- **Artifacts:** [Live Studio](https://seotarek.github.io/omnicode-studio/) · [Docker Microservice](https://github.com/seotarek/omnicode-studio/pkgs/container/omnicode-api)

---

## Core Architecture Domains

- **AI Safety & Agent Security**: Sub-millisecond runtime firewalls, MCP least-privilege enforcement, prompt injection mitigation, red teaming.
- **Systems & Native Graphics**: Memory safety in Rust, SIMD canvas rasterization, native WebKitGTK desktop browsers.
- **Clinical Informatics (CDS)**: Regulatory-aligned AI ecosystems (IEC 62304), deterministic clinical calculators, epistemic provenance.
- **Distributed Cloud & Messaging**: WhatsApp multi-device REST engine (Go), Traefik v3 edge routing, distributed rate limiters.
- **Data & Vector Infrastructure**: PostgreSQL `pgvector` HNSW indexing, AST SQL query auditing, hybrid dense + BM25 retrieval.

---

## Languages & Systems Runtimes

<div align="center">

[![Rust](https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white)](https://www.rust-lang.org/)
[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)](https://go.dev/)
[![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white)](https://kotlinlang.org/)
[![PHP](https://img.shields.io/badge/PHP_8.3+-777BB4?style=for-the-badge&logo=php&logoColor=white)](https://www.php.net/)
[![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)](https://www.postgresql.org/)
[![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)](https://www.docker.com/)

</div>

---

## Quick Install Hub

Direct terminal installation for production tools:

```bash
# 1. Sub-Millisecond AI Agent Security Firewall (PyPI)
pip install lightguard-agent

# 2. Medical AI Clinical Informatics CDS Skills
npx skills add seotarek/medorqis

# 3. Deterministic Interface Governance Gates
npx skills add seotarek/orthotect
```

---

## Advisory & Contact

I partner with engineering organizations, healthcare innovators, and technology leaders on securing autonomous AI systems, designing high-throughput infrastructure, and regulatory-aligned domain architectures.

<p align="center">
  <a href="https://tarek-mohamed.me.eg/start-project">
    <img src="https://img.shields.io/badge/Start_a_Project-tarek--mohamed.me.eg-2563eb?style=for-the-badge&logo=rocket&logoColor=white" alt="Start a Project" />
  </a>
  &nbsp;&nbsp;
  <a href="https://www.linkedin.com/in/seotarek/">
    <img src="https://img.shields.io/badge/LinkedIn-seotarek-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  &nbsp;&nbsp;
  <a href="mailto:seotarek@gmail.com">
    <img src="https://img.shields.io/badge/Email-seotarek%40gmail.com-10b981?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
</p>
