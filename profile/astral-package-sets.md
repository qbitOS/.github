# Astral Package Sets (qbitOS)

Reference source: <https://github.com/orgs/astral-sh/repositories>

This page is the click-through target for the Astral partner badges on the org profile.

## Core Runtime Set

| Artifact | Upstream | Lane | qbitOS usage |
|---|---|---|---|
| uv | <https://github.com/astral-sh/uv> | tracked | runtime/env bootstrap |
| ruff | <https://github.com/astral-sh/ruff> | tracked | lint and formatting quality lane |
| ty | <https://github.com/astral-sh/ty> | tracked | type-check signal lane |
| pyx | <https://astral.sh/pyx> | reference | requested Granite/QPU package handler pathway |

## CI and Release Set

| Artifact | Upstream | Lane | qbitOS usage |
|---|---|---|---|
| setup-uv | <https://github.com/astral-sh/setup-uv> | reference | GitHub Actions runtime setup |
| ruff-action | <https://github.com/astral-sh/ruff-action> | reference | lint action path |
| ruff-pre-commit | <https://github.com/astral-sh/ruff-pre-commit> | reference | pre-commit checks |
| uv-pre-commit | <https://github.com/astral-sh/uv-pre-commit> | reference | dependency and env checks |

## pyx Auth and Supply Chain Set

| Artifact | Upstream | Lane | qbitOS usage |
|---|---|---|---|
| pyx-auth-action | <https://github.com/astral-sh/pyx-auth-action> | reference | trusted publishing auth |
| attest-action | <https://github.com/astral-sh/attest-action> | reference | artifact attestation |
| python-build-standalone | <https://github.com/astral-sh/python-build-standalone> | reference | portable Python build options |

## Lane Definitions

- `fork`: qbitOS maintains forked upstream
- `reference`: upstream consumed as reference lane
- `tracked`: upstream pinned and monitored in qbitOS workflows
- `modified`: qbitOS wrappers/config alter behavior for production lanes
