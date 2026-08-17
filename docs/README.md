# OctoAcme Project Management Process Docs

## Overview
OctoAcme runs projects using a structured, iterative lifecycle that emphasizes customer value, clear ownership, and measurable outcomes. Projects begin with a lightweight initiation (a project one‑pager) to align stakeholders and define success metrics, then proceed through planning, execution, release, and retrospective phases. The processes prioritize small, testable increments, frequent feedback loops, and data‑informed decisions to reduce risk and accelerate learning.

Workflows center on a visible project board and disciplined pull request practices: backlog → ready → in progress → in review → QA → done, small PRs linked to issues and acceptance criteria, and CI gates for tests, linting, and security scans before review. Releases follow defined types (patch/minor/major) and a checklist that includes staging smoke tests, rollback plans, and post‑deploy verification to keep deployments safe and observable.

Roles are clearly defined so ownership is unambiguous: Product Managers own outcomes and prioritization; Project Managers coordinate plans, schedules, and stakeholder communications; Developers implement and test; QA validates acceptance criteria and runs manual checks when needed; Stakeholders provide input and approvals. Together these roles support artifacts like the Project One‑pager, release plan, Definition of Done, risk register, and retrospective action items.

This repository contains phase‑by‑phase guides and supporting process documents. Use this README as your navigation hub and follow the suggested starting points below to onboard quickly or run a new project.

## Navigation
### Getting Started
- [Project Management Overview](./octoacme-project-management-overview.md) — Introduction to OctoAcme's approach, roles, and key artifacts

### Phase-by-Phase Guides
- [Project Initiation Guide](./octoacme-project-initiation.md) — Steps to validate and authorize work, align stakeholders, and create a lightweight plan
- [Project Planning Guide](./octoacme-project-planning.md) — Turn approved initiatives into actionable plans and backlogs
- [Execution & Tracking Guide](./octoacme-execution-and-tracking.md) — Day-to-day execution, progress tracking, and blocker escalation
- [Release & Deployment Guide](./octoacme-release-and-deployment.md) — Standardized release and deployment processes
- [Retrospective & Continuous Improvement Guide](./octoacme-retrospective-and-continuous-improvement.md) — Capture learnings and convert them to improvements

### Supporting Processes
- [Risk Management & Communication Guide](./octoacme-risks-and-communication.md) — Identify, manage, and communicate risks and dependencies
- [Roles & Personas](./octoacme-roles-and-personas.md) — Definitions of key roles and responsibilities

## Quick Reference
Key principles:
- Customer-first; Iterative delivery; Clear ownership; Data-informed decisions; Psychological safety

Key artifacts:
- Project One-pager / Charter
- Backlog & Acceptance Criteria
- Definition of Done
- Risk Register
- Release notes & Rollback plan
- Retrospective action items

## Getting Started
- New to OctoAcme? Start with the [Project Management Overview](./octoacme-project-management-overview.md).
- Starting a new project? Follow the [Project Initiation Guide](./octoacme-project-initiation.md).
- Building and delivering? Reference the [Execution & Tracking Guide](./octoacme-execution-and-tracking.md).
- Releasing to production? Use the [Release & Deployment Guide](./octoacme-release-and-deployment.md).
- Want to suggest an improvement? Use the "Add Content to Project Management Process Docs" issue template.

## Contributing
Found a gap or want to suggest an improvement? Please use the "Add Content to Project Management Process Docs" issue template to propose updates.
