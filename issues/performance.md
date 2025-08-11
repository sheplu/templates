---
name: Performance Issue
about: Report slow performance, high resource usage, or scalability problems
title: "[PERF] Short description"
labels: [performance]
assignees: []
---

## Description

Describe the performance problem:
- What is slow or inefficient?
- When does it happen? (e.g., startup, during a specific operation, under heavy load)

---

## Expected vs Actual Performance

- **Expected**: What performance should it have? (e.g., “This CLI command should finish in under 2 seconds”)
- **Actual**: What are you seeing? (e.g., “Takes 12–15 seconds on average”)

Include measurements if possible:
- Duration in seconds/ms
- Memory usage (MB/GB)
- CPU usage (%)
- Other metrics (e.g., FPS, request throughput, etc.)

---

## Steps to Reproduce

1. Run `command` / Perform action
2. Observe slow behavior or high resource usage

---

## Environment

- **Project version**: (CLI version, library version, commit SHA, etc.)
- **OS & version**: (macOS, Linux, Windows, etc.)
- **Runtime**: (Node.js, Python, Browser + version, etc.)
- **Hardware specs**: (CPU model, RAM size, GPU if relevant)
- **Additional setup details**: (e.g., containerized, network conditions, dataset size)

---

## Additional Context

Any profiling results, benchmarks, logs, or diagrams that might help identify the problem.

---

### Checklist

- [ ] I have checked existing issues for similar reports
- [ ] I have provided performance measurements or benchmarks
- [ ] I have described the environment in detail
