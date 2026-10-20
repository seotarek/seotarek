<div align="center">
  <img src="./assets/hero-banner.svg" alt="Tarek Mohamed - Software Architect & AI Systems Engineer" width="100%" />
</div>

<h1 align="center">Tarek Mohamed</h1>

<p align="center">
  <strong>Principal Software Architect · AI Systems & Security Researcher · Systems Engineer</strong>
</p>

<p align="center">
  I design high-performance systems, secure autonomous AI agent runtimes, and resilient cloud-native platforms. My work bridges <strong>deep systems programming in Rust</strong> (creative engines, SIMD, binary parsers), <strong>AI security research</strong> (sub-millisecond prompt injection firewalls), and <strong>high-concurrency distributed architectures</strong> across Python, TypeScript, and Kotlin.
</p>

<p align="center">
  <a href="https://tarek-mohamed.me.eg"><img src="https://img.shields.io/badge/Website-tarek--mohamed.me.eg-2563eb?style=flat-square&logo=google-chrome&logoColor=white" alt="Website" /></a>
  <a href="https://zenodo.org/records/22731104"><img src="https://img.shields.io/badge/Research_DOI-10.5281%2Fzenodo.22731104-success?style=flat-square&logo=doi&logoColor=white" alt="DOI" /></a>
  <a href="https://github.com/seotarek"><img src="https://img.shields.io/badge/GitHub-seotarek-181717?style=flat-square&logo=github&logoColor=white" alt="GitHub" /></a>
  <a href="https://discord.com/users/568723296326254613"><img src="https://img.shields.io/badge/Discord-seotarek-5865F2?style=flat-square&logo=discord&logoColor=white" alt="Discord" /></a>
  <img src="https://img.shields.io/badge/Languages-Rust%20%7C%20Python%20%7C%20TypeScript%20%7C%20Kotlin%20%7C%20C%2B%2B-orange?style=flat-square" alt="Languages" />
</p>

<div align="center">
  <a href="#-featured-research--publications">🔬 Research</a>
  &nbsp;·&nbsp;
  <a href="#-major-open-source-contributions">🌐 Open Source Contributions</a>
  &nbsp;·&nbsp;
  <a href="#-key-systems--security-projects">🛡️ Systems & Security Projects</a>
  &nbsp;·&nbsp;
  <a href="#-core-languages--technical-mastery">💻 Languages & Stack</a>
  &nbsp;·&nbsp;
  <a href="https://tarek-mohamed.me.eg/start-project">🚀 Start a Project</a>
</div>

<br />

<img src="./assets/section-divider.svg" alt="" width="100%" />

## 🔬 Featured Research & Publications

