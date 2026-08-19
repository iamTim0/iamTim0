<p align="center">
  <img src="./assets/logo_provideit.png" alt="ProvideIT Logo" width="75"/>
</p>

<h1 align="center">Timo Hoffschröer</h1>

<p align="center">
  <b>Senior Full-Stack Developer</b> &nbsp;·&nbsp; Applied Artificial Intelligence (M.Sc.)
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/timohoffschroeer/" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
</p>

---

## 💻 About Me

Senior full-stack developer building production systems end to end — from data model and API to the interface people actually use. My work centers on **TypeScript web platforms** (Next.js, NestJS), **Python backends** (FastAPI, Django), **event-driven and time-series data** (NATS, TimescaleDB, Redis), and **applied AI**: LLM-based agents and pipelines that do real work, not demos.

I started out in cross-platform mobile with Flutter and still ship it. Alongside development I'm pursuing a **Master's in Applied Artificial Intelligence**, which shapes how I work day to day — spec-driven, agent-assisted engineering as a normal part of the build, not a side experiment.

Whether it's a multi-service analytics platform or a single Chrome extension: clean architecture, honest data handling, and software that stays maintainable long after the first release.

## 🎯 What I Work On

- **Applied AI & agentic engineering** — LLM agents and autonomous pipelines, MCP servers, RAG, local models on edge hardware
- **Event-driven backends** — FastAPI and NestJS services over NATS and gRPC, PostgreSQL / TimescaleDB
- **Modern web platforms** — Next.js App Router, TypeScript, Tailwind, multi-tenant auth and role-based access
- **Cross-platform mobile** — Flutter apps published on the App Store and Google Play
- **Ship and operate** — Docker Compose, Kubernetes, Traefik, GitHub Actions, self-hosted and on-premise deployments

## 🛠️ Tech Stack

<table>
  <tr>
    <td><b>Web</b></td>
    <td><img src="https://skillicons.dev/icons?i=react,nextjs,ts,js,tailwind" /></td>
  </tr>
  <tr>
    <td><b>Mobile</b></td>
    <td><img src="https://skillicons.dev/icons?i=flutter,dart" /></td>
  </tr>
  <tr>
    <td><b>Backend</b></td>
    <td><img src="https://skillicons.dev/icons?i=nestjs,fastapi,django,python,nodejs,bun" /></td>
  </tr>
  <tr>
    <td><b>Data</b></td>
    <td><img src="https://skillicons.dev/icons?i=postgres,redis,sqlite,prisma" /></td>
  </tr>
  <tr>
    <td><b>Platform</b></td>
    <td><img src="https://skillicons.dev/icons?i=docker,kubernetes,githubactions,git,linux" /></td>
  </tr>
</table>

**Data & messaging:** TimescaleDB · pgvector · PostGIS · NATS · gRPC / Protobuf · SQLAlchemy · Alembic  
**AI & tooling:** MCP (Model Context Protocol) · litellm · llama.cpp · Playwright · Vitest · Taskfile · Traefik · Cloudflare Tunnel  
**Also worked with:** Angular · Microsoft Dynamics 365 Business Central

## 🚀 Selected Projects

### AI & agentic systems

| Project | Overview | Stack |
| :-- | :-- | :-- |
| **Short-Content Generation** | Autonomous pipeline that turns any URL into a 9:16 marketing video — Playwright-based perception, LLM planning against DOM-injected selectors, speech synthesis via litellm, FFmpeg video assembly. | Next.js · FastAPI · Playwright · litellm |
| **Terra Edge AI** | Fully local AI assistant for an edge thin client — GGUF models through llama.cpp, no cloud, no telemetry. | Python · llama-cpp-python |
| **Paperflow** | Automates the mechanical side of academic work: a RAG index over your own source PDFs, Zotero metadata lookup, BibTeX citation resolution and LaTeX output written straight into a local Overleaf volume. | Python · RAG · Zotero · LaTeX |

### Platforms & apps

| Project | Overview | Stack |
| :-- | :-- | :-- |
| **Quantified Self** | Multi-tenant personal data analytics platform: microservices communicating over NATS and gRPC, TimescaleDB with pgvector and PostGIS, a Next.js dashboard, and a read-only MCP server that lets an AI assistant query your own metrics. Released as containerized images with a one-file deployment bundle. | FastAPI · NATS · gRPC · TimescaleDB · Next.js |
| **Fleet Inspection Portal** | On-premise, white-label portal for a German vehicle inspection office — HU/AU, SP and UVV due dates with traffic-light status, uploaded documents behind a staff review step, strict tenant separation, fully bilingual. | Next.js · TypeScript · Prisma · PostgreSQL |
| **[DriveTogether](https://drivetogether.provideit.eu/)** | Privacy-first carpooling for schools and organizations — OAuth login via IServ and Microsoft, GDPR-compliant backend, one Flutter codebase across mobile and web. | Flutter · Django · PostgreSQL |
| **[Streak – Gym Log](https://streak-gym-log.web.app/)** | Workout logging with progress analytics, live notifications and Apple/Google Health sync. Published on both app stores. | Flutter · Dart · SQLite |

<div align="center">
  <sub>Streak – Gym Log is available on</sub><br>
  <a href="https://apps.apple.com/de/app/streak-gym-log/id6445900024">
    <img src="https://img.shields.io/badge/App_Store-0D96F6?style=for-the-badge&logo=app-store&logoColor=white" alt="App Store"/>
  </a>
  <a href="https://play.google.com/store/apps/details?id=com.streakapp.streak">
    <img src="https://img.shields.io/badge/Google_Play-34A853?style=for-the-badge&logo=google-play&logoColor=white" alt="Google Play"/>
  </a>
</div>

> A selection — most of my work, from client projects to AI and agent experiments, lives in private repositories. Happy to talk through it.

---

<div align="center">
  <p>Open to conversations about applied AI, agentic systems and well-built software.</p>
  <a href="https://www.linkedin.com/in/timohoffschroeer/">Connect on LinkedIn</a>
</div>
