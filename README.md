# 3cors CorIM — Issue Tracker

Public issue tracker for the **3cors CorIM Builder** component.

## Purpose

This repository is dedicated to tracking bugs, feature requests, and improvements for CorIM Builder. Issues documented here are structured to be actionable by [Archon](https://github.com/hcai42/remote-coding-agent) workflows for automated implementation.

## How to file an issue

Use one of the issue templates:

- **Bug Report** — something is broken or behaving unexpectedly
- **Feature Request** — a new capability or enhancement
- **Refactoring** — code quality, performance, or architecture improvements

## Archon Integration

Issues in this repo are designed to be picked up by Archon's `archon-fix-github-issue` workflow:

```bash
archon workflow run archon-fix-github-issue --branch fix/issue-<number> "Fix hcai42/3cors-corim-issues#<number>"
```

To make issues Archon-friendly, always include:
- **Clear problem description** with steps to reproduce (for bugs)
- **Affected files/components** when known
- **Acceptance criteria** that can be validated
- **Labels** for priority and type

## Labels

| Label | Description |
|-------|-------------|
| `bug` | Something is broken |
| `feature` | New functionality |
| `refactor` | Code quality / architecture |
| `archon-ready` | Issue is well-defined enough for Archon to pick up |
| `priority:high` | Should be addressed soon |
| `priority:medium` | Normal priority |
| `priority:low` | Nice to have |
| `frontend` | UI/UX related |
| `backend` | API/server related |
| `database` | Schema/migration related |
| `infra` | Docker/deployment/CI related |

## Related Repositories

- [3cors-engine](https://github.com/miiwins/3cors-engine) — Platform monorepo (private)
- [remote-coding-agent](https://github.com/hcai42/remote-coding-agent) — Archon workflow engine
