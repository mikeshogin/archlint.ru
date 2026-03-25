---
title: "Scan Results"
description: "Architecture analysis results for open-source projects"
---

## archlint self-scan

archlint-rs (Rust version) scanning the archlint Go + Rust codebase:

| Metric | Value |
|--------|-------|
| Components | 55 |
| Links | 197 |
| Cycles | 0 |
| Violations | 13 |
| Max fan-out | 10 |

### Violations (fan-out > 5)

| Component | Fan-out | Limit |
|-----------|---------|-------|
| cli::callgraph | 10 | 5 |
| mcp::server | 9 | 5 |
| mcp::server_test | 9 | 5 |
| analyzer::go | 8 | 5 |
| archlint-rs::src::analyzer | 8 | 5 |
| cli::check | 7 | 5 |
| cli::metrics | 7 | 5 |
| cli::collect | 7 | 5 |
| analyzer::rust | 7 | 5 |
| config::bpmn_contexts | 7 | 5 |
| mcp::watcher | 7 | 5 |
| cli::bpmn | 6 | 5 |
| tests::fullcycle_test | 6 | 5 |

Scanned with archlint-rs v0.1.0 (Rust, parallel via rayon).
