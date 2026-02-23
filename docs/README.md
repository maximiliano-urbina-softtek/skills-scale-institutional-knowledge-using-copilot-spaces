# OctoAcme Project Management Overview

This document summarizes the project management processes used by OctoAcme, serving as a quick onboarding and reference guide for the entire team.

## Project Lifecycle & Core Workflows

OctoAcme operates with a structured five-phase lifecycle: Initiation, Planning, Execution, Release, and Retrospective. Project work starts with a validated business case and a Project One-pager, followed by stakeholder alignment and approval. After Initiation, work moves into Planning, where items are broken into shippable increments, acceptance criteria are set, and release plans are created. During Execution, teams use GitHub Projects with columns like Backlog, Ready, In Progress, In Review, QA, Done, and follow disciplined pull request workflows—requiring automated tests, small PRs, and at least one approval per merge. Continuous quality checks and transparency drive consistent delivery.

## Key Roles & Communication Strategies

Three main roles shape OctoAcme's process: Project Managers (coordinate schedules and risk), Product Managers (define outcomes and measure success), and Developers (implement features and ensure testability). Communication includes daily standups, weekly PM-PdM syncs, monthly stakeholder updates, and structured escalation paths for blockers. Risks are tracked in a register, and escalations move up clearly defined levels for quick decision-making.

## Quality Assurance & Continuous Improvement

Quality is built into all phases, with unit tests, integration, and end-to-end smoke tests integrated into CI/CD pipelines, as well as manual QA as needed. Releases are distinguished by scope (patch, minor, major), each following a checklist: from acceptance criteria, CI passing, and release notes, to rollback and playbooks for incidents. After sprints and releases, retrospectives capture learnings and turn them into improvements, fostering a culture of continuous refinement.

---

## Process Documentation

For detailed guidance on each phase of project execution, refer to the following documents:

- [**octoacme-project-management-overview.md**](octoacme-project-management-overview.md) — High-level principles, roles, artifacts, and lifecycle
- [**octoacme-project-initiation.md**](octoacme-project-initiation.md) — Problem validation, stakeholder alignment, and one-pager template
- [**octoacme-project-planning.md**](octoacme-project-planning.md) — Scope, backlog, estimation, Definition of Done, and risk management
- [**octoacme-execution-and-tracking.md**](octoacme-execution-and-tracking.md) — Day-to-day execution, standups, PR workflows, quality, and metrics
- [**octoacme-risks-and-communication.md**](octoacme-risks-and-communication.md) — Risk registers, escalation paths, and stakeholder communication
- [**octoacme-release-and-deployment.md**](octoacme-release-and-deployment.md) — Release types, deployment checklists, rollback, and incident playbooks
- [**octoacme-retrospective-and-continuous-improvement.md**](octoacme-retrospective-and-continuous-improvement.md) — Retrospective structure and tracking improvements
- [**octoacme-roles-and-personas.md**](octoacme-roles-and-personas.md) — Detailed role descriptions for Developers, Product Managers, and Project Managers
