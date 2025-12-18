# Daemoniorum Bug Bounty & QA/QC Process

*Internal documentation for founders and core team*

---

## The Bounty

The real reward: working software, fewer 3am debugging sessions, and the quiet satisfaction of watching something you built actually *work*.

Track your victories here. Share the bugs. Celebrate the fixes.

---

## Bug Tracking

### Severity Levels

| Level | Description | Response |
|-------|-------------|----------|
| **P0 - Critical** | Blocks development, data loss, security hole | Drop everything |
| **P1 - High** | Major feature broken, significant UX issue | Next work session |
| **P2 - Medium** | Feature degraded, workaround exists | This sprint |
| **P3 - Low** | Minor annoyance, cosmetic issue | When convenient |

### Bug Report Format

```
**Product:** [Which tool/app]
**Found by:** [Your name]
**Date:** [When discovered]
**Severity:** [P0-P3]

**What happened:**
[Description]

**Expected behavior:**
[What should happen]

**Steps to reproduce:**
1.
2.
3.

**Environment:**
- OS:
- Version:
- Relevant config:

**Screenshots/Logs:**
[If applicable]
```

---

## QA/QC Process

### Before Committing

- [ ] Code compiles/builds without errors
- [ ] Existing tests still pass
- [ ] New functionality has basic test coverage
- [ ] No hardcoded secrets, keys, or credentials
- [ ] Linter/formatter has been run

### Before Merging to Main

- [ ] Feature branch tested locally
- [ ] Cross-checked with at least one other founder (async is fine)
- [ ] Breaking changes documented
- [ ] Migration path clear (if applicable)

### Testing Checklist by Product Type

**For IDEs/Dev Tools (Wraith, Paimon, Sigil)**
- [ ] Basic editing operations work
- [ ] File save/load functions correctly
- [ ] Plugin/extension system stable
- [ ] Performance acceptable on target hardware

**For Web Platforms (Bael, Archon, etc.)**
- [ ] Auth flows work (login/logout/session)
- [ ] CRUD operations function
- [ ] UI renders correctly
- [ ] API endpoints respond appropriately

**For Frameworks/SDKs (Persona, Aether)**
- [ ] Core APIs function as documented
- [ ] Example code runs
- [ ] Dependencies resolve correctly
- [ ] Build/install process works

**For AI/Agent Components (Leviathan, Infernum)**
- [ ] Model loads successfully
- [ ] Inference produces reasonable output
- [ ] Memory/resource usage acceptable
- [ ] NPU/GPU utilization as expected

---

## The Trophy Case

### Bugs Squashed

| Date | Bug | Found By | Fixed By | Product |
|------|-----|----------|----------|---------|
| | | | | |

### Milestones

| Date | Achievement | Who |
|------|-------------|-----|
| | | |

---

## Quick Reference

### Common Debug Commands

```bash
# Check running services
docker ps

# Tail logs
docker logs -f <container>

# Check system resources
htop

# Test API endpoint
curl -X GET http://localhost:PORT/health
```

### Environment Notes

```
Infernum: NPU-accelerated inference
Leviathan: Currently debugging (restructured)
Bael: React frontend for agent actions
```

---

## Notes

*Use this space for gotchas, workarounds, and tribal knowledge*

-

---

<sub>Internal use only | Daemoniorum, LLC</sub>
