<p align="center">
  <img src="./assets/sklab-studio.svg" width="640" alt="SKLab Studio — independent software experiments, AI tools and developer infrastructure" />
</p>

# SKLab Studio

Independent software experiments, AI tools,
developer infrastructure & automation.

This is a working software lab. Ideas are turned into usable prototypes,
developer tools, and small, well-scoped experiments. Build. Test. Ship.

---

## What I build

- AI agents and agent-adjacent tooling
- MCP and tool interoperability experiments
- APIs and backend systems
- Automation and workflow tooling
- Developer utilities and reusable components
- Small experimental software, published as it becomes usable

Scope grows as projects are published. Nothing here is claimed before it exists.

## SKLab Verified Agent platform

The current focus is one local-first engineering agent that routes work to a
compatible coding agent, injects provider credentials only at execution time,
runs work in reproducible environments, and verifies patches before reporting
success.

```text
CLI / Web UI / MCP client
          |
     Orchestrator
    /     |       \
Context  Skills  Providers + Agents
    \     |       /
       ReproBox
          |
       PatchBench
          |
  evidence-backed result
```

### Featured repositories

| Project | Role |
| --- | --- |
| [Orchestrator](https://github.com/sklabstudio/orchestrator) | Plans, routes, retries, and coordinates verified runs |
| [Agent Adapters](https://github.com/sklabstudio/agent-adapters) | Normalized discovery and execution contract for coding agents |
| [Provider Connections](https://github.com/sklabstudio/provider-connections) | Secret-safe provider configuration and runtime injection |
| [RepoContext](https://github.com/sklabstudio/repo-context) | Deterministic, local repository context |
| [Skill Hub](https://github.com/sklabstudio/skill-hub) | Versioned skill discovery, trust, permissions, and routing |
| [ReproBox](https://github.com/sklabstudio/reprobox) | Reproducible execution environments and receipts |
| [PatchBench](https://github.com/sklabstudio/patchbench) | Objective patch and regression verification |
| [Web UI](https://github.com/sklabstudio/web-ui) | Human control plane for the integrated stack |
| [BenchSuite](https://github.com/sklabstudio/benchsuite) | Frozen benchmark tasks with hidden verification |

The platform is under active integration hardening. Mock/demo execution is
explicitly labelled; availability is never reported as proof of execution.

## Engineering interests

Agent infrastructure · Tool interoperability · API design ·
Automation · Reliability · Developer experience · Experimental software

## Stack

`Python` · `FastAPI` · `TypeScript` · `Next.js` · `Docker` · `Git` · `REST` · `MCP`

Small, boring, proven — chosen to ship and maintain.

## Open source & experiments

This account will contain:

- working prototypes
- reusable components
- experiments and proofs of concept
- developer tooling
- research-driven builds

A clean account with a few strong repositories is the goal. No filler repos.

## Links

- Website: https://sklab.cc
- GitHub: https://github.com/sklabstudio
