# 3cors CorIM Builder — Public Issue Tracker

This is the **public issue tracker** for the [3cors CorIM Builder](https://github.com/hcai42/3cors-corim). Use this repository to report bugs, request features, or suggest improvements.

> **Note:** This repository contains only issues — no source code. All code changes are implemented in the [hcai42/3cors-corim](https://github.com/hcai42/3cors-corim) repository.

---

## How to Create an Issue

1. Go to [**New Issue**](https://github.com/hcai42/3cors-corim-issues/issues/new/choose)
2. Choose the appropriate template:
   - **Bug Report** — something is broken or doesn't work as expected
   - **Feature Request** — you'd like new functionality or an enhancement
   - **Refactoring** — a code quality, performance, or architecture improvement
3. Fill out the template thoroughly — the more detail you provide, the faster the issue can be resolved

### What Makes a Good Issue?

A well-written issue contains:

- **A clear, specific title** — "Login fails after password reset" is better than "Login broken"
- **Steps to reproduce** (for bugs) — exact steps someone else can follow to see the same problem
- **Expected vs. actual behavior** — what should happen vs. what actually happens
- **Context** — screenshots, error messages, browser/device info, log output
- **Affected component** — Frontend, Backend, Database, or Infrastructure
- **Acceptance criteria** — concrete checklist of conditions that confirm the issue is resolved

### Bug Reports: What We Need

| Information | Why It Matters |
|---|---|
| Steps to reproduce | Without this, we cannot reliably find or verify the fix |
| Expected behavior | Clarifies what "fixed" looks like |
| Error messages / logs | Points directly to the root cause |
| Browser / device | Frontend issues often depend on the environment |
| Screenshots | A picture saves a thousand words of explanation |

### Feature Requests: What We Need

| Information | Why It Matters |
|---|---|
| Problem statement | Explains *why* the feature is needed, not just *what* |
| User story | Clarifies who benefits and how |
| Requirements | Defines the scope — what's in, what's out |
| Acceptance criteria | Makes it testable — how do we know it's done? |
| Mockups / examples | Visual references prevent misunderstandings |

---

## Automated Issue Processing

Issues in this repository can be automatically processed by our AI coding agent [Archon](https://github.com/hcai42/remote-coding-agent). When an issue is well-structured, a maintainer can trigger Archon to analyze, plan, implement, and create a pull request — all in the [hcai42/3cors-corim](https://github.com/hcai42/3cors-corim) code repository.

This is why structured, detailed issues matter: they enable faster, higher-quality automated resolution.

---

## Labels

| Label | Meaning |
|---|---|
| `bug` | Something is broken |
| `feature` | New functionality requested |
| `refactor` | Code quality or architecture improvement |
| `archon-ready` | Issue is well-defined and ready for automated processing |
| `priority:high` | Urgent — needs attention soon |
| `priority:medium` | Normal priority |
| `priority:low` | Nice to have |
| `frontend` | Relates to the UI (React / TypeScript) |
| `backend` | Relates to the API / server (Python / FastAPI) |
| `database` | Relates to schema, migrations, or queries |
| `infra` | Relates to Docker, deployment, or CI/CD |

---

## Related Repositories

| Repository | Description |
|---|---|
| [hcai42/3cors-corim](https://github.com/hcai42/3cors-corim) | CorIM Builder source code (where fixes and features land) |
| [hcai42/remote-coding-agent](https://github.com/hcai42/remote-coding-agent) | Archon — AI workflow engine for automated development |
