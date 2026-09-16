# kubeli8

**Building small, understandable infrastructure software.**

kubeli8 is an open-source engineering organization focused on systems software, container orchestration, distributed systems, and developer infrastructure.

Our current project is **k6e**, a lightweight container orchestrator written in Go and inspired by the core ideas behind Kubernetes.

The goal is not to recreate Kubernetes, but to understand and build the fundamental systems behind modern orchestration:

* control planes
* desired and actual state
* scheduling
* reconciliation
* node agents
* container lifecycle management
* health monitoring
* failure detection and recovery

We build deliberately small systems that can be understood, tested, broken, and repaired.

**Current focus:** k6e
**Stack:** Go, Docker, SQLite, HTTP, YAML

---

### Engineering philosophy

> Build small. Understand deeply. Test failure. Document decisions.

KubeLi8 prioritizes engineering depth over feature count, with an emphasis on clear architecture, reproducible experiments, and honest documentation of limitations and trade-offs.

### Projects

**k6e**
A lightweight, Go-based container orchestration system for learning, experimentation, and eventually small-scale self-hosted infrastructure.

### Status
- k6e is being actively developed.
- Engineering: [Notion InfoHub and Tracker](https://app.notion.com/p/KubeLi8-Engineering-Hub-3dcb17f2a6978165b0d5c0718acbe46f)
