---
name: Dependency Update Request
about: Propose updating one or more dependencies
title: "[DEPS] package@from → to"
labels: [dependencies]
assignees: []
---

## Packages

List each package with ecosystem and type:
- **Name:** `package-a` — **from:** 1.2.3 → **to:** 1.3.0
  - **Ecosystem:** npm/pip/maven/gradle/cargo/etc.
  - **Type:** runtime / dev / build / peer / optional
  - **Transitive impact:** (if known)

---

## Rationale

Why update? (security fix / bug fix / performance / new features / policy)

---

## Impact & Risks

- Breaking changes noted in changelog: (link/summary)
- Runtime/environment changes (node/python/browser/OS)
- Build/bundle size / tree-shaking / ESM-CJS considerations
- Known incompatibilities (peer deps, engines)

---

## References

Changelogs, release notes, advisories (CVEs), migration guides.

---

### Checklist

- [ ] Reviewed changelog/release notes
- [ ] Assessed breaking changes & peers
- [ ] CI passes locally
- [ ] Rollout & rollback documented
- [ ] Linked security advisories (if applicable)
