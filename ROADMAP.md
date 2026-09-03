# SKLab Studio — Roadmap

This document describes the intended structure of the `sklabstudio`
GitHub account. It is a plan, not a promise. Repositories are created
only when there is real, documented work to put in them.

A clean account with a few strong repositories beats many empty ones.

## Intended account structure

```text
sklabstudio/sklabstudio
  Profile and brand. This repository.
  README, BRAND, ROADMAP, assets, templates.

sklabstudio/experiments
  Small experimental builds and proofs of concept.
  Quick, scoped, documented. May graduate to standalone repos.

sklabstudio/opencode-lab
  OpenCode prompts, workflows, skills, and experiments.
  Reusable developer infrastructure for agent-assisted work.

sklabstudio/starters
  Reusable software starters and boilerplates.
  Only what is actually reused. No generic template dumps.

Standalone high-quality products
  Each gets its own repository with its own README,
  quick start, tests, and license. See templates/project-readme.md.
```

## Principles

1. Publish when usable. A repo is public when it has a README,
   a quick start, and a defined status.
2. One repo, one job. No monoliths of unrelated scripts.
3. Templates first. New repos start from `templates/`.
4. Archive honestly. Dead experiments are marked as such, not deleted silently.

## Phases

### Phase 1 — Foundation (now)

- [x] Profile repository with README, brand, and wordmark
- [x] README templates for experiments and projects
- [ ] Publish first `experiments` entries
- [ ] Publish `opencode-lab` with actually-used workflows

### Phase 2 — Prototypes

- First small tools that solve a real problem
- Each with quick start, limitations, and license
- Promote only the ones worth maintaining

### Phase 3 — Standalone products

- Individual repositories per product
- Proper versioning, testing, Docker where relevant
- Featured in profile README → Current lab

## Explicitly not doing

- Creating dozens of empty repositories to look active
- Claiming expertise, users, or traction before it exists
- Adding stats widgets, counters, or trophy boards to the profile