### [LightGuard-Agent: A Lightweight Defense Architecture Against Indirect Prompt Injection in Tool-Calling AI Agents](https://github.com/seotarek/LightGuard-Agent)
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.22731104.svg)](https://doi.org/10.5281/zenodo.22731104)
[![Hugging Face Spaces](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-Live%20Playground-blue?style=flat-square)](https://huggingface.co/spaces/seotarek/LightGuard-Agent)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=flat-square)](https://opensource.org/licenses/MIT)

- **Problem:** Autonomous AI agents executing tool calls via the **Model Context Protocol (MCP)** and external APIs are critically vulnerable to Indirect Prompt Injection (IPI) attacks hidden in untrusted external data streams.
- **Architecture:** A high-throughput, sub-millisecond (< 0.1 ms) three-tier defense pipeline combining deterministic syntactic isolation, semantic intent heuristics, and an execution policy action firewall.
- **Empirical Validation:** 100.0% mitigation rate across adversarial benchmark suites with zero false positives.
- **Artifacts:** Permanent DOI: [`10.5281/zenodo.22731104`](https://doi.org/10.5281/zenodo.22731104) · [Live Playground](https://huggingface.co/spaces/seotarek/LightGuard-Agent) · [Manuscript](https://github.com/seotarek/LightGuard-Agent/blob/main/paper/paper.md) · [Source Code](https://github.com/seotarek/LightGuard-Agent)

---

## 🌐 Major Open Source Contributions

### [PhotoCraft Engine](https://github.com/storytold/photocraft) — Core Contributor
*High-performance, professional digital creative and graphics studio engine written in **Rust**.*

- **Memory Safety & Engine Stability:** Hardened high-resolution canvas trimming and multi-layer duplication against out-of-memory panics on canvases exceeding 1 billion render pixels ($2^{30}$).
- **Photoshop Actions (.atn) Binary Engine:** Architected strict binary `.atn` recording and export pipelines, normalising active layer references at record time, eliminating unreferenced numeric identifiers, guaranteeing recording buffer flushes on save, and validating complex geometric selections.
- **Compositing & Graphics Algorithms:** Eliminated exterior stroke bleeding into opaque character interiors across transparent raster surfaces, and engineered dynamic brush-diameter blur sigma scaling for mathematically consistent rendering.
- **Cross-Platform UI Runtime:** Hardened global snapping and smart guide engines to guarantee deterministic view state synchronization across Linux, macOS, and Windows, integrated native clipboard support for macOS modal dialogs, and designed nested multi-theme menu architectures.

### [FastMCP](https://github.com/PrefectHQ/fastmcp) — Contributor
*Standard framework for building Model Context Protocol (MCP) servers in Python and TypeScript by Prefect.*

- **Framework Caching Architecture:** Engineered HTTP `Accept` header cache partitioning for list operations, preventing content negotiation cache pollution and decoupling test dependency injection.

---

## 🛡️ Key Systems & Security Projects

- **[LightGuard-Agent](https://github.com/seotarek/LightGuard-Agent):** Production runtime defense preventing prompt injection in autonomous LLM agent execution loops with sub-millisecond latency.
- **[Kashef (كاشف) — Scam Shield](https://github.com/seotarek/kashef-scam-shield):** On-device zero-knowledge fraud prevention and phishing heuristic engine for Android built with Kotlin, Jetpack Compose, and Material 3.
- **[mcp-arabic-toolkit](https://github.com/seotarek/mcp-arabic-toolkit):** High-performance Model Context Protocol (MCP) server providing Arabic NLP, text normalization, diacritization, and dialect classification for AI agents.
- **[laravel-llm-router](https://github.com/seotarek/laravel-llm-router):** Modular Laravel 11 package for intelligent multi-provider LLM routing, cost optimization, and automated failover.
- **[prompt-injection-detector-action](https://github.com/seotarek/prompt-injection-detector-action):** GitHub Action security gate auditing AI prompts and tool definitions during CI/CD.
- **[waha-orchestrator](https://github.com/seotarek/waha-orchestrator):** Resilient, high-throughput WhatsApp messaging pipeline with webhook verification and zero-downtime architecture.

---

## 💻 Core Languages & Technical Mastery

| Language | Primary Focus & Applied Systems |
| :--- | :--- |
| **Rust** | Creative graphics engines, binary file parsers (`.atn`, `.psd`), memory safety, SIMD, cross-platform egui runtimes |
| **Python** | AI agent orchestration, Model Context Protocol (FastMCP), PyTorch, FastAPI, prompt injection defense firewalls |
| **TypeScript** | Distributed cloud platforms, MCP TypeScript SDK, streaming WebSocket runtimes, modern web architectures |
| **Kotlin** | Modern Android engineering, Jetpack Compose, Coroutines & Flow, Room, on-device security heuristics |
| **C++ / WASM** | Performance-critical systems, SIMD vectorization, WebAssembly compilation, cross-platform graphics |
| **SQL** | PostgreSQL (`pgvector`), Redis, complex query optimization, high-concurrency transactional modeling |

---

## 🛠️ Architecture & Domain Capabilities

| Domain | Core Technologies & Frameworks |
| :--- | :--- |
| **Systems & Engine Engineering** | **Rust**, C++, WebAssembly (WASM), Memory Safety, SIMD, Binary Format Parsing |
| **AI Systems & Security** | Model Context Protocol (**MCP**), LLM Guardrails & Firewalls, Multi-Agent Orchestration, PyTorch |
| **Enterprise Backend** | Node.js / NestJS, TypeScript, Python (FastAPI), Laravel 11, PHP 8+, High-Concurrency WebSockets |
| **Databases & Vector Search** | PostgreSQL (**pgvector**), Redis, MySQL, SQLite, Hybrid Lexical/Dense Retrieval |
| **Cloud & DevOps** | Docker, Linux Kernel / Server Hardening, Ansible, Traefik, Automated CI/CD Pipelines |
| **Mobile Engineering** | Kotlin, Jetpack Compose, Android Security, Material 3, Clean Architecture, MVVM |

---

## 📊 GitHub Metrics & Activity

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=seotarek&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" alt="Tarek's GitHub Stats" height="165" />
  &nbsp;
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=seotarek&layout=compact&theme=tokyonight&hide_border=true&langs_count=8" alt="Top Languages" height="165" />
</div>

<br />

<img src="./assets/section-divider.svg" alt="" width="100%" />

## 🌐 Enterprise Inquiries & Collaborations

I partner with forward-thinking engineering teams and organizations on:
- Architecting and securing **Autonomous AI Agent Workflows & MCP Servers**.
- Building mission-critical **Systems Infrastructure in Rust and Cloud-Native Distributed Platforms**.
- Conducting **AI Application Red-Teaming, Prompt Injection Hardening & Penetration Audits**.

<p align="center">
  <a href="https://tarek-mohamed.me.eg/start-project">
    <img src="https://img.shields.io/badge/Start_a_Project-Work_With_Me-2563eb?style=for-the-badge&logo=rocket" alt="Start a Project" />
  </a>
  &nbsp;&nbsp;
  <a href="https://discord.com/users/568723296326254613">
    <img src="https://img.shields.io/badge/Discord-seotarek-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord" />
  </a>
  &nbsp;&nbsp;
  <a href="mailto:seotarek@gmail.com">
    <img src="https://img.shields.io/badge/Email_Me-seotarek%40gmail.com-10b981?style=for-the-badge&logo=gmail&logoColor=white" alt="Email Me" />
  </a>
</p>
