<!-- BlackRoad SEO Enhanced -->

# RoadCode

> Part of **[BlackRoad OS](https://blackroad.io)** — Sovereign Computing for Everyone

[![BlackRoad OS](https://img.shields.io/badge/BlackRoad-OS-ff1d6c?style=for-the-badge)](https://blackroad.io)
[![BlackRoad Agents](https://img.shields.io/badge/Org-BlackRoad-Agents-2979ff?style=for-the-badge)](https://github.com/BlackRoad-Agents)
[![License](https://img.shields.io/badge/License-Proprietary-f5a623?style=for-the-badge)](LICENSE)

**RoadCode** is part of the **BlackRoad OS** ecosystem — a sovereign, distributed operating system built on edge computing, local AI, and mesh networking by **BlackRoad OS, Inc.**

## About BlackRoad OS

BlackRoad OS is a sovereign computing platform that runs AI locally on your own hardware. No cloud dependencies. No API keys. No surveillance. Built by [BlackRoad OS, Inc.](https://github.com/BlackRoad-OS-Inc), a Delaware C-Corp founded in 2025.

### Key Features
- **Local AI** — Run LLMs on Raspberry Pi, Hailo-8, and commodity hardware
- **Mesh Networking** — WireGuard VPN, NATS pub/sub, peer-to-peer communication
- **Edge Computing** — 52 TOPS of AI acceleration across a Pi fleet
- **Self-Hosted Everything** — Git, DNS, storage, CI/CD, chat — all sovereign
- **Zero Cloud Dependencies** — Your data stays on your hardware

### The BlackRoad Ecosystem
| Organization | Focus |
|---|---|
| [BlackRoad OS](https://github.com/BlackRoad-OS) | Core platform and applications |
| [BlackRoad OS, Inc.](https://github.com/BlackRoad-OS-Inc) | Corporate and enterprise |
| [BlackRoad AI](https://github.com/BlackRoad-AI) | Artificial intelligence and ML |
| [BlackRoad Hardware](https://github.com/BlackRoad-Hardware) | Edge hardware and IoT |
| [BlackRoad Security](https://github.com/BlackRoad-Security) | Cybersecurity and auditing |
| [BlackRoad Quantum](https://github.com/BlackRoad-Quantum) | Quantum computing research |
| [BlackRoad Agents](https://github.com/BlackRoad-Agents) | Autonomous AI agents |
| [BlackRoad Network](https://github.com/BlackRoad-Network) | Mesh and distributed networking |
| [BlackRoad Education](https://github.com/BlackRoad-Education) | Learning and tutoring platforms |
| [BlackRoad Labs](https://github.com/BlackRoad-Labs) | Research and experiments |
| [BlackRoad Cloud](https://github.com/BlackRoad-Cloud) | Self-hosted cloud infrastructure |
| [BlackRoad Forge](https://github.com/BlackRoad-Forge) | Developer tools and utilities |

### Links
- **Website**: [blackroad.io](https://blackroad.io)
- **Documentation**: [docs.blackroad.io](https://docs.blackroad.io)
- **Chat**: [chat.blackroad.io](https://chat.blackroad.io)
- **Search**: [search.blackroad.io](https://search.blackroad.io)

---


Monorepo pointer for all agent-related code across BlackRoad GitHub organizations.

## Core Repos

| Repo | Org | Description |
|------|-----|-------------|
| [agent-memory](https://github.com/BlackRoad-Agents/agent-memory) | BlackRoad-Agents | SQLite + FTS5 persistent agent memory |
| [ollama-fleet](https://github.com/BlackRoad-Agents/ollama-fleet) | BlackRoad-Agents | Multi-node Ollama model management |
| [hailo-vision](https://github.com/BlackRoad-Agents/hailo-vision) | BlackRoad-Agents | Hailo-8 YOLOv8s object detection |
| [rag-engine](https://github.com/BlackRoad-Agents/rag-engine) | BlackRoad-Agents | Qdrant + Ollama RAG pipeline |
| [voice-engine](https://github.com/BlackRoad-Agents/voice-engine) | BlackRoad-Agents | Whisper STT + Piper TTS |
| [roundtrip](https://github.com/BlackRoad-Agents/roundtrip) | BlackRoad-Agents | Sovereign multi-agent chat |

## Platform Repos

| Repo | Org | Description |
|------|-----|-------------|
| [blackroad-operator](https://github.com/BlackRoad-OS-Inc/blackroad-operator) | BlackRoad-OS-Inc | Core operator scripts, memory system, fleet tools |
| [roundtrip-blackroad](https://github.com/BlackRoad-OS-Inc/roundtrip-blackroad) | BlackRoad-OS-Inc | RoundTrip CF Worker implementation |
| [start](https://github.com/BlackRoad-OS-Inc/start) | BlackRoad-OS-Inc | Certification and validation scripts |

## Self-Hosted (Gitea on Octavia)

| Repo | Description |
|------|-------------|
| RoadCode | Gitea fork (sovereign git hosting) |
| Passenger | Ollama fork (sovereign AI inference) |
| CarPool | NATS fork (sovereign pub/sub mesh) |
| TollBooth | WireGuard fork (sovereign VPN) |
| PitStop | Pi-hole fork (sovereign DNS) |
| OneWay | Caddy fork (sovereign TLS edge) |
| RearView | Qdrant fork (sovereign vector DB) |
| Curb | MinIO fork (sovereign object storage) |
| RoundAbout | Headscale fork (sovereign mesh) |
| OverPass | n8n fork (sovereign automation) |
| BackRoad | Portainer fork (sovereign containers) |
| RoadMap | Grafana fork (sovereign monitoring) |

## Part of BlackRoad-Agents

Remember the Road. Pave Tomorrow.

BlackRoad OS, Inc. — Incorporated 2025.
