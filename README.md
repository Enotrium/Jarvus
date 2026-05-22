# Jarvus — Enotrium G-Agent

**Autonomous agent framework** for the Enotrium ecosystem.

Jarvus is a TypeScript-based autonomous agent with long-term memory, tool use, knowledge ingestion, and dashboard capabilities. Designed to support research, experiment tracking, and internal operations for the Arthedain platform.

---

## Features

- **Persistent Memory** — Vector + graph memory layer
- **Tool Use** — Extensible tool calling system
- **Knowledge Ingestion** — Process documents, code, benchmarks
- **Dashboard** — Real-time agent monitoring
- **Modular Architecture** — Easy to extend with new tools and capabilities

---

## Quick Start

```bash
git clone https://github.com/Enotrium/Jarvus.git
cd Jarvus
cp .env.example .env
npm install
npm run dev
