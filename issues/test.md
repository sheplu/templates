---
name: Test Coverage / QA Task
about: Request new or improved tests, or define a test plan for a change
title: "[TEST] Short description"
labels: [testing, qa]
assignees: []
---

## Goal

What quality gap are we addressing?
- **Current state:** (e.g., low coverage in module X, missing e2e for flow Y)
- **Target state:** (e.g., >80% branch coverage, e2e for checkout flow)

---

## Test Scope

- **In scope:** (components/modules/packages)
- **Out of scope:** (explicitly list exclusions to prevent scope creep)

---

## Test Types (select all that apply)

- [ ] Unit
- [ ] Integration
- [ ] End-to-end (E2E)
- [ ] Contract/API (OpenAPI/GraphQL, Pact)
- [ ] Accessibility (a11y)
- [ ] Visual regression
- [ ] Performance/Benchmark
- [ ] Security checks (linting/SAST/DAST)
- [ ] Smoke/Sanity
- [ ] Upgrade/Migration

---

## Scenarios & Acceptance Criteria

List critical scenarios with clear pass/fail criteria.
Use Gherkin-style if helpful:

- **Given** … **When** … **Then** …

---

## Implementation Plan

- **Frameworks/tools:** (e.g., test runner, e2e tool, contract tester — keep generic)
- **Fixtures/mocks/test data:** (how created, where stored)
- **Failure/fault injection:** (timeouts, retries, network errors)
- **Special setup:** (feature flags, seeding, test users)

---

## Environment & Matrix

- **Runtime(s):** (Node/Python/… versions)
- **OS/Browser/Device matrix:** (if applicable)
- **Services/DBs:** (real vs mocked, containers)
- **Network conditions:** (offline/slow/limited)

---

## CI Integration

- **How to run:** (`npm test`, `make test`, `pytest`, etc.)
- **CI job(s):** (job name, parallelism, caching, artifacts)
- **Gates:** (required checks, min coverage thresholds, flake detection)

---

## Metrics & Targets

- **Coverage (current → target):** Lines %, Branches %, Critical paths
- **Performance budgets (if perf tests):** (e.g., p95 < 300ms)
- **Stability:** Flake rate target (e.g., <1% over last 20 runs)

---

### Checklist

- [ ] Scope & test types defined
- [ ] Scenarios include acceptance criteria
- [ ] CI integration documented
- [ ] Coverage/metrics targets set
- [ ] Cross-platform/browsers considered (if applicable)
- [ ] No sensitive data in tests/fixtures
