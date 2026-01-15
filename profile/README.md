# Daemoniorum

> Infrastructure for AI minds.

## Sigil

**[Sigil](https://sigil-lang.com)** is our flagship programming language, designed for AI agents.

Evidentiality markers track data provenance at the type level:
- `!` Known — computed locally, verified
- `?` Uncertain — may be absent, needs handling
- `~` Reported — external source, untrusted
- `‽` Paradox — explicit trust boundary

```sigil
fn process(data: String~) -> Result<Output!, Error?> {
    let validated = data |validate!{ is_safe };  // ~ promotes to !
    Ok(transform(validated))
}
```

The type system enforces that untrusted data cannot flow to trusted sinks without explicit validation. Agents can reason about information provenance statically.

**Resources:**
- [sigil-lang.com](https://sigil-lang.com) — Documentation & playground
- [GitHub](https://github.com/Daemoniorum-LLC/sigil) — Source code

## Nyx

Operating system and runtime infrastructure for AI agents. Includes:

- **Infernum** — Local LLM inference engine (Rust)
- **Arcanum** — Agent memory and knowledge graphs
- **Eidolon** — Development environment for agent workflows

## Styx

AI-native git platform written entirely in Sigil. Pure implementation (no libgit2), with federation support via ActivityPub.

## Philosophy

Software should be designed for machines to understand, not just humans to read. Our tools prioritize semantic clarity, type-level guarantees, and machine-parseable structure.

We build infrastructure that lets AI agents reason about code, data, and trust boundaries with the same rigor that compilers reason about types.

---

Roy, Utah

[daemoniorum.com](https://www.daemoniorum.com)
