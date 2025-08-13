---
name: Build / Packaging Issue
about: Problems building, bundling, or packaging for distribution
title: "[PACKAGING] Short description"
labels: [packaging, build]
assignees: []
---

## Context
- **Ecosystem:** npm / pip / maven / gradle / cargo / other
- **Format(s):** ESM / CJS / UMD / wheel / sdist / jar / binary
- **Targets:** node / browser / serverless / native / OS/arch matrix

---

## Problem
Describe the build/packaging failure (compilation error, missing files, bad `exports`, type defs, sourcemaps, tree-shaking, ABI mismatch).

---

## Steps to Reproduce
1. …
2. …
3. …

**Build logs / commands:**

    <paste minimal, relevant output>

---

## Artifacts / Contents
- **Expected files:**
- **Actual files present/missing:**
- **Module metadata:** (`package.json` exports/types/engines/sideEffects) or equivalent:

---

## Environment
- **Toolchain/bundler:** webpack / Rollup / Vite / esbuild / node-gyp / setuptools / etc.
- **Runtime versions:** node/python/jdk/rust
- **OS/arch:**

---

## Expected vs Actual
- **Expected:**
- **Actual:**

---

## References
Related issues/PRs, release notes, repro repo if available.

---

### Checklist
- [ ] Minimal repro provided
- [ ] Toolchain versions listed
- [ ] Artifact contents verified
- [ ] Module format/exports clarified
