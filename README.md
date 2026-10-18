<div align="center">
  <img src="./assets/hero-banner.svg" alt="Tarek Mohamed - Software Architect & AI Systems Engineer" width="100%" />
</div>

<h1 align="center">Tarek Mohamed</h1>

<p align="center">
  <strong>Principal Software Architect · AI Systems & Security Researcher · Systems Engineer</strong>
</p>

<p align="center">
  I design high-performance systems, secure autonomous AI agent runtimes, and resilient cloud-native platforms. My work bridges <strong>deep systems programming in Rust</strong> (creative engines, SIMD, binary parsers), <strong>AI security research</strong> (sub-millisecond prompt injection firewalls), and <strong>high-concurrency distributed architectures</strong>.
</p>

<p align="center">
  <a href="https://tarek-mohamed.me.eg"><img src="https://img.shields.io/badge/Website-tarek--mohamed.me.eg-2563eb?style=flat-square&logo=google-chrome&logoColor=white" alt="Website" /></a>
  <a href="https://zenodo.org/records/22731104"><img src="https://img.shields.io/badge/Research_DOI-10.5281%2Fzenodo.22731104-success?style=flat-square&logo=doi&logoColor=white" alt="DOI" /></a>
  <a href="https://github.com/seotarek"><img src="https://img.shields.io/badge/GitHub-seotarek-181717?style=flat-square&logo=github&logoColor=white" alt="GitHub" /></a>
  <img src="https://img.shields.io/badge/Core_Stack-Rust%20%7C%20Python%20%7C%20TypeScript%20%7C%20MCP-orange?style=flat-square" alt="Core Stack" />
</p>

<div align="center">
  <a href="#-featured-research--publications">🔬 Research</a>
  &nbsp;·&nbsp;
  <a href="#-systems-engineering--open-source-contributions">🦀 Systems & Open Source</a>
  &nbsp;·&nbsp;
  <a href="#-key-security--agentic-tooling">🛡️ Security & AI Tooling</a>
  &nbsp;·&nbsp;
  <a href="#-core-capabilities--technical-stack">🛠️ Tech Stack</a>
  &nbsp;·&nbsp;
  <a href="https://tarek-mohamed.me.eg/start-project">🚀 Start a Project</a>
</div>

<br />

<img src="./assets/section-divider.svg" alt="" width="100%" />

## 🔬 Featured Research & Publications

### [LightGuard-Agent: A Lightweight Defense Architecture Against Indirect Prompt Injection in Tool-Calling AI Agents](https://github.com/seotarek/LightGuard-Agent)
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.22731104.svg)](https://doi.org/10.5281/zenodo.22731104)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=flat-square)](https://opensource.org/licenses/MIT)

- **Problem:** Autonomous AI agents executing tool calls via the **Model Context Protocol (MCP)** and external APIs are critically vulnerable to Indirect Prompt Injection (IPI) attacks hidden in untrusted external data streams.
- **Architecture:** A high-throughput, sub-millisecond (< 0.1 ms) three-tier defense pipeline combining deterministic syntactic isolation, semantic intent heuristics, and an execution policy action firewall.
- **Empirical Validation:** 100.0% mitigation rate across adversarial test suites with zero false positives.
- **Artifacts:** Permanent DOI: [`10.5281/zenodo.22731104`](https://doi.org/10.5281/zenodo.22731104) · [Manuscript](https://github.com/seotarek/LightGuard-Agent/blob/main/paper/paper.md) · [Source Code](https://github.com/seotarek/LightGuard-Agent)

---

## 🦀 Systems Engineering & Open Source Contributions

### [PhotoCraft Engine](https://github.com/storytold/photocraft) — Core Contributor
*High-performance, professional digital creative and graphics studio engine written in **Rust**.*

- **Engine Stability & Memory Bounds:** Hardened canvas trimming and merged layer duplication against out-of-memory document panics exceeding $2^{30}$ render pixels ([#7255](https://github.com/storytold/photocraft/pull/7255)).
- **Photoshop ATN Engine Architecture:** Engineered strict `.atn` export safety, isolating numeric layer references ([#7262](https://github.com/storytold/photocraft/pull/7262)), flushing pending recording buffers ([#7244](https://github.com/storytold/photocraft/pull/7244)), and validating complex selection geometry ([#7249](https://github.com/storytold/photocraft/pull/7249), [#7232](https://github.com/storytold/photocraft/pull/7232)).
- **Compositing & Graphics Algorithms:** Prevented exterior stroke effects from bleeding into opaque character interiors in raster/vector surfaces ([#5937](https://github.com/storytold/photocraft/pull/5937)) and scaled blur sigma dynamically with brush diameter ([#5939](https://github.com/storytold/photocraft/pull/5939)).
- **Cross-Platform UI Runtime:** Enabled unified clipboard operations on macOS modal dialogs ([#5938](https://github.com/storytold/photocraft/pull/5938)) and hardened snapping / smart guide engines ([#5936](https://github.com/storytold/photocraft/pull/5936)).

---

## 🛡️ Key Security & Agentic Tooling

- **[LightGuard-Agent](https://github.com/seotarek/LightGuard-Agent):** Production runtime defense preventing prompt injection in autonomous LLM agent execution loops.
- **[ai-agent-security-eval](https://github.com/seotarek/ai-agent-security-eval):** Automated adversarial test suites and security evaluation frameworks for agentic workflows.
- **[prompt-injection-ci](https://github.com/seotarek/prompt-injection-ci):** GitHub Action security gate auditing AI prompts and tool definitions during CI/CD.
- **[mcp-postgres-audit](https://github.com/seotarek/mcp-postgres-audit):** Secure Model Context Protocol (MCP) server enforcing least-privilege database operations.
- **[unified-whatsapp-gateway](https://github.com/seotarek/unified-whatsapp-gateway):** Resilient, high-throughput messaging pipeline with webhook verification.
- **[zero-downtime-deploy-kit](https://github.com/seotarek/zero-downtime-deploy-kit):** Production-ready deployment automation with automated health probes and instant rollbacks.

---

## 🛠️ Core Capabilities & Technical Stack

| Domain | Core Technologies & Frameworks |
| :--- | :--- |
| **Systems & Engine Engineering** | **Rust**, C++, WebAssembly (WASM), Memory Safety, SIMD, Binary File Format Parsing (`.psd`, `.atn`) |
| **AI Systems & Security** | Model Context Protocol (**MCP**), LLM Guardrails & Firewalls, Multi-Agent Orchestration, PyTorch, Python |
| **Enterprise Backend** | Node.js / NestJS, TypeScript, Python (FastAPI), Laravel 11, PHP 8+, High-Concurrency WebSockets |
| **Databases & Vector Search** | PostgreSQL (**pgvector**), Redis, MySQL, SQLite, Hybrid Lexical/Dense Retrieval |
| **Cloud & DevOps** | Docker, Linux Kernel / Server Hardening, Ansible, Traefik, CI/CD Pipeline Automation |
| **Frontend & Mobile Client** | React, Next.js, Tailwind CSS, Flutter, Jetpack Compose, Kotlin |

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
  <a href="mailto:seotarek@gmail.com">
    <img src="https://img.shields.io/badge/Email_Me-seotarek%40gmail.com-10b981?style=for-the-badge&logo=gmail&logoColor=white" alt="Email Me" />
  </a>
</p>
