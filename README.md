<div align="center">
  <img src="./assets/hero-banner.svg" alt="Tarek Mohamed — Principal Software Architect, AI Systems & Security Researcher" width="100%" />
</div>

<br />

<div align="center">
  <a href="https://tarek-mohamed.me.eg"><img src="https://img.shields.io/badge/Website-tarek--mohamed.me.eg-2563eb?style=flat-square&logo=google-chrome&logoColor=white" alt="Website" /></a>
  <a href="https://www.linkedin.com/in/seotarek/"><img src="https://img.shields.io/badge/LinkedIn-seotarek-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="https://doi.org/10.5281/zenodo.22731104"><img src="https://img.shields.io/badge/Research_DOI-10.5281%2Fzenodo.22731104-0d9488?style=flat-square&logo=doi&logoColor=white" alt="DOI" /></a>
  <a href="https://pypi.org/project/lightguard-agent/"><img src="https://img.shields.io/badge/PyPI-lightguard--agent_v0.3.0-3775A9?style=flat-square&logo=pypi&logoColor=white" alt="PyPI" /></a>
  <a href="https://www.npmjs.com/package/medorqis"><img src="https://img.shields.io/badge/npm-medorqis_v2.1.1-cb3837?style=flat-square&logo=npm&logoColor=white" alt="npm" /></a>
  <a href="https://discord.com/users/568723296326254613"><img src="https://img.shields.io/badge/Discord-seotarek-5865F2?style=flat-square&logo=discord&logoColor=white" alt="Discord" /></a>
  <a href="mailto:seotarek@gmail.com"><img src="https://img.shields.io/badge/Email-seotarek%40gmail.com-10b981?style=flat-square&logo=gmail&logoColor=white" alt="Email" /></a>
</div>

<p align="center">
  <strong>Principal Software Architect · AI Systems &amp; Security Researcher · Systems Engineer</strong><br />
  17+ years architecting deterministic AI agent runtimes, sub-millisecond prompt-injection firewalls, memory-safe graphics engines in <strong>Rust</strong>, and resilient distributed platforms across <strong>Python, Go, TypeScript, Kotlin, and PHP/Laravel</strong>.
</p>

<div align="center">
  <a href="#architecture-domains">Architecture Domains</a>
  &nbsp;·&nbsp;
  <a href="#engineering-principles">Engineering Principles</a>
  &nbsp;·&nbsp;
  <a href="#featured-research">Security Research</a>
  &nbsp;·&nbsp;
  <a href="#case-studies">Case Studies</a>
  &nbsp;·&nbsp;
  <a href="#categorized-portfolio">Portfolio</a>
  &nbsp;·&nbsp;
  <a href="#languages-runtimes">Languages</a>
  &nbsp;·&nbsp;
  <a href="#quick-install">Quick Install</a>
  &nbsp;·&nbsp;
  <a href="https://tarek-mohamed.me.eg/start-project">Advisory</a>
</div>

<br />

<div align="center">
  <img src="./assets/metrics.svg" alt="Key Architecture and Research Metrics" width="100%" />
</div>

<br />
<img src="./assets/section-divider.svg" alt="" width="100%" />

<a id="architecture-domains"></a>
## Architecture Domains &amp; Systems Specialization

