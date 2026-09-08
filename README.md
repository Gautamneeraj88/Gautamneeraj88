<div align="center">

<img src="./banner.svg" alt="Neeraj Gautam Banner" width="100%" />

<br>

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=16&duration=2000&pause=1000&color=00FFC8&center=true&vCenter=true&multiline=true&repeat=true&width=650&height=50&lines=Building+resilient+systems+and+modern+mobile+experiences.;Security-aware+dev+%7C+Zero-trust+mindset+%7C+Terminal-first.)](https://git.io/typing-svg)

<p align="center">
  <a href="https://www.linkedin.com/in/neeraj-gautam-b86188251" target="_blank"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <a href="mailto:gautamneeraj014@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>
  <img src="https://komarev.com/ghpvc/?username=Gautamneeraj88&style=for-the-badge&color=00ffc8&labelColor=0d1117&label=VIEWS" />
  <a href="#-featured-proof-of-work"><img src="https://img.shields.io/badge/Target-Product--Based_2026-00ffc8?style=for-the-badge&labelColor=0d1117" /></a>
  <a href="#-technical-arsenal"><img src="https://img.shields.io/badge/Security-CPT_Certified-00ffc8?style=for-the-badge&labelColor=0d1117" /></a>
</p>

</div>

---

### ⚡ Executive Overview

```bash
neeraj@workstation:~$ whoami --verbose
```
```json
{
  "name": "Neeraj Gautam",
  "role": "Android & Distributed Systems Engineer",
  "domains": "Fintech & Banking Systems (Reliability, Compliance, BCNF Normalization)",
  "specialization": ["Android Architecture (Kotlin · Compose)", "Event-Driven Microservices (Kafka · Node)"],
  "security_profile": "CPT Certified · Production CVE Remediator (GHSA-9qr9-h5gf-34mp)",
  "environment": "macOS M4 + Kali Linux (Pi 5) · Neovim (Lua, 50+ plugins) · Rootless Podman"
}
```

---

### 🧩 System Architecture in Action

*Event-driven distributed architecture designed and deployed to production:*

```mermaid
%%{init: {
  'theme': 'base',
  'themeVariables': {
    'primaryColor': '#161b22',
    'primaryTextColor': '#e6edf3',
    'primaryBorderColor': '#00ffc8',
    'lineColor': '#00ffc8',
    'secondaryColor': '#0d1117',
    'tertiaryColor': '#161b22',
    'edgeLabelBackground': '#0d1117'
  }
}}%%
flowchart TD
    subgraph Clients [" Client Layer "]
        direction LR
        Android["📱 Android App (Compose + MVVM)"]
        Web["💻 Web App (Next.js)"]
    end

    subgraph Gateway [" Gateway & Notification Layer "]
        direction LR
        API["⚡ Node.js API Gateway"]
        SSE["📡 SSE Real-Time Hub"]
    end

    subgraph Core [" Distributed Event & Storage Tier "]
        direction LR
        Kafka{{"🔥 Apache Kafka"}}
        Redis[("⚡ Redis Cache")]
        Postgres[("🐘 PostgreSQL (BCNF)")]
        Mongo[("🍃 MongoDB Replica Set")]
    end

    Clients -->|HTTPS / WSS| API
    API <-->|Sub-50ms Cache| Redis
    API -->|ACID Transactions| Postgres
    API -->|Dynamic Forms| Mongo
    API -->|Publish Events| Kafka
    Kafka -->|Consume Events| SSE
    SSE -.->|Push Notifications| Clients
```

---

### 🛠 Technical Arsenal

<div align="center">

<p align="center">
  <img src="https://skillicons.dev/icons?i=kotlin,android,nodejs,express,kafka,redis,postgres,mongodb,docker,linux,neovim,cpp&theme=dark" />
</p>

<br>

**· Android & Mobile ·**

![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white)
![Jetpack Compose](https://img.shields.io/badge/Jetpack_Compose-4285F4?style=flat-square&logo=jetpackcompose&logoColor=white)
![Android](https://img.shields.io/badge/Android-3DDC84?style=flat-square&logo=android&logoColor=white)
![Coroutines](https://img.shields.io/badge/Coroutines-7F52FF?style=flat-square&logo=kotlin&logoColor=white)
![Retrofit](https://img.shields.io/badge/Retrofit-48B983?style=flat-square)
![MVVM](https://img.shields.io/badge/MVVM-FF6B6B?style=flat-square)

**· Backend & Microservices ·**

![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white)
![Kafka](https://img.shields.io/badge/Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white)
![SSE](https://img.shields.io/badge/SSE-00ffc8?style=flat-square&labelColor=0d1117)
![WebSockets](https://img.shields.io/badge/WebSockets-010101?style=flat-square&logo=socket.io&logoColor=white)

**· DevOps & Infrastructure ·**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Podman](https://img.shields.io/badge/Podman-892CA0?style=flat-square&logo=podman&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)

**· Security & Tools ·**

![Kali Linux](https://img.shields.io/badge/Kali_Linux-557C94?style=flat-square&logo=kalilinux&logoColor=white)
![Neovim](https://img.shields.io/badge/Neovim-57A143?style=flat-square&logo=neovim&logoColor=white)
![Raspberry Pi](https://img.shields.io/badge/Raspberry_Pi-A22846?style=flat-square&logo=raspberrypi&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)

</div>

<br>

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

<img height="155em" src="https://github-stats-extended.vercel.app/api?username=Gautamneeraj88&show_icons=true&theme=transparent&hide_border=true&title_color=00ffc8&icon_color=00ffc8&text_color=8b949e&bg_color=0d1117&count_private=true&include_all_commits=true" />
<img height="155em" src="https://github-stats-extended.vercel.app/api/top-langs/?username=Gautamneeraj88&layout=compact&theme=transparent&hide_border=true&title_color=00ffc8&text_color=8b949e&bg_color=0d1117&langs_count=6" />

<img src="https://streak-stats.demolab.com/?user=Gautamneeraj88&theme=transparent&hide_border=true&stroke=1a2535&ring=00ffc8&fire=ff6b6b&currStreakLabel=00ffc8&sideLabels=8b949e&dates=3a4a5a&background=0d1117" />

</div>

#### ⚡ Recent Activity
<!--START_SECTION:activity-->
- ⚡ Pushed 1 commit to [Gautamneeraj88/Gautamneeraj88](https://github.com/Gautamneeraj88/Gautamneeraj88) — *Sep 8, 2026*
- 🌱 Created branch `fix/keymap-and-plugin-cleanup` in [Gautamneeraj88/nvim-config](https://github.com/Gautamneeraj88/nvim-config) — *Aug 25, 2026*
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
