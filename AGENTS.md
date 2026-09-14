# Repository Instructions

## Purpose

Maintain the public SKLab profile, brand rules, roadmap, reusable README templates, and repository presentation standards.

## Read before editing

- `BRAND.md` before changing public language or visual assets
- `ROADMAP.md` before changing platform scope
- `templates/` before creating or revising repository documentation

## Working rules

- Work only inside this repository unless the user explicitly requests a coordinated cross-repository change.
- Read `README.md`, the package manifest, and the relevant CI workflow before changing behavior.
- Preserve unrelated user changes. Do not rewrite or delete work merely to make a patch cleaner.
- Never commit credentials, tokens, client data, local state, caches, build output, or generated secrets.
- Do not describe a configured, mocked, or importable integration as successfully executed.
- When behavior or a public contract changes, update tests and user-facing documentation in the same change.
- Keep SKLab's long-term platform story separate from APIVouch's hackathon story.
- Link only public repositories from the profile and never expose private capability details.
- Do not add fake metrics, fragile widgets, inflated claims, or a second unrelated visual identity.

## Verification

- Parse every SVG as XML and render changed artwork in light and dark mode.
- Verify every GitHub link in `README.md`.
- Run `git diff --check`.
- Review the live GitHub profile after pushing.

If an environment-dependent check cannot run, state exactly what was skipped and
why. Do not replace a missing check with a claim of success.

## Completion checklist

- The smallest correct change is implemented within this repository's scope.
- New or changed behavior has focused tests.
- Public interfaces, examples, and limitations are documented.
- Security and credential boundaries still hold.
- `git diff --check` passes and the working tree contains no unintended files.
