# Daemoniorum

> Infrastructure for AI minds.

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

## Nyx

Operating system and runtime infrastructure for AI agents:

- **Infernum** — Local LLM inference engine (Rust)
- **Arcanum** — Agent memory and knowledge graphs
- **Eidolon** — Development environment for agent workflows

## Styx

AI-native git platform written entirely in Sigil. Pure implementation (no libgit2), with federation support via ActivityPub.

## Paimon

Multi-agent orchestration framework. Persona-based AI systems with configurable identities, memory, and tool access.

---

Roy, Utah

[daemoniorum.com](https://www.daemoniorum.com)
