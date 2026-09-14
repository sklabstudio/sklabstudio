# Experiment Name

One sentence describing the question this experiment tests.

> Status: `experimental` | `active` | `concluded` | `archived`
>
> Scope: `<what is intentionally included>`
>
> License: `<SPDX identifier or Proprietary>`

## Question

What are you trying to learn or prove? State one falsifiable question and the
conditions that would count as success or failure.

## Boundaries

- Included: …
- Excluded: …
- Safety or authorization constraints: …

## Method

Describe the input, controlled variables, execution steps, and output. Label
mock data, fixtures, and live integrations explicitly.

```text
input → execution → check → recorded result
```

## Quick start

```bash
git clone https://github.com/sklabstudio/<repo>.git
cd <repo>

# Replace with the real setup and run commands.
```

Expected result: describe exactly what the user should observe.

## Verification

```bash
# Replace with the real test or verification command.
```

Record the environment, fixture version, and limitations needed to reproduce
the result. Availability alone is not evidence of successful execution.

## Findings

- Observed: …
- Not observed: …
- Confidence and caveats: …

## Status and next decision

- [ ] Repeat with another fixture or environment
- [ ] Promote into a maintained project
- [ ] Conclude and archive with findings preserved

## Security and data handling

List required permissions and environment variables by name. Never include
secrets, private datasets, client data, or generated credentials.

## License

`<License>` — see [LICENSE](./LICENSE).
