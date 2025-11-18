# OctoAcme Project Management Overview

This repository's `docs/` folder contains OctoAcme's project and delivery processes.  The purpose of this short README is to provide a single, concise overview and a bridge to the more detailed documents in this directory.

## High-level lifecycle

OctoAcme follows an iterative delivery lifecycle with defined gates and artifacts:

- Initiation: A project one‑pager and stakeholder alignment so goals and scope are well understood.
- Planning: Define backlog, estimates, Definition of Done (DoD), acceptance criteria, and trench planning.
- Execution: Iterative sprints and work tracked in a project board with Pull Requests and CI.
- Release: Releases follow a checklist (pre‑release acceptance checks, CI/security passing, notes, and rollback plan).
- Close & Retrospective: Retrospectives produce prioritized action items tracked back to the backlog.

## Board and work flow

Typical board columns are Backlog → Ready → In Progress → In Review → QA → Done.  PRs should be small and focused (ideally <= 400 lines).  Each issue or PR should contain acceptance criteria and link to supporting tasks and artifacts in the project board.

## Roles & ownership

- Product Lead (PdM): defines outcomes and success metrics.
- Project Manager (PM): coordinates delivery and tracks risks and dependencies.
- Developers: implement features and write tests.
- QA / Testing: validate acceptance criteria, run manual/automated tests.

Roles are documented in detail in `octoacme-roles-and-personas.md`.

## Communication & cadence

- Daily standups for progress and blockers (15 minutes).
- Weekly delivery syncs for status and risks.
- Sprint demos and milestone reviews.
- Monthly stakeholder updates and incident templates where appropriate.

## Quality & release checklists

Quality gates include unit and integration tests, end‑to‑end smoke tests for critical flows, security scanning in CI, and manual QA when needed.  Releases use a checklist with pre‑release acceptance criteria, CI/security gates, release notes, and rollback plans; post‑deploy verifications and a blameless playbook are part of the process.

## Risks, escalations & continuous improvement

Risks are tracked in a lightweight Risk Register (ID, impact, likelihood, owner, mitigation, status).  Escalations follow a tiered path from triage to PM → Product Lead → Sponsor.  Retrospectives close the loop by returning prioritized action items to the backlog.

## Where to find more details

Detailed processes and templates are available in this folder:

- `octoacme-project-management-overview.md`
- `octoacme-project-initiation.md`
- `octoacme-project-planning.md`
- `octoacme-execution-and-tracking.md`
- `octoacme-release-and-deployment.md`
- `octoacme-retrospective-and-continuous-improvement.md`
- `octoacme-roles-and-personas.md`
- `octoacme-risks-and-communication.md`

---
Created by the OctoAcme playbook — see the individual docs for templates, checklists, and artifacts.
