# SKLab Studio — Roadmap

This roadmap describes the intended direction of the SKLab ecosystem. It is a
working plan, not a promise of features or release dates.

## Product tracks

### SKLab Studio

A personal, long-term agent engineering platform: local-first execution,
reproducible environments, explicit approvals, and evidence-backed outcomes.
It is developed independently of hackathon deadlines.

### APIVouch

A focused API verification agent and the XAgent hackathon submission. APIVouch
may integrate with SKLab components, but it keeps its own product story,
release path, deployment, and submission requirements.

## Current system map

| Layer | Repositories |
| :--- | :--- |
| Control | `web-ui`, `sklab-cli` |
| Coordination | `orchestrator`, `agent-adapters`, `provider-connections` |
| Context and skills | `repo-context`, `skill-hub`, `coding-lab` |
| Execution | `reprobox`, `starters` |
| Verification | `patchbench`, `benchsuite`, `promptbench`, `codetrials` |
| Specialist tools | `contract-toolkit`, `cyber-pack` |
| Private intelligence | `appsec-lab`, `protocol-intelligence` |
| Focused product | `apivouch` |
| Profile and standards | `sklabstudio` |

The repository count is not a success metric. Integration quality, reliable
execution, and daily usefulness matter more than adding another module.

## Open-core boundary

Keep public:

- local single-user control surfaces and orchestration interfaces;
- agent/provider adapters, context, skills, and reproducible execution tools;
- reusable evaluation tools, schemas, examples, and starter projects;
- the public APIVouch implementation required for distribution and review.

Keep private:

- advanced AppSec and protocol intelligence logic;
- proprietary rules, datasets, scoring, and client engagement data;
- future multi-tenant cloud control plane, billing, and enterprise policy;
- secrets, credentials, operational telemetry, and internal deployment state.

Repository visibility and license are separate decisions. Every repository must
carry an explicit license appropriate to its boundary.

## Milestones

### 1. Foundation — complete

- [x] Profile, brand guide, roadmap, and README templates
- [x] Agent, provider, context, skill, sandbox, and verification boundaries
- [x] CLI and browser control surfaces
- [x] Public repository documentation and CI baselines
- [x] Separate APIVouch product identity

### 2. Daily-driver runtime — next

- [ ] Run one real repository task end to end from the Web UI
- [ ] Persist sessions, decisions, evidence, and resumable task state
- [ ] Install and permission MCP servers and skills through one workflow
- [ ] Support long-running jobs, cancellation, retry, and scheduling
- [ ] Provide one-command local setup and a reliable doctor command
- [ ] Replace remaining demo paths with clearly verified live execution

### 3. Reliability and learning

- [ ] Add regression suites for complete cross-repository workflows
- [ ] Add durable memory with explicit scope, retention, and deletion controls
- [ ] Measure agent/provider results using frozen tasks and reproducible receipts
- [ ] Add failure recovery, backup, migration, and compatibility policies
- [ ] Dogfood SKLab on its own repositories and record recurring failures

### 4. Optional distribution

- [ ] Publish documentation at `sklab.cc`
- [ ] Package supported local installers and signed releases
- [ ] Define community contribution and security-reporting processes
- [ ] Evaluate an optional hosted control plane without weakening local-first use

## Decision rules

1. Improve an existing execution path before creating another repository.
2. A green health check proves availability, not task success.
3. No feature is complete without an expected result and a verification path.
4. Keep private capability boundaries private in code, fixtures, logs, and docs.
5. Archive abandoned experiments honestly; do not preserve misleading status.
6. Keep SKLab's long-term roadmap separate from APIVouch's hackathon timeline.
