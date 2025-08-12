---
name: Backport Request
about: Request cherry-picking a merged fix to maintained branches
title: "[BACKPORT] PR/Issue # to branch(es)"
labels: [backport, release]
assignees: []
---

## 🎯 Source

- Original issue/PR: #
- Description of the fix:

---

## 🎯 Targets

- Branch(es) to backport to: (e.g., release/1.8, 2.0.x)
- Affected versions in the wild:

---

## 🔍 Justification

Why is a backport needed? (security, critical bug, LTS, major consumer impact)

---

## 🧪 Validation on Target

- Repro confirmed on target branch
- Tests that cover the fix
- Extra checks needed (compat, build, e2e)

---

## ⚠️ Risks & Conflicts

- Conflicts expected? (files, APIs, deps)
- Alternative approach if cherry-pick fails

---

## 📦 Release Plan

- SemVer impact (patch/minor)
- Changelog entry
- Communication (release notes, upgrade notes)

---

### Checklist

- [ ] Repro confirmed on target branch
- [ ] Cherry-pick applies or plan for conflicts
- [ ] Tests pass on target
- [ ] Changelog/notes drafted
