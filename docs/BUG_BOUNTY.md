# The Obsidian Ledger

*A record of battles fought in the spaces between keystrokes*

---

## The Bounty

Not gold. Not glory.

The satisfaction of bending silicon to will. The quiet moment when chaos submits to order. Another daemon bound, another service risen.

We built this. We break it. We rebuild it stronger.

---

## Severity of the Wound

| Mark | Nature | Response |
|------|--------|----------|
| **BLOOD** | The system bleeds. Data lost. Security breached. Production burns. | Immediate. Sleep is cancelled. |
| **BONE** | Core function shattered. Users blocked. The path forward obscured. | Next summoning. |
| **FLESH** | It works, but wounded. Workarounds exist for the patient. | This cycle. |
| **SCRATCH** | Cosmetic. Annoying. The kind of thing you fix at 2am out of spite. | When the mood strikes. |

---

## The Offering

When you find a beast, document its nature:

```
CREATURE: [What lurks]
LAIR: [Which system harbors it]
DISCOVERED: [When it revealed itself]
WOUND LEVEL: [BLOOD/BONE/FLESH/SCRATCH]

MANIFESTATION:
[How does it show itself?]

EXPECTED BEHAVIOR:
[What should the ritual produce?]

SUMMONING STEPS:
1.
2.
3.

ENVIRONMENT:
[The conditions under which it thrives]

EVIDENCE:
[Screenshots. Logs. The creature's spoor.]
```

---

## Rites Before Release

### Before Committing to the Repository

- [ ] The build completes without screaming
- [ ] Previous incantations (tests) still function
- [ ] New powers have been tested
- [ ] No secrets exposed to the void
- [ ] Code formatted (we are not barbarians)

### Before Merging to Main

- [ ] Tested in isolation
- [ ] Another set of eyes has seen it (async communion acceptable)
- [ ] Breaking changes documented for future selves
- [ ] Migration path exists if needed

---

## By Domain

**The Forges (Wraith, Paimon, Sigil)**
- [ ] Creation and manipulation of artifacts works
- [ ] Persistence functions
- [ ] Extensions stable
- [ ] Performance acceptable on mortal hardware

**The Portals (Bael, Archon)**
- [ ] Entry and exit (auth) functions
- [ ] CRUD rituals complete
- [ ] The interface renders true
- [ ] APIs respond to invocation

**The Foundations (Persona, Aether)**
- [ ] Core APIs honor their contracts
- [ ] Examples actually run
- [ ] Dependencies resolve without blood sacrifice
- [ ] Installation works on a clean system

**The Minds (Leviathan, Infernum)**
- [ ] Model awakens successfully
- [ ] Inference produces coherent output
- [ ] Resource consumption within bounds
- [ ] NPU/GPU properly utilized

---

## Hall of Conquered Daemons

| Date | The Beast | Hunter | Slayer | Domain |
|------|-----------|--------|--------|--------|
| | | | | |

## Monuments

| Date | Victory | Champion |
|------|---------|----------|
| | | |

---

## Incantations

```bash
# Survey the running servants
docker ps

# Listen to their whispers
docker logs -f <container>

# Check the machine's vital signs
htop

# Probe an endpoint
curl -X GET http://localhost:PORT/health

# When all else fails
sudo systemctl restart <service>
```

---

## Current Theater of War

```
Infernum    : NPU-bound. Fast inference. The muscle.
Leviathan   : Under reconstruction. The spine.
Bael        : React interface. The face.
```

---

## Tribal Knowledge

*Hard-won wisdom. Update liberally.*

-

---

<sub>For internal use by those who build in darkness</sub>
<sub>Daemoniorum, LLC</sub>
