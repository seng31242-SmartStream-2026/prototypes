# Prototypes

**Project:** SmartStream – Integrated Business Management System  
**Course:** SENG 31242 – System Design Project  
**Group:** Group 07 – NextGen Developers  
**Organisation:** University of Kelaniya, Faculty of Science – Software Engineering Teaching Unit

---

## Purpose

This repository holds all UI/UX design artefacts produced during the **design phase** of the SmartStream project, including wireframes, Figma exports, and low-fidelity prototypes. Content here directly supports the UI Design section of the Software Design Specification (SDS).

> **Design phase only.** This repository is active during Weeks 5–8. Prototyping artefacts are not produced during the requirements engineering phase.

---

## Repository Structure

```
prototypes/
├── wireframes/
│   ├── *.fig / *.drawio            # Source wireframe files
│   └── exports/                    # Exported PNG or PDF wireframes (one file per screen)
├── figma-exports/
│   └── *.pdf / *.png               # Exports from Figma (high-fidelity where applicable)
├── low-fidelity/
│   └── *.png / *.jpg               # Sketches or low-fidelity prototype images
├── navigation-flow/
│   ├── navigation-flow.drawio      # Source file for the navigation flow diagram
│   └── navigation-flow.svg         # Exported navigation flow diagram
└── ux-decisions/
    └── ux-rationale.md             # UX decisions and rationale for key design choices
```

---

## Screens to Cover

The following major screens are required for the SmartStream system:

| Screen | Description |
|--------|-------------|
| Login | Role-based login page |
| Executive Dashboard | Real-time KPI overview for Directors |
| Inventory Management | Stock listing, search, and low-stock indicators |
| Invoice Generation | Create and manage invoices |
| Accounting / Finance | Financial records and reports |
| User Management | RBAC – manage roles and user accounts |
| Alerts & Notifications | Email/SMS alert configuration and log |

---

## Tooling Required

| File Type | Tool to Open |
|-----------|-------------|
| `.fig` | [Figma](https://figma.com) |
| `.drawio` | [draw.io / diagrams.net](https://app.diagrams.net) |
| `.pdf` | Any PDF viewer |
| `.png` / `.svg` | Any image viewer or browser |

> Source files (`.fig`, `.drawio`) must always be committed alongside their exported images so that peers can open and edit them.

---

## Branching & Contribution

Please read [CONTRIBUTING.md](./CONTRIBUTING.md) before making any changes.

Key rules:
- `main` is protected. All changes must go through a Pull Request with **at least 1 approving review**.
- Use `draft/<document>` branches for active work (e.g. `draft/wireframe-dashboard`).
- Use `fix/<issue-number>` branches for corrections after review (e.g. `fix/55`).
- All commit messages must follow the Conventional Commits convention (see CONTRIBUTING.md).

---

## Team

| Student No. | Name |
|-------------|------|
| SE/2022/002 | Dinith Ankitha |
| SE/2022/003 | Akila Abenayaka |
| SE/2022/017 | Maleesha Rukshan |
| SE/2022/022 | Hirushi Wickramarachchi |
| SE/2022/034 | Avishka Medagamagodage |

**Academic Supervisors:** Dr. Nalin Warnajith · Prof. (Mrs) Isuru Hewapathirana · Eng. Dr. Tiroshan Madushanka
