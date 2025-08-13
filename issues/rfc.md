---
name: API Change Proposal (RFC)
about: Propose adding/changing/removing public APIs
title: "[API] Short description"
labels: [api, rfc]
assignees: []
---

## Problem Statement
What limitation or pain point does this address?

---

## Current Behavior
Document current API surface with brief examples.

---

## Proposal
Describe the new/changed API with examples:

    // Before

    // After

- Types/interfaces, payloads, error shapes
- Sync/async semantics, streaming, pagination
- Config/flags

---

## Compatibility & SemVer
- Backward compatibility impact
- Deprecation plan (if any)
- SemVer classification: patch / minor / major

---

## Migration
Code mods, sample diffs, upgrade guide.

---

## Risks & Trade-offs
Performance, security, complexity, ecosystem impact.

---

## Observability
Metrics/logs/traces to add for this API, SLIs/SLOs.

---

## Validation
Test strategy (unit/contract/e2e), conformance tests for SDKs/clients.

---

## Timeline
Milestones, experimentation window, removal dates (if deprecating).

---

### Checklist
- [ ] Proposal includes examples
- [ ] Compatibility and SemVer assessed
- [ ] Migration path documented
- [ ] Tests and observability planned
