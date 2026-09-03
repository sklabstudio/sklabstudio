# Project

One-line description of what this does and who it is for.

> Status: `active` | `beta` | `maintenance` | `archived`
> License: MIT

## Problem

The problem, with enough context for a new reader to understand why
this project exists. 2–5 sentences.

## Solution

How this project solves the problem. What it is and what it is not.

## Features

- Feature one — one line
- Feature two — one line
- Feature three — one line

Keep the list short. Link to docs for the rest.

## Architecture

```text
src/
  api/        HTTP layer
  core/       business logic
  adapters/   external integrations
tests/
Dockerfile
```

One paragraph on key design decisions: framework choice, data flow,
boundaries. Omit if trivial.

## Quick start

```bash
git clone https://github.com/sklabstudio/<repo>.git
cd <repo>
```

### Local

```bash
# Python example — replace with actual stack
python -m venv .venv
source .venv/bin/activate  # Windows: .venv\Scripts\activate
pip install -r requirements.txt
python -m src.main
```

### Docker

```bash
docker build -t <repo> .
docker run --rm -p 8000:8000 <repo>
```

Open http://localhost:8000.

## Usage

Minimal working examples. Prefer copy-pasteable code.

```bash
curl -s http://localhost:8000/health
```

```python
import httpx

r = httpx.get("http://localhost:8000/health")
print(r.json())
```

## API

| Method | Path | Description |
| --- | --- | --- |
| GET | `/health` | Health check |
| GET | `/v1/example` | Short description |

Link to full reference (e.g. `/docs`) if available.

## Development

```bash
# setup
pip install -r requirements.txt -r requirements-dev.txt

# run in dev mode
python -m src.main --reload

# lint / format (adjust to stack)
ruff check . && ruff format --check .
```

## Testing

```bash
pytest -q
```

Describe what is covered and what is not.

## Docker

- Base image and why
- Required env vars (list, no secrets)
- Volumes / ports

```bash
docker build -t <repo> .
docker run --rm -p 8000:8000 \
  -e ENV=prod \
  <repo>
```

## Roadmap

- [ ] Next meaningful milestone
- [ ] Following milestone
- [ ] Non-goals

## License

MIT — see [LICENSE](./LICENSE).
