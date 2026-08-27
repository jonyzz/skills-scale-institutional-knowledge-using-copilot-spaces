# OctoAcme Project Management Documentation

## Overview

OctoAcme follows a structured, customer-first approach to project delivery grounded in clear ownership, iterative delivery, and data-informed decisions. This docs collection is the single entry point for the project lifecycle from initiation through planning, execution, release, and continuous improvement. Use these files to understand roles, artifacts, meeting cadence, risk management, and the quality controls that keep releases safe and reliable.

## Project management processes summary

OctoAcme begins work with a lightweight Project One-pager to confirm the business need, define measurable success metrics, identify stakeholders, and set a high-level timeline. Approved initiatives move to planning where teams run kickoff meetings, create a prioritized backlog with acceptance criteria, estimate scope, and define the Definition of Done. Execution uses a project board workflow (Backlog → Ready → In Progress → In Review → QA → Done) and a disciplined Pull Request process: small PRs when possible, linked issues and acceptance criteria, CI checks, and required approvals before merge. Risk and dependency management is explicit (Risk Register entries, weekly reviews), and blockers are escalated using a defined path from team-level to sponsor-level as required.

## Roles & communication

Roles are clearly defined so responsibilities and handoffs remain visible: Product Managers own outcomes and prioritization; Project Managers coordinate schedules, risks, and stakeholder communications; Developers implement features and tests; QA validates acceptance and runs manual or automated checks; stakeholders provide approvals and input. Communication cadence includes daily standups for progress and blockers, weekly PM–PdM syncs, regular demos at the end of sprints or milestones, and monthly stakeholder updates. Templates (weekly status, incident summaries) help keep messages consistent and actionable.

## Quality assurance & release practices

QA combines automated and targeted manual checks: unit and integration tests, security scanning in CI, and end-to-end smoke tests for critical flows. PRs must pass CI and linting and include acceptance criteria. Releases follow a checklist: pre-release verification, staging smoke tests, automated production deployment where possible, and post-deploy verification. A rollback/incident playbook is available for production problems and retrospectives feed continuous improvement back into the backlog.

## Quick links

- Project Management Overview — octoacme-project-management-overview.md — high-level intro to roles, principles, and artifacts
- Project Initiation Guide — octoacme-project-initiation.md — how we validate ideas and authorize work
- Project Planning — octoacme-project-planning.md — backlog creation, estimation, and release planning
- Execution & Tracking — octoacme-execution-and-tracking.md — day-to-day workflow, PR conventions, and tracking
- Risks & Communication — octoacme-risks-and-communication.md — risk register, escalation, and stakeholder messaging
- Release & Deployment — octoacme-release-and-deployment.md — release types, checklist, and rollback playbook
- Retrospective & Continuous Improvement — octoacme-retrospective-and-continuous-improvement.md — running retros and tracking action items
- Roles & Personas — octoacme-roles-and-personas.md — role descriptions and responsibilities

## Getting started

New team members should read Project Management Overview first to get the big picture, then follow the phase documents for activities they need to perform (initiation → planning → execution → release → retrospective). For quick questions, check the project README and the Risk Register for current blockers and dependencies.
