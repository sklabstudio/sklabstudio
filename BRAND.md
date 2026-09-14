# SKLab Studio — Brand and Publishing Guide

This file is the source of truth for SKLab Studio's public identity and
repository presentation.

## Public profile

- Name: `SKLab Studio`
- Username: `sklabstudio`
- Bio: `Independent software lab building local-first AI agents, verification systems, and developer infrastructure.`
- Website: `https://sklab.cc`
- Profile repository: `https://github.com/sklabstudio/sklabstudio`

## Positioning

SKLab Studio is a personal, long-term software lab. It builds local-first AI
agent infrastructure, developer tools, and reproducible verification systems.

It is not an agency, a company with implied employees, or a hackathon-only
account. APIVouch is a separate focused product; it must not redefine the SKLab
platform or its roadmap.

Primary tagline:

> Build agents. Verify outcomes.

Supporting principle:

> Evidence over claims.

Use `Build. Test. Ship.` only when the context is general software delivery,
not as a replacement for the primary tagline.

## Voice

- Technical, minimal, curious, and direct.
- Explain the problem before the implementation.
- Write about the work, not an imagined team or company.
- Prefer short sentences and concrete nouns.
- State the current scope and limitations plainly.

Avoid:

- corporate buzzwords and excessive AI hype;
- fake users, traction, customers, partners, awards, or benchmarks;
- unverified performance, security, compatibility, or production claims;
- implying that an integration is working because it is merely configured;
- presenting mock or demo execution as a live result.

## Proof standard

Public claims should point to at least one inspectable signal:

- a runnable quick start;
- an automated test or CI workflow;
- a reproducible receipt or fixture;
- an example with expected output;
- a clearly labelled release or implementation status.

Use `experimental`, `alpha`, `beta`, `stable`, `maintenance`, or `archived`
deliberately. Do not use `production-ready` without deployment evidence and a
documented support boundary.

## Visual system

The visual direction is inspired by restrained developer products: generous
space, strong typography, neutral surfaces, and one small status accent.

- Wordmark: `assets/sklab-studio.svg`
- Avatar source: `assets/sklab-avatar.svg`
- Ready-to-upload avatar: `assets/sklab-avatar.png`
- Workflow diagram: `assets/verified-agent-loop.svg`
- Accent: green `#22C55E`, used sparingly as a live/status signal
- All profile artwork must work in GitHub light and dark modes.
- Keep important text in Markdown; images must not carry essential information.
- Use repository-owned SVG/PNG assets. Avoid fragile third-party image widgets.
- Do not add visitor counters, trophy boards, streak cards, badge walls,
  contribution snakes, cyberpunk art, or stock robot imagery.

## Portfolio structure

The profile highlights no more than six projects. Choose projects that explain
the complete agent loop, not simply the newest repositories. The wider system
belongs in a compact, collapsible map.

A project may be featured only when it is public, documented, runnable, and has
an honest status. Private repositories may be described by capability area but
must never be linked, mirrored, or summarized in a way that exposes internal
logic.

## Repository rules

- Names are lowercase, short, and hyphen-separated.
- One repository has one primary job.
- Every public repository includes a README, license, setup path, test command,
  limitations, and security boundary where relevant.
- Public and private boundaries follow the open-core decision documented in
  `ROADMAP.md`.
- Credentials, client data, private datasets, and generated local state are
  never committed.

## Profile maintenance checklist

Before changing the profile README:

1. Verify every linked repository exists and is public.
2. Verify image XML and render images in light and dark mode.
3. Run `git diff --check` and the repository link check.
4. Remove outdated roadmap language and unverified claims.
5. Confirm APIVouch remains presented separately from the SKLab platform.
6. Review the live GitHub profile after pushing.
