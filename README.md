<div align="center">

# Kuco

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono\&weight=600\&size=22\&pause=1200\&color=58A6FF\&center=true\&vCenter=true\&width=900\&lines=Systems+%26+AI+Infrastructure+Developer;Linux+Networking+%7C+kTLS+%7C+Zero-copy;Local+LLM+%7C+GPU+Serving+%7C+API+Gateway;SmartNIC+%7C+DPU+%7C+High-performance+Networking)](https://git.io/typing-svg)

**Building reliable infrastructure, high-performance networks, and self-hosted AI systems.**

</div>

---

## About Me

I am a systems and infrastructure developer focused on building and operating:

* Local LLM serving and multi-GPU inference infrastructure
* OpenAI- and Anthropic-compatible API gateways
* Linux networking and secure content-delivery systems
* SmartNIC, DPU, kTLS, and zero-copy acceleration
* Self-hosted collaboration and development platforms
* Backend services and community-operated web platforms

My current interests include **high-performance networking**, **GPU inference optimization**, **AI agent infrastructure**, and **reliable self-hosted systems**.

---

## Areas of Focus

| Area                     | Experience                                                                  |
| ------------------------ | --------------------------------------------------------------------------- |
| **AI Infrastructure**    | Multi-GPU model serving, local LLM deployment, inference optimization       |
| **API Gateway**          | OpenAI/Anthropic-compatible APIs, routing, authentication, usage management |
| **Linux Networking**     | kTLS, zero-copy, NGINX, OpenSSL, TLS offloading, performance analysis       |
| **SmartNIC / DPU**       | NVIDIA ConnectX and BlueField platforms, DOCA, XLIO                         |
| **Platform Engineering** | Ubuntu Server, Docker, Proxmox, GitLab, Mattermost, OpenProject             |
| **Backend Development**  | Node.js, Express, EJS, REST APIs, authentication, automation                |
| **Network Operations**   | Cloudflare, WireGuard, VLAN, reverse proxy, remote-access infrastructure    |

---

## Selected Work

### Kemonofantasy AI Platform

[GitHub Repository](https://github.com/Kuco-dev/kemonofantasy-ai-platform) · In development and validation

Developing a wiki-based AI web service for questions about fictional worlds and characters, character interpretation, and creative conversations. The project connects the web UI, API, asynchronous workers, databases, retrieval and inference pipelines, and deployment environment.

* Built a wiki ingestion pipeline that maps redirects to canonical document aliases and preserves character attributes, affiliations, and origins from infoboxes
* Expanded retrieval candidates and added exact-title matching to a **Qwen-based retrieval and reranking pipeline**, including FP32 reranking on a GTX 1650
* Added answer citations and source previews, with response policies that distinguish wiki-grounded facts from character speculation, fan fiction, and roleplay
* Built a live generation-progress UI with expandable stage timings, immediate display of submitted questions, message editing, an auto-resizing input, suggested questions, and conversation-based titles
* Blocked unavailable models in both the selection UI and API, and improved Markdown and citation rendering while retaining restrictions on external images and raw HTML
* Built sidebar-based settings and user profiles with activity statistics, annual heatmaps, model preferences, and usage patterns; added quota balances, reset times, 7- and 30-day token usage, and completed-response counts by model
* Added Gravatar and avatar uploads with browser-based pan, zoom, and crop controls, plus server-side file validation, orientation correction, resizing, and WebP conversion using **Sharp**
* Worked on wiki-linked account eligibility checks, sessions, and TOTP security; added configurable role badges, audit logs, a local test-account CLI with explicit eligibility exceptions, and database schema migrations
* Managed web, API, worker, and shared packages in a **pnpm and Turborepo monorepo**, with Docker Compose builds, deployments, and database migrations
* Ran Vitest tests, type checks, and linting, and used Playwright to check desktop and mobile layouts, image cropping, and CSP behavior; browser checks that use API mocks are not full end-to-end validation of live account integration

Stack: **TypeScript · Python**, Next.js · React, Fastify, PostgreSQL · Prisma · Redis, Qwen · Qdrant, Sharp, pnpm · Turborepo, Vitest · Playwright · ESLint, Docker Compose · GitHub

### Secure Content Delivery Optimization

* Researched secure content-transfer optimization using **Linux zero-copy and kTLS**
* Evaluated software and hardware-assisted TLS transmission
* Built performance-testing environments with **NGINX, OpenSSL, ConnectX, and BlueField**
* Analyzed throughput, latency, CPU utilization, and TLS-offload counters
* Worked with high-speed Ethernet environments up to **100 GbE**

### Local LLM and GPU Infrastructure

* Deployed and operated models using **SGLang, vLLM, Ollama, and Open WebUI**
* Built multi-GPU inference environments with tensor parallelism
* Configured reasoning parsers, model context limits, and serving parameters
* Integrated local models with development tools and AI coding agents
* Operated OpenAI- and Anthropic-compatible API endpoints

### AI Gateway and Agent Systems

* Built and maintained AI gateway environments using tools such as:

  * LiteLLM Proxy
  * CLIProxyAPI
  * One API
  * Anthropic-compatible proxies
* Integrated AI models with VS Code, Claude Code, Copilot agents, and automation systems
* Investigated authentication, rate limiting, model routing, and reasoning controls

### Self-hosted Platform Engineering

* Deployed and operated services on **Ubuntu Server and Proxmox**
* Managed containerized services with Docker and systemd
* Configured GitLab, Mattermost, OpenProject, PostgreSQL, MongoDB, and Redis
* Built remote-access environments using Cloudflare and WireGuard
* Diagnosed DNS, TLS, SMTP, routing, VLAN, and reverse-proxy issues

### Web and Community Services

* Developed Node.js and Express-based web services
* Built server-rendered applications with EJS, JavaScript, and CSS
* Operated community platforms backed by MongoDB, Redis, and Meilisearch
* Implemented authentication, search, backups, monitoring, and service migration
* Maintained long-running community-operated infrastructure

---

## Languages and Development

<p>
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" alt="JavaScript">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white" alt="Bash">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white" alt="HTML5">
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white" alt="CSS3">
</p>

## Infrastructure and Platforms

<p>
  <img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black" alt="Linux">
  <img src="https://img.shields.io/badge/Ubuntu-E95420?style=flat-square&logo=ubuntu&logoColor=white" alt="Ubuntu">
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker">
  <img src="https://img.shields.io/badge/Proxmox-E57000?style=flat-square&logo=proxmox&logoColor=white" alt="Proxmox">
  <img src="https://img.shields.io/badge/NGINX-009639?style=flat-square&logo=nginx&logoColor=white" alt="NGINX">
  <img src="https://img.shields.io/badge/Cloudflare-F38020?style=flat-square&logo=cloudflare&logoColor=white" alt="Cloudflare">
  <img src="https://img.shields.io/badge/GitLab-FC6D26?style=flat-square&logo=gitlab&logoColor=white" alt="GitLab">
  <img src="https://img.shields.io/badge/NVIDIA-76B900?style=flat-square&logo=nvidia&logoColor=white" alt="NVIDIA">
</p>

## Databases and Search

<p>
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL">
  <img src="https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white" alt="MongoDB">
  <img src="https://img.shields.io/badge/Redis-FF4438?style=flat-square&logo=redis&logoColor=white" alt="Redis">
  <img src="https://img.shields.io/badge/Meilisearch-FF5CAA?style=flat-square&logo=meilisearch&logoColor=white" alt="Meilisearch">
</p>

## AI and GPU Stack

<p>
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" alt="PyTorch">
  <img src="https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black" alt="Hugging Face">
  <img src="https://img.shields.io/badge/vLLM-GPU%20Inference-4B8BBE?style=flat-square" alt="vLLM">
  <img src="https://img.shields.io/badge/SGLang-LLM%20Serving-7C3AED?style=flat-square" alt="SGLang">
  <img src="https://img.shields.io/badge/Local%20LLM-Self--Hosted-2EA44F?style=flat-square" alt="Local LLM">
  <img src="https://img.shields.io/badge/SmartNIC%20%2F%20DPU-Network%20Acceleration-76B900?style=flat-square" alt="SmartNIC and DPU">
</p>

---

## Tokscale

<div align="center">

[![Tokscale Stats](https://tokscale.ai/api/embed/Kuco-dev/svg?view=3d\&sort=cost)](https://tokscale.ai/u/Kuco-dev)

</div>

---

## Currently Exploring

```text
Local LLM Infrastructure
├── Multi-GPU inference
├── Reasoning model integration
├── OpenAI / Anthropic compatible gateways
├── AI coding agents
└── Usage and cost observability

High-performance Networking
├── Linux zero-copy
├── Kernel TLS
├── SmartNIC and DPU offloading
├── NGINX and OpenSSL optimization
├── 100 GbE performance analysis
└── 200 GbE performance analysis

Platform Engineering
├── Containerized self-hosting
├── Service monitoring
├── Secure remote access
├── Infrastructure automation
└── Reliable backup and recovery
```

---

<div align="center">

### Build. Measure. Optimize. Repeat.

</div>
