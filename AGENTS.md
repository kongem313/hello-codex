# How to work on this repo (for humans and Codex)

## Tooling
- Python 3.11
- Package manager: pip (venv already active)
- Test: `pytest -q`
- Lint: `ruff check .`
- Format: `black .`
- Types: `mypy .` (optional if config present)

## Conventions
- Keep functions small; add docstrings for public functions.
- Add tests for new features and bug fixes.
- Treat linter warnings as issues to fix, not ignore.

## Definition of done
- All tests pass locally and in CI.
- Lint/format clean.
- README updated when behavior changes.
