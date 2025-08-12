---
name: Flaky Test Report
about: Track and stabilize an intermittently failing test
title: "[FLAKE] suite › test name"
labels: [flaky-test, testing]
assignees: []
---

## Summary
Briefly describe what flakes (suite/file and test name) and the user-facing risk.

- **Suite/File:**
- **Test name/ID:**
- **Type:** unit / integration / e2e / contract / visual

---

## Repro & Frequency
- **Failure rate:** (e.g., 3/10 runs)
- **Last known good commit:**
- **First observed commit (if known):**
- **CI links (failing & passing):**

---

## Failure Signature
Minimal, representative error/log pattern (trim noise).

> <stack trace or assertion diff>

Screenshots/video (for e2e): <links>

---

## Environment & Matrix
- **Runtime/Version:** (Node/Python/Browser, etc.)
- **OS/Arch:**
- **CI executor/image:**
- **Parallelism/Shard:**
- **Timezone/Locale:**
- **Network mode:** online/offline/mocked

---

## Suspected Causes
Check all that might apply and add notes:
- [ ] Timing/async race
- [ ] Order-dependence (test pollution)
- [ ] Shared state or missing cleanup
- [ ] Randomness/seed sensitivity
- [ ] Network/external dependency
- [ ] Clock/timers (fake vs real)
- [ ] Resource limits (CPU/mem)
- [ ] Other: …

---

## Isolation Steps Taken
What have you tried?
- Fixed random **seed**: yes/no (seed value)
- Run **serial** (`--runInBand` / single worker): result
- **Increased timeouts** / explicit awaits: result
- **Mocked network/time** (nock/fake timers): result
- **Data reset** between tests (DB/fs): result
- **Min repro** branch/repo: link

---

## Proposed Fix & Validation
- **Fix idea:** (what to change and why it helps)
- **Stabilization target:** (e.g., 50 consecutive green CI runs)
- **Metrics to watch:** failure rate, duration, retries used
- **Quarantine removal criteria:** (when we un-skip/un-quarantine)

---

## Quarantine (if needed)
- **Action:** skip/quarantine suite/test
- **Owner:**
- **Expiry date:** (auto-remind)
- **Exit criteria:** (fix merged + N green runs)

---

## References
Related issues/PRs, flaky history, dashboards.

---

### Checklist
- [ ] Failure signature captured (snippet + CI links)
- [ ] Environment/matrix documented
- [ ] Suspected cause(s) noted with evidence
- [ ] Quarantine plan (owner + expiry) if blocking
- [ ] Stabilization target & validation plan defined
