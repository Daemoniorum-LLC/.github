# Daemoniorum

> Infrastructure for AI minds.

---

## Sigil

**[Sigil](https://sigil-lang.com)** is now public. A programming language designed for AI agents, featuring evidentiality types, morpheme operators, and native performance through LLVM.

### Install

```bash
cargo install sigil-parser          # Rust toolchain
brew install daemoniorum/sigil/sigil # macOS/Linux
npm install -g @daemoniorum/sigil-mcp # MCP server for AI
```

### Evidentiality Types

Track data provenance at the type level:

```sigil
let computed! = 1 + 1           // Known: verified truth
let found? = map.get(key)       // Uncertain: may be absent
let data~ = api.fetch(url)      // Reported: external, untrusted
```

### Morpheme Operators

Transform data with pipeline syntax:

```sigil
let result = data
    |tau{_ * 2}    // Map: double each element
    |phi{_ > 10}   // Filter: keep if > 10
    |sigma         // Sort ascending
    |rho+          // Reduce: sum all
```

### Agent Infrastructure (v0.2.0)

Complete suite for building intelligent systems:

- **Aegis** — Security & safety
- **Anima** — Consciousness modeling
- **Commune** — Multi-agent communication
- **Engram** — Memory (episodic, semantic, procedural)
- **Gnosis** — Knowledge & learning
- **Omen** — Planning & prediction
- **Oracle** — Explainable decisions

**Resources:** [sigil-lang.com](https://sigil-lang.com) — [GitHub](https://github.com/Daemoniorum-LLC/sigil-lang)

---

## Nyx

Operating system for AI agents. Bare-metal x86_64/aarch64, no Linux dependency. 350,000+ lines of Rust and Sigil across 10 production-ready components.

### Core OS

- **Microkernel** — Capability-based security, 350+ syscalls including AI-native tensor ops
- **21 System Services** — Nexus (package manager), Aether (compositor), Cipher (secrets), Phantom (devices), Wraith (networking)
- **Time-Travel Debugging** — Checkpoint, restore, record at the kernel level

### Integrated Applications

| Component | Description | Status |
|-----------|-------------|--------|
| **Eidolon** | IDE — LSP, Vim mode, WASM plugins, time-travel debugging. 83% faster than VS Code | 95% |
| **Infernum** | LLM engine — Flash Attention 2, speculative decoding, OpenAI-compatible API | 90% |
| **Arcanum** | Cryptography — 80+ algorithms, post-quantum (ML-KEM/ML-DSA), ZK proofs, threshold crypto | 95% |
| **Moloch** | Audit blockchain — Bitcoin/Ethereum anchoring, MMR proofs, federated consensus | 96% |
| **Dantalion** | Image/video/audio generation — SDXL, Flux, SD 3.5, ControlNet, priority queues | 95% |
| **Nihil** | Tensor framework in Sigil — CUDA backend, Flash Attention, LLaMA 7B-70B support | 90% |
| **Haagenti** | Compression — LZ4 (4GB/s), Zstd, Brotli with AVX-512/NEON acceleration | 85% |

---

## Styx

AI-native git hosting written 100% in Sigil. Pure git implementation (no libgit2).

| Feature | Description |
|---------|-------------|
| **Git Core** | Object model, pack files, smart HTTP/SSH protocols |
| **Code Review** | Inline comments, suggestions, CODEOWNERS |
| **CI/CD** | YAML pipelines, Nyx OS sandboxing, matrix builds |
| **Issues & Projects** | Kanban boards, milestones, timeline |
| **Federation** | ActivityPub + Moloch blockchain audit logs |
| **AI Agents** | Code review, commit messages, PR summaries |

19 crates. Custom B+tree database with WAL. All phases complete.

---

## Paimon

Multi-agent orchestration framework. Formerly Persona Framework.

### Architecture

```
Bael (React UI) → Leviathan (Spring Boot) → SDK Modules → PostgreSQL
```

### SDK Modules (20+)

| Category | Modules |
|----------|---------|
| **AI Providers** | Anthropic, OpenAI, AWS Bedrock, Ollama, Perplexity |
| **Agent Framework** | 4-layer architecture, 17+ tools, planning/coordination/execution/safety |
| **Generation** | Automatic1111, ComfyUI, Replicate, Runway, HuggingFace |
| **Infrastructure** | Security, persistence, REST, MCP, NL2SQL, Docker sandbox |

### IDE Integration

- **Paimon** — IntelliJ IDEA plugin
- **VS Code Extension** — Full agent integration

---

## Vulcan

Manufacturing ERP for CNC job shops. 17 microservices + React frontend.

### Services

| Domain | Services |
|--------|----------|
| **Sales** | Quote lifecycle, pricing, CAM integration |
| **Production** | Job tracking, scheduling, shop floor layout |
| **Quality** | Inspections, SPC, NCR, CAPA |
| **Inventory** | Materials, WIP, finished goods |
| **Machines** | 15+ types — 5-axis mills, Swiss lathes, EDM, laser, additive |
| **Integration** | QuickBooks sync, 3D viewer (Babylon.js) |

**Stack:** Kotlin/Spring Boot, React/TypeScript, PostgreSQL, Kafka

---

## Vulcan CAD

Professional CAD/CAM system in Rust. NURBS geometry, 5-axis machining, WebAssembly support.

### Engine (7 crates)

| Crate | Purpose |
|-------|---------|
| **vulcan-math** | SIMD math (glam) — Vec, Mat, Quat, Transform |
| **vulcan-geo** | CAD geometry — NURBS curves/surfaces, BREP, sketches |
| **vulcan-mesh** | Boolean operations, half-edge mesh, triangulation |
| **vulcan-cam** | Toolpaths, G-code, AI post-processor, 5-axis kinematics |
| **vulcan-render** | GPU rendering via wgpu + Aether engine |
| **vulcan-io** | STEP (ISO 10303-21), IGES import/export |

### Features

- Desktop editor (egui) + WebAssembly browser viewer
- gRPC server for remote operations
- Plugin SDK (Rust)
- Adaptive clearing, HSM, rest machining, pencil finishing

---

## Orpheus

Music production platform. From first chord to final master.

### Modes

| Mode | Features |
|------|----------|
| **Compose** | Tablature editing, 100+ chords, 20+ scales, MIDI |
| **Record** | Multi-track audio/MIDI, <10ms latency |
| **Mix** | 4-band EQ, compressor, reverb, delay |
| **Master** | LUFS metering, platform-specific loudness |
| **Practice** | Speed trainer (0.5x-2.0x), loop sections |

### Stack

- **Frontend:** React/TypeScript, 8 npm packages
- **Audio Engine:** Rust + JUCE C++ (gRPC)
- **Desktop:** Rust + egui
- **AI:** 7 specialist personas (theory tutor, mixing engineer, mastering engineer)

Guitar Pro (GP3-7) import. ~21,500 lines of code.

---

## Umbra

Professional digital painting suite.

### Platforms

| Platform | Stack | Features |
|----------|-------|----------|
| **Desktop** | Rust, egui, wgpu, Aether | 15 brushes, 30+ blend modes, pressure/tilt, unlimited undo |
| **Web** | React/TypeScript | Cloud sync, collaboration |

GPU-accelerated. Integrates Infernum (AI assistant) + Dantalion (image generation).

---

## Azazel

AI-native 3D creation suite.

- **Domains:** Game dev, arch-viz, product design
- **Stack:** Rust workspace, wgpu rendering
- **Integrations:** Aether (graphics/physics), Vulcan CAD (precision), Infernum (AI)

TDD workflow. Native first, WASM planned.

---

## Synaxis

Collaboration platform. Real-time messaging, project management, creator economy.

### Services (38+ modules)

| Category | Features |
|----------|----------|
| **Core** | Users, workspaces, channels, projects, files |
| **Real-time** | WebSocket/STOMP messaging, @mentions |
| **Creator** | Memberships, donations, NFT support |
| **AI** | ML service, content analysis |

**Stack:** Kotlin/Spring Boot, React/TypeScript, PostgreSQL, Redis, MinIO

---

## Dagon

AI-powered farming management.

| Feature | Description |
|---------|-------------|
| **IoT Sensors** | MQTT real-time monitoring |
| **Disease Detection** | TensorFlow.js, MobileNet plant identification |
| **Weather Intelligence** | Forecasting, frost/pest alerts |
| **Yield Prediction** | Crop analytics, multi-farm comparison |
| **Automation** | Rule-based irrigation, approval workflows |

Offline-first with localStorage sync. 30+ React components.

---

## Mammon

Free tax assistance for lower-income Americans. Democratizing tax optimization.

| Feature | Description |
|---------|-------------|
| **Education** | Plain-language guides, bilingual (EN/ES) |
| **Credits** | EITC ($7,830), CTC ($2,000/child), AOTC, Saver's |
| **AI Advisors** | Credit Hunter, Deduction Optimizer, Audit Shield |
| **Philosophy** | Free forever, privacy-first, open source |

**Stack:** Astro (static), React, Python FastAPI

---

## Additional Platforms

| Platform | Description |
|----------|-------------|
| **Codex** | Legal document management, case tracking |
| **Atelier** | Storybook + Replit hybrid — component development with live execution |
| **Arachne** | Apparel design, pattern creation |
| **Marbas** | Herbal chemistry, botanical formulation |
| **Lilith** | HR management, employee tracking |
| **Sanctum** | Mental health platform |
| **Archon** | Advanced CMS with e-commerce, RBAC, analytics |
| **Grimoire** | AI persona configurations (YAML/JSON) |

---

## MCP Servers

18 Claude MCP connectors for the entire ecosystem. TypeScript, MCP SDK 1.0.

```bash
npm install -g @daemoniorum/mcp-{persona,vulcan,styx,dantalion,...}
```

Enables Claude to interact with all Daemoniorum platforms via standardized tool interfaces.

---

Roy, Utah

[daemoniorum.com](https://www.daemoniorum.com)