| Engineering Domain | Focus Areas &amp; Capabilities | Production Implementations |
| :--- | :--- | :--- |
| **AI Safety &amp; Agent Security** | Sub-millisecond runtime firewalls, Indirect Prompt Injection (IPI) defense, tool-calling validation, Model Context Protocol (MCP) policy enforcement, red teaming. | [LightGuard-Agent](https://github.com/seotarek/LightGuard-Agent), [ai-agent-security-scanner](https://github.com/seotarek/ai-agent-security-scanner), [prompt-injection-detector-action](https://github.com/seotarek/prompt-injection-detector-action) |
| **Systems &amp; Native Graphics** | Memory-safe extreme canvas rendering ($2^{30}$ pixels), binary format parsers (`.atn`, `.psd`), SIMD acceleration, native WebKitGTK desktop browsers. | [PhotoCraft Engine (Rust)](https://github.com/storytold/photocraft), [Valorex Browser (Rust)](https://github.com/seotarek/valorex) |
| **Clinical Decision Support (CDS)** | Regulatory-aligned AI ecosystems (IEC 62304 Class A/B/C), zero-token deterministic clinical calculators, multi-dialect clinical negation benchmarks. | [MedOrqis (24 Medical AI Skills)](https://github.com/seotarek/MedOrqis) |
| **Distributed Cloud &amp; Messaging** | High-concurrency WhatsApp multi-device REST engines, unified multi-tenant webhooks, distributed sliding-window rate limiters, zero-downtime replication. | [GOWA (Go)](https://github.com/seotarek/gowa), [unified-whatsapp-webhook-gateway](https://github.com/seotarek/unified-whatsapp-webhook-gateway), [distributed-rate-limiter-node](https://github.com/seotarek/distributed-rate-limiter-node) |
| **Data &amp; Vector Infrastructure** | PostgreSQL `pgvector` indexing (HNSW), AST-level SQL query auditing, read-only transaction sandboxing, hybrid dense + BM25 retrieval. | [mcp-postgres-guard](https://github.com/seotarek/mcp-postgres-guard), [laravel-pgvector-eloquent](https://github.com/seotarek/laravel-pgvector-eloquent), [pgvector-hybrid-rag-starter](https://github.com/seotarek/pgvector-hybrid-rag-starter) |
| **Interface Engineering &amp; BiDi** | Compiler-grade design system governance, WCAG 2.2 AAA APCA contrast, W3C DTCG tokens, CSS Logical BiDi/RTL symmetry, finite-state UI. | [Orthotect](https://github.com/seotarek/orthotect), [Kashef Scam Shield (Kotlin Compose)](https://github.com/seotarek/kashef-scam-shield) |

---

<a id="engineering-principles"></a>
## Engineering Principles

- **Deterministic Over Stochastic**: Safety, authorization, and clinical calculators must never rely on probabilistic model inferences. Runtime security firewalls and clinical engines must execute deterministically with sub-millisecond guarantees.
- **Zero-Knowledge by Default**: On-device edge heuristics (such as Kashef on Android) must analyze untrusted streams with zero cloud telemetry and strictly scoped local permissions.
- **Memory Safety &amp; Extreme Scale**: Systems code written in Rust must remain resilient against extreme-scale allocation boundaries (such as billion-pixel raster canvases) without unexpected panics or dangling references.
- **Verification Before Assertion**: Every performance, mitigation, or compliance claim must be grounded in executable test suites, public benchmarks, or permanent scientific artifacts (DOI).
- **Epistemic Provenance &amp; Formal Constraints**: Regulated architectures (clinical informatics, multi-tenant databases) require strict audit trails, boundary enforcement, and formal error containment.

---

<a id="featured-research"></a>
## Security Research &amp; Red Teaming

### [LightGuard-Agent: A Lightweight Defense Architecture Against Indirect Prompt Injection in Tool-Calling AI Agents](https://github.com/seotarek/LightGuard-Agent)

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.22731104.svg)](https://doi.org/10.5281/zenodo.22731104)
[![PyPI](https://img.shields.io/badge/PyPI-v0.3.0-3775A9?style=flat-square&logo=pypi&logoColor=white)](https://pypi.org/project/lightguard-agent/)
[![Hugging Face Spaces](https://img.shields.io/badge/Playground-Hugging%20Face-f59e0b?style=flat-square)](https://huggingface.co/spaces/seotarek/LightGuard-Agent)
[![Docs](https://img.shields.io/badge/Docs-GitHub%20Pages-0d9488?style=flat-square&logo=google-chrome&logoColor=white)](https://seotarek.github.io/LightGuard-Agent/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=flat-square)](https://opensource.org/licenses/MIT)

- **Threat Model**: Autonomous AI agents executing tool calls via the **Model Context Protocol (MCP)** and external APIs are critically exposed to Indirect Prompt Injection (IPI), homoglyph evasion, and multi-turn crescendo jailbreaks embedded in untrusted external data streams.
- **Defense Architecture**: A sub-millisecond (`< 0.1 ms`) three-tier security pipeline combining deterministic syntactic isolation, semantic intent heuristics, and a least-privilege execution policy firewall.
- **Empirical Verification**: Achieved a **100.0% mitigation rate** across adversarial benchmark suites with zero false positives on benign clinical, financial, and developer workflows.
- **Permanent Artifacts**: DOI [`10.5281/zenodo.22731104`](https://doi.org/10.5281/zenodo.22731104) · [PyPI Package](https://pypi.org/project/lightguard-agent/) · [Interactive Playground](https://huggingface.co/spaces/seotarek/LightGuard-Agent) · [Paper Manuscript](https://github.com/seotarek/LightGuard-Agent/blob/main/paper/paper.md) · [CI/CD GitHub Action](https://github.com/seotarek/prompt-injection-detector-action)

---

<a id="case-studies"></a>
## Selected Engineering Case Studies

### 1. Sub-Millisecond AI Agent Security Firewall (`< 0.1 ms` Latency)
* **Challenge**: LLM tool loops executing MCP calls are vulnerable to malicious payload injections. Traditional LLM-as-a-judge defenses add 500ms+ latency per turn, increase token costs exponentially, and are themselves susceptible to indirect prompt injection.
* **Architecture**: Engineered an ultra-lightweight, 3-tier hybrid evaluation engine in Python combining zero-latency syntactic sanitization, unicode homoglyph normalization, semantic intent heuristic classification, and strict tool-call schema boundary validation.
* **Impact**: Decreased evaluation latency to under $0.1\text{ ms}$ (less than 1% of a model inference frame) while reaching a 100.0% adversarial mitigation rate without external LLM dependencies. Published under DOI [`10.5281/zenodo.22731104`](https://doi.org/10.5281/zenodo.22731104).

### 2. Extreme-Canvas Memory Safety &amp; Binary Actions Engine in Rust
* **Challenge**: High-performance raster and vector graphics operations on ultra-dense canvases exceeding $2^{30}$ pixels (1+ billion render points) experienced out-of-memory panics during trimming and multi-layer duplications in PhotoCraft.
* **Architecture**: Hardened canvas memory allocation buffers using tile-based chunked processing, validated bounding geometry, architected a deterministic binary `.atn` (Photoshop Actions) parser and recording engine that eliminates dangling identifiers, and engineered dynamic brush-diameter blur sigma scaling.
* **Impact**: Completely eliminated memory exhaustion crashes on extreme surfaces; achieved mathematically uniform stroke feathering and cross-platform desktop UI synchronization across Linux, macOS, and Windows.

### 3. Regulatory-Aligned Clinical AI CDS with Zero-Token Deterministic Engines
* **Challenge**: Generative AI models deployed in clinical workflows hallucinate dosages, fail on dialectal negations, and cannot be certified under medical device risk management standards (ISO 14971 / IEC 62304).
* **Architecture**: Designed **MedOrqis** as a modular clinical informatics ecosystem consisting of 24 risk-stratified skills (Class A/B/C) and 12 zero-token deterministic clinical calculators (ESC 2024 CHA₂DS₂-VA, CKD-EPI 2021, Bedside Schwartz, NEWS2, HAS-BLED, DDI Engine), coupled with strict epistemic provenance locks.
* **Impact**: 36/36 verification suites passed; 100% accuracy on a 126-case multilingual clinical negation benchmark with full compatibility across Claude Code, Cursor, Codex, and Google Antigravity.

---

<a id="categorized-portfolio"></a>
## Categorized Portfolio &amp; Repositories

### AI & Agent Security

| Repository | Description &amp; Highlights | Stack | Links |
| :--- | :--- | :--- | :--- |
| **[LightGuard-Agent](https://github.com/seotarek/LightGuard-Agent)** | Sub-millisecond AI agent security firewall protecting LLM tool-calling loops and MCP runtimes against IPI attacks. | `Python` `MCP` `PyPI` | [Docs](https://seotarek.github.io/LightGuard-Agent/) · [Playground](https://huggingface.co/spaces/seotarek/LightGuard-Agent) · [DOI](https://doi.org/10.5281/zenodo.22731104) |
| **[ai-agent-security-scanner](https://github.com/seotarek/ai-agent-security-scanner)** | Security auditor and benchmark suite for autonomous AI agents, prompt injection defense, and tool verification. | `Python` `Security` | [Source](https://github.com/seotarek/ai-agent-security-scanner) |
| **[agentic-rag-faithfulness](https://github.com/seotarek/agentic-rag-faithfulness)** | Sub-millisecond evaluation library measuring RAG groundedness and detecting LLM hallucinations in Arabic and English. | `Python` `RAG` `NLP` | [Source](https://github.com/seotarek/agentic-rag-faithfulness) |
| **[MedOrqis](https://github.com/seotarek/MedOrqis)** | Evidence-grounded medical AI ecosystem: 24 clinical skills (IEC 62304 Class A/B/C) &amp; 12 deterministic calculators. | `Python` `Clinical` `npm` | [Catalog](https://seotarek.github.io/MedOrqis/) · [npm](https://www.npmjs.com/package/medorqis) · [Tests](https://github.com/seotarek/MedOrqis/blob/main/tests/reports/VERIFICATION_REPORT.md) |
| **[prompt-injection-detector-action](https://github.com/seotarek/prompt-injection-detector-action)** | GitHub Action security gate that audits system prompts, `SKILL.md` manifests, and MCP schemas on pull requests. | `GitHub Actions` `CI/CD` | [Source](https://github.com/seotarek/prompt-injection-detector-action) |

---

### Systems Engineering

| Repository | Description &amp; Highlights | Stack | Links |
| :--- | :--- | :--- | :--- |
| **[Valorex](https://github.com/seotarek/valorex)** | Ultra-fast, privacy-first native desktop web browser with WebKitGTK, Brave Adblock, and native Arabic RTL support. | `Rust` `WebKitGTK` `Linux` | [Source](https://github.com/seotarek/valorex) |
| **[PhotoCraft Engine](https://github.com/storytold/photocraft)** | Core contributor to pure Rust creative studio engine: memory safety on 1B+ canvases, `.atn` parser, and compositing math. | `Rust` `SIMD` `Graphics` | [Upstream Repo](https://github.com/storytold/photocraft) |
| **[distributed-rate-limiter-node](https://github.com/seotarek/distributed-rate-limiter-node)** | High-concurrency sliding-window distributed rate limiter middleware for Express and NestJS backends powered by Redis. | `TypeScript` `Redis` `NestJS` | [Source](https://github.com/seotarek/distributed-rate-limiter-node) |
| **[Hcnsec-AI-Assistant](https://github.com/seotarek/Hcnsec-AI-Assistant)** | AI coding assistant VS Code extension with dedicated sidebar chat and context-aware code explanations. | `TypeScript` `VS Code API` | [Source](https://github.com/seotarek/Hcnsec-AI-Assistant) |

---

### MCP & Data Infrastructure

| Repository | Description &amp; Highlights | Stack | Links |
| :--- | :--- | :--- | :--- |
| **[mcp-postgres-guard](https://github.com/seotarek/mcp-postgres-guard)** | Secure Model Context Protocol server for PostgreSQL: query auditing, slow-query `EXPLAIN`, and AST injection defense. | `Python` `MCP` `PostgreSQL` | [Source](https://github.com/seotarek/mcp-postgres-guard) |
| **[mcp-arabic-toolkit](https://github.com/seotarek/mcp-arabic-toolkit)** | High-performance MCP server providing Arabic NLP, morphological analysis, diacritization, and dialect classification. | `Python` `MCP` `Arabic NLP` | [Source](https://github.com/seotarek/mcp-arabic-toolkit) |
| **[laravel-pgvector-eloquent](https://github.com/seotarek/laravel-pgvector-eloquent)** | Native PostgreSQL `pgvector` integration for Laravel Eloquent with cosine/L2 distance scopes and automated HNSW indexing. | `PHP 8.3` `Laravel` `pgvector` | [Source](https://github.com/seotarek/laravel-pgvector-eloquent) |
| **[pgvector-hybrid-rag-starter](https://github.com/seotarek/pgvector-hybrid-rag-starter)** | Enterprise starter template for hybrid dense vector + BM25 keyword retrieval using PostgreSQL `pgvector` and RRF. | `Python` `PostgreSQL` `RAG` | [Source](https://github.com/seotarek/pgvector-hybrid-rag-starter) |
| **[laravel-llm-router](https://github.com/seotarek/laravel-llm-router)** | Multi-provider LLM routing engine with budget enforcement, circuit-breaker failover, and semantic response caching. | `PHP 8.3` `Laravel 11` `AI` | [Source](https://github.com/seotarek/laravel-llm-router) |

---

### Backend & Cloud Infrastructure

| Repository | Description &amp; Highlights | Stack | Links |
| :--- | :--- | :--- | :--- |
| **[gowa](https://github.com/seotarek/gowa)** | High-throughput Go WhatsApp Web multi-device REST API engine with webhook callbacks and persistent session storage. | `Go` `REST API` `WebSocket` | [Source](https://github.com/seotarek/gowa) |
| **[unified-whatsapp-webhook-gateway](https://github.com/seotarek/unified-whatsapp-webhook-gateway)** | High-concurrency webhook orchestrator bridging Evolution API and WAHA with multi-tenant CRMs and n8n workflows. | `JavaScript` `Node.js` `WAHA` | [Source](https://github.com/seotarek/unified-whatsapp-webhook-gateway) |
| **[docker-traefik-ha-cluster](https://github.com/seotarek/docker-traefik-ha-cluster)** | Production edge reverse proxy with automated SSL/TLS load balancing using Traefik v3 and Docker Swarm. | `Docker Swarm` `Traefik v3` | [Source](https://github.com/seotarek/docker-traefik-ha-cluster) |
| **[zero-downtime-db-sync](https://github.com/seotarek/zero-downtime-db-sync)** | Resilient streaming database migration and replication CLI tool for MySQL, PostgreSQL, and SQLite. | `Python` `Database` `CLI` | [Source](https://github.com/seotarek/zero-downtime-db-sync) |

---

### Developer Tools & Systems Utilities

| Repository | Description &amp; Highlights | Stack | Links |
| :--- | :--- | :--- | :--- |
| **[Kashef (كاشف)](https://github.com/seotarek/kashef-scam-shield)** | On-device zero-knowledge fraud prevention and phishing heuristic engine for Android built with Jetpack Compose. | `Kotlin` `Jetpack Compose` `M3` | [Source](https://github.com/seotarek/kashef-scam-shield) |
| **[Orthotect](https://github.com/seotarek/orthotect)** | Compiler-grade design system governance and static analysis gates: WCAG 2.2 AAA APCA contrast, W3C DTCG tokens, CSS Logical BiDi. | `Python` `Design Systems` `CLI` | [Source](https://github.com/seotarek/orthotect) |
| **[arabic-web-dev-tools](https://github.com/seotarek/arabic-web-dev-tools)** | Client-side web utilities for Arabic web developers: RTL CSS converter, Tashkeel stripper, and typography testing. | `HTML5` `CSS Logical` `JS` | [Source](https://github.com/seotarek/arabic-web-dev-tools) |
| **[arabic-whisper-preprocessor](https://github.com/seotarek/arabic-whisper-preprocessor)** | Pre-processing and quality telemetry tools for audio recordings in Arabic dialects to optimize word error rate (WER). | `Python` `Audio` `Whisper` | [Source](https://github.com/seotarek/arabic-whisper-preprocessor) |
| **[server-hardening-toolkit](https://github.com/seotarek/server-hardening-toolkit)** | Production hardening scripts for Linux servers: SSH, firewall rules, kernel sysctl parameters, and process isolation. | `Shell` `Linux` `DevSecOps` | [Source](https://github.com/seotarek/server-hardening-toolkit) |

---

<a id="languages-runtimes"></a>
## Core Languages &amp; Systems Runtimes

<div align="center">

[![Rust](https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white)](https://www.rust-lang.org/)
[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)](https://go.dev/)
[![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white)](https://kotlinlang.org/)
[![PHP](https://img.shields.io/badge/PHP_8.3+-777BB4?style=for-the-badge&logo=php&logoColor=white)](https://www.php.net/)
[![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)](https://www.postgresql.org/)
[![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white)](https://isocpp.org/)
[![WebAssembly](https://img.shields.io/badge/WebAssembly-654FF0?style=for-the-badge&logo=webassembly&logoColor=white)](https://webassembly.org/)
[![Linux / Bash](https://img.shields.io/badge/Linux_/_Bash-FCC624?style=for-the-badge&logo=linux&logoColor=black)](https://www.kernel.org/)

</div>

---

<a id="quick-install"></a>
## One-Line Install &amp; Quick Start Hub

Direct installation commands for production tools:

```bash
# 1. Install Sub-Millisecond AI Agent Security Firewall (PyPI)
pip install lightguard-agent

# 2. Add Medical AI Clinical Informatics CDS Skills
npx skills add seotarek/medorqis
# Or install via npm
npm install medorqis

# 3. Add Deterministic Interface Governance Gates (WCAG 2.2 AAA / DTCG Tokens)
npx skills add seotarek/orthotect
```

**Live Demos &amp; Portals:**
- [LightGuard-Agent Interactive Playground](https://huggingface.co/spaces/seotarek/LightGuard-Agent) — Test real-time prompt-injection defense heuristics
- [MedOrqis Live Clinical Catalog](https://seotarek.github.io/MedOrqis/) — Explore all 24 medical skills and deterministic calculators
- [LightGuard-Agent Documentation Portal](https://seotarek.github.io/LightGuard-Agent/) — Full API and architectural reference

---

<img src="./assets/section-divider.svg" alt="" width="100%" />

## Enterprise Architecture, Research &amp; Advisory

I partner with engineering organizations, healthcare innovators, and technology leaders on:
- **Securing Autonomous AI Agents &amp; MCP Ecosystems**: Designing deterministic runtime gates, custom MCP servers, and sub-millisecond prompt-injection firewalls.
- **High-Performance Systems &amp; Distributed Platforms**: Architecting Rust engines, multi-tenant cloud backends (Go / Python / TypeScript / PHP), and zero-downtime infrastructure.
- **Specialized Domain AI**: Building verified, regulatory-aware AI systems for clinical informatics (IEC 62304 / ISO 14971), Arabic NLP, and RTL-first enterprise products.

<p align="center">
  <a href="https://tarek-mohamed.me.eg/start-project">
    <img src="https://img.shields.io/badge/Start_a_Project-tarek--mohamed.me.eg-2563eb?style=for-the-badge&logo=rocket&logoColor=white" alt="Start a Project" />
  </a>
  &nbsp;&nbsp;
  <a href="https://www.linkedin.com/in/seotarek/">
    <img src="https://img.shields.io/badge/LinkedIn-seotarek-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  &nbsp;&nbsp;
  <a href="https://discord.com/users/568723296326254613">
    <img src="https://img.shields.io/badge/Discord-seotarek-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord" />
  </a>
  &nbsp;&nbsp;
  <a href="mailto:seotarek@gmail.com">
    <img src="https://img.shields.io/badge/Email-seotarek%40gmail.com-10b981?style=for-the-badge&logo=gmail&logoColor=white" alt="Email Me" />
  </a>
</p>
