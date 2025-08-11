---
name: Refactor / Code Quality
about: Propose a structural/code quality improvement without changing external behavior
title: "[REFACTOR] Short description"
labels: [refactor, tech debt]
assignees: []
---

## Summary

Briefly describe the refactor or code quality improvement you’re proposing.

---

## Motivation

What problem does this address? (e.g., hard-to-test module, duplication, complex function, architecture drift)

---

## Scope & Non-Goals

- **In scope:** What will be changed?
- **Out of scope:** What will *not* be changed? (Ensure no functional/behavior changes unless explicitly noted.)

---

## Proposed Approach

How will you implement the refactor?
- Files/modules/classes affected
- Patterns/principles applied (e.g., SRP, dependency inversion, composition)
- Any API/internal interface reshapes

---

## Testing Plan

- How will you verify no behavior change?
- New or updated tests (unit/integration/e2e)
- Tooling (linters, static analysis, type checks)

---

### Checklist

- [ ] No external behavior changes (unless explicitly stated)
- [ ] Added/updated tests to guard behavior
- [ ] Considered performance and security
- [ ] Updated docs/notes/ADRs if needed
- [ ] Checked for related open issues/PRs
