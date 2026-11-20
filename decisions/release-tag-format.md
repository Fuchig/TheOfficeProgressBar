---
status: accepted
sources:
  - claude:0022362e-f712-4a20-83c4-fa32ae3695dd
added: 2026-11-20
---

# Git release tags use the format `release-<version>`

## Context

The team needs a consistent naming scheme for Git release tags.

## Options

- `release-<version>` (e.g. `release-2.10.1`)
- `v<version>` or bare `<version>`

## Decision

Git release tags use `release-<version>`, e.g. `release-2.10.1`.

## Why

Team rule stated by the user.

## Consequences

When creating or referencing release tags, always use the `release-` prefix; no `v` prefix.
