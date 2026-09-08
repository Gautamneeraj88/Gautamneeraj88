<div align="center">

# Neeraj Gautam
### Android & Distributed Systems Engineer · Fintech & Security Mindset

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=16&duration=2000&pause=1000&color=00FFC8&center=true&vCenter=true&multiline=true&repeat=true&width=650&height=50&lines=Building+resilient+systems+and+modern+mobile+experiences.;Security-aware+dev+%7C+Zero-trust+mindset+%7C+Terminal-first.)](https://git.io/typing-svg)

<p align="center">
  <a href="https://www.linkedin.com/in/neeraj-gautam-b86188251"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <a href="mailto:gautamneeraj014@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>
  <img src="https://img.shields.io/badge/Focus-Product--Based_Company_2026-00ffc8?style=for-the-badge&labelColor=0d1117" />
  <img src="https://img.shields.io/badge/Security-CPT_Certified-00ffc8?style=for-the-badge&labelColor=0d1117" />
</p>

</div>

---

### ⚡ Executive Overview

I engineer high-throughput backend microservices and fluid, reactive Android applications. With a foundation in banking/fintech, my focus is on **data integrity, zero-trust security, and high-concurrency event-driven architecture**.

```bash
$ whoami --verbose
{
  "name": "Neeraj Gautam",
  "specialization": ["Android Architecture (Compose)", "Event-Driven Microservices (Kafka)"],
  "domain_experience": "Fintech & Banking Systems (Reliability, Compliance, BCNF Normalization)",
  "security_profile": "CPT Certified · Production CVE Patch Remediator (GHSA-9qr9-h5gf-34mp)",
  "developer_environment": "macOS M4 + Kali Linux (Pi 5) · Neovim (Lua, 50+ plugins) · Linux/Podman"
}
```

---

### 🧩 System Architecture in Action

*High-level overview of an enterprise event-driven architecture I've designed and deployed:*

```mermaid
graph LR
    subgraph Client ["Client Layer"]
        Android["📱 Android App (Compose + MVVM)"]
        Web["💻 Web App (Next.js)"]
    end

    subgraph Gateway ["Gateway & Ingestion"]
        API["⚡ Node.js API Gateway"]
        SSE["📡 SSE Notification Engine"]
    end

    subgraph Bus ["Distributed Event Bus"]
        Kafka{{"🔥 Apache Kafka"}}
    end

    subgraph Persistence ["Data & Cache"]
        Redis[("⚡ Redis Cache")]
        Mongo[("🍃 MongoDB Replica Set")]
        Postgres[("🐘 PostgreSQL (BCNF)")]
    end

    Android -->|REST / SSE| API
    Web -->|REST / SSE| API
    API <-->|Low-latency Cache| Redis
    API -->|Transactions| Postgres
    API -->|Dynamic Forms| Mongo
    API -->|Publish Events| Kafka
    Kafka -->|Async Consume| SSE
    SSE -.->|Real-time Push| Android
    SSE -.->|Real-time Push| Web
```

---

### 🛠 Technical Arsenal

| Domain | Core Stack | Applied Focus |
| :--- | :--- | :--- |
| **Mobile Engineering** | **Kotlin**, **Jetpack Compose**, Coroutines, StateFlow, Retrofit | Clean Architecture, MVVM, 60fps UI, offline-first persistence |
| **Backend & Distributed** | **Node.js**, **Express**, **Kafka**, **Redis**, **SSE**, WebSockets | Event streaming, Pub/Sub, horizontal scaling, sub-50ms caching |
| **Databases** | **PostgreSQL**, **MongoDB**, **Prisma ORM** | BCNF normalization, replica sets, transaction guarantees |
| **DevOps & Infrastructure** | **Podman**, **Docker**, Linux, GitHub Actions CI/CD, Nginx | Containerized microservices, rootless containers, automated pipelines |
| **Security & Auditing** | **CPT Certified**, Kali Linux, Wireshark, Metasploit, DVWA | Production CVE remediation, threat modeling, attack surface reduction |
| **Dev Velocity** | **Neovim** (50+ Lua plugins), Tmux, Zsh, Git | Keyboard-driven workflow, zero GUI overhead, high output |

---

### 🚀 Featured Proof-of-Work

<details open>
<summary><b>🔥 DSA Mastery — Interactive Algorithm Visualizer (Open Source)</b></summary>
<br>

> Interactive educational platform visualizing 190+ data structures and algorithms with real-time canvas state machines.

- **Stack:** React · D3.js · Vite · GitHub Pages
- **Engineering Highlights:** Custom canvas animation pipeline, algorithmic step-by-step state machine, zero heavy UI framework dependencies.
- **Links:** [🌐 Live Demo](https://gautamneeraj88.github.io/dsa-mastery) · [💻 GitHub Repository](https://github.com/Gautamneeraj88/dsa-mastery)

</details>

<details>
<summary><b>🛡️ FormBuilder & Real-Time Engine — Distributed Platform (Enterprise)</b></summary>
<br>

> High-throughput dynamic form engine and notification service supporting enterprise clients.

- **Stack:** Node.js · Kafka · Redis · MongoDB Replica Set · Next.js · Podman
- **Engineering Highlights:**
  - Event-driven notifications orchestrated via Apache Kafka and RxJS over Server-Sent Events (SSE).
  - Remediated critical Remote Code Execution CVE (`GHSA-9qr9-h5gf-34mp`) in production Next.js dependencies.
  - Containerized and deployed with rootless Podman on enterprise servers.
- **Status:** `Office Work (Proprietary)`

</details>

<details>
<summary><b>📱 Bank On The Go — Modern Android Banking Application (Fintech)</b></summary>
<br>

> Mobile banking application built with modern Android guidelines, focusing on banking-grade security and instant transaction updates.

- **Stack:** Kotlin · Jetpack Compose · MVVM · Clean Architecture · PostgreSQL · SSE
- **Engineering Highlights:**
  - Unidirectional Data Flow (UDF) with Compose and Coroutines/StateFlow.
  - BCNF normalized schema via Prisma + PostgreSQL for strict transaction consistency.
  - Real-time balance and transaction push alerts via SSE.
- **Status:** `Office Work (Proprietary)`

</details>

<details>
<summary><b>⚡ Neovim Configuration — Ultimate Terminal Development Environment</b></summary>
<br>

> Fully modular Lua-based Neovim configuration built for blazing-fast full-stack and mobile development.

- **Stack:** Lua · Neovim 0.10+ · Treesitter · Mason · Telescope · LSP Zero
- **Features:** 50+ plugins, sub-40ms startup time, unified theme, customized keymaps.
- **Links:** [💻 GitHub Repository](https://github.com/Gautamneeraj88/nvim-config)

</details>

---

### 📈 Activity & Stats

<div align="center">

<img height="150em" src="https://github-readme-stats.vercel.app/api?username=Gautamneeraj88&show_icons=true&theme=transparent&hide_border=true&title_color=00ffc8&icon_color=00ffc8&text_color=8b949e&bg_color=0d1117&count_private=true&include_all_commits=true" />
<img height="150em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Gautamneeraj88&layout=compact&theme=transparent&hide_border=true&title_color=00ffc8&text_color=8b949e&bg_color=0d1117&langs_count=6" />

</div>

#### ⚡ Recent Activity
<!--START_SECTION:activity-->
<!--END_SECTION:activity-->

---

<div align="center">

```bash
$ echo "Let's connect: Android architecture · Distributed systems · Security research"
```

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/neeraj-gautam-b86188251)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/Gautamneeraj88)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:gautamneeraj014@gmail.com)

```
neeraj@gautam:~$ █
```

</div>
