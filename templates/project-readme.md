# Project Name

One sentence describing what the project does and who it is for.

> Status: `alpha` | `beta` | `stable` | `maintenance` | `archived`
>
> Scope: `<single primary responsibility>`
>
> License: `<SPDX identifier or Proprietary>`

## Why it exists

Explain the problem and why this repository is the right boundary for solving
it. State what the project is not.

## Capabilities

- Capability one — concrete behavior and output
- Capability two — concrete behavior and output
- Capability three — concrete behavior and output

Keep this list short. Link to documentation for the full surface. Do not list a
planned feature as shipped.

## How it fits into SKLab

```text
upstream input → this project → verified downstream output
```

List required and optional SKLab integrations. The project must remain useful
within its stated standalone boundary.

## Architecture

```text
src/
  api/        public interface
  core/       domain behavior
  adapters/   external integrations
tests/
```

Describe important data flow, trust boundaries, persisted state, and failure
modes. Omit this section only for trivial libraries.

## Quick start

```bash
git clone https://github.com/sklabstudio/<repo>.git
cd <repo>

# Replace with the tested setup command.
# Replace with the tested run command.
```

Expected result: describe the visible output, exit code, port, or generated
artifact that confirms the quick start worked.

## Configuration

| Variable | Required | Purpose | Secret |
| :--- | :---: | :--- | :---: |
| `EXAMPLE_URL` | No | Optional service endpoint | No |
| `EXAMPLE_API_KEY` | For live use | Provider authentication | Yes |

Provide `.env.example` with names and safe placeholders only. Never commit real
credentials or print them in logs.

## Usage

Show the smallest real example. Prefer copy-pasteable commands with expected
output over screenshots or marketing prose.

```bash
<command>
```

## Verification

```bash
# lint / typecheck
<command>

# tests
<command>

# build or package verification
<command>
```

Describe what each command proves and what it does not prove. Link to CI when a
workflow exists.

## Security and permissions

- Filesystem access: …
- Network access: …
- Command execution: …
- Credential handling: …
- Approval boundary: …
- Vulnerability reporting: …

For security tooling, state the authorization requirement prominently.

## Limitations

- Known unsupported case
- Operational constraint
- Intentional non-goal

## Development

Document the supported runtime versions, dependency manager, formatting,
testing, and contribution commands. Commands in this section must match CI.

## Release policy

State versioning, compatibility, migration, and support expectations. Do not use
`stable` or `production-ready` without evidence that supports those labels.

## Roadmap

- [ ] Next meaningful capability
- [ ] Reliability or verification milestone
- [ ] Documentation or distribution milestone

## License

`<License>` — see [LICENSE](./LICENSE).
