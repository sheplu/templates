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

- **Frameworks/tools:** (e.g., test ru
