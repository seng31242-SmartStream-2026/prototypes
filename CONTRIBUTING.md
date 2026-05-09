# Contributing to `prototypes`

**Project:** SmartStream – Integrated Business Management System
**Group:** Group 07 – NextGen Developers

> **Design phase only** — this repository is active during Weeks 5–8.

---

## Branching Strategy

| Branch | Purpose |
|--------|---------|
| `main` | Protected. Merge via Pull Request only, minimum 1 approval. |
| `draft/<document>` | Working branch for a wireframe or prototype in progress. e.g. `draft/wireframe-dashboard` |
| `fix/<issue-number>` | Corrective changes after review feedback. e.g. `fix/55` |

---

## Commit Message Format

```
<type>(scope): short summary

Closes #<issue-number>
```

| Type | When to use |
|------|-------------|
| `feat` | Adding a new wireframe or prototype screen |
| `fix` | Correcting a design error or review feedback |
| `docs` | Updating UX rationale or design decision notes |
| `chore` | README, .gitignore housekeeping |

**Good:** `feat(wireframes): add executive dashboard wireframe`
**Bad:** `new screen`, `updated design`, `final`

---

## Pull Request Rules

- Minimum **1 approving review** before merging into `main`
- PR must reference the related issue: `Closes #<number>`
- No unresolved comments before merging
- Author must **not** merge their own PR

---

## Key Rules

- Always commit both the **source file** (`.fig` / `.drawio`) and the **exported image** (SVG / PNG)
- Update the navigation flow diagram if a new screen is added
- Never commit directly to `main`
