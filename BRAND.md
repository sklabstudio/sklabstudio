# SKLab Studio — Brand

Brand name: SKLab Studio
GitHub username: sklabstudio
Website: https://sklab.cc
Profile repository: https://github.com/sklabstudio/sklabstudio

## Positioning

Independent software experiments, AI tools & developer infrastructure.

A personal, long-term software lab and developer portfolio. Not an agency,
not a startup with employees, not a hackathon account.

Short philosophy, used sparingly: Build. Test. Ship.

## Tone

- technical
- minimal
- curious
- experimental
- professional
- direct

Write about the work, not about yourself. Short sentences. No hype.

## Avoid

- corporate buzzwords
- fake startup claims (team, customers, traction, funding)
- overly futuristic language
- excessive AI hype
- fake users, stars, awards, collaborations, benchmarks, social accounts
- visitor counters, trophy widgets, streak stats, badge walls
- neon cyberpunk graphics, gradient banners, robot stock imagery

## Visual principles

Inspired by Linear, Vercel, Stripe developer tools, Cloudflare:
whitespace, typography, restraint.

- Monochrome / neutral palette. Works in GitHub light and dark mode.
- One wordmark: `assets/sklab-studio.svg`.
- One compact avatar derived from the same mark: `assets/sklab-avatar.svg`
  with a ready-to-upload `assets/sklab-avatar.png` export.
- Plain text over badges. If badges are used, keep to build/license status only.
- Tables and separators only when they improve readability.
- No external fragile image dependencies. SVG + Markdown only.
- README renders on desktop and mobile, approximately 1–3 screens.

## Repository naming conventions

- lowercase
- hyphen-separated
- short
- descriptive

Examples:

```text
agent-utils
api-toolkit
opencode-lab
experiments
starters
```

Standalone products use their actual product name converted to
lowercase/hyphenated form. No `SKLab-`, `sklabstudio-` prefixes unless
needed to avoid collision.

## Profile maintenance

- `README.md` is visitor-facing. No TODOs, no fake projects, no dead links.
- `ROADMAP.md` documents intended account structure. It is a plan, not a promise.
- `templates/` holds reusable READMEs. Use them for new repos.
- Update `README.md` → `Current lab` only when a repository is public,
  documented, and runnable.
