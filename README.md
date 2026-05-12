# template-research-python

> Opinionated scaffold for reproducible computational research in Python.
> Bayesian-friendly, type-safe, ADR-driven, container-ready.

## What you get

- `pyproject.toml` with `ruff`, `black`, `mypy`, `pytest`, `coverage`, `hypothesis`.
- Pre-commit hooks wired and enforced in CI.
- MkDocs Material site with an ADR folder pre-seeded.
- Dockerfile + Makefile + `scripts/repro.sh` for one-command reproduction.
- `CITATION.cff` so every release is citable (Zenodo-compatible).
- GitHub Actions: CI, docs deploy, CodeQL, Dependabot.

## Quick start

```bash
make install   # creates venv and installs dev deps
make test      # runs pytest with coverage
make docs      # serves MkDocs locally
make repro     # full reproduction pipeline
```

## Philosophy

1. If it does not rerun deterministically, it did not happen.
2. Document decisions, not just code (see `docs/architecture/`).
3. Types are documentation that compiles.
4. Small surfaces, strong contracts.
5. Audit trails by default.

## Using this template

Click **Use this template -> Create a new repository** at the top of this page.

## License

MIT - see LICENSE.
