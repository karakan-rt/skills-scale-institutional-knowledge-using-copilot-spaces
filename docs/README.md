# OctoAcme Project Management Docs

This README centralizes OctoAcme's project management process documents (stored in docs/) and provides a concise overview of how the team initiates, plans, executes, validates, and improves work. Use these links to find the canonical process documents and the short summary below to onboard quickly.

## Overview of OctoAcme project management processes

OctoAcme follows a lifecycle-driven approach that begins with a lightweight Initiation step and proceeds through Planning, Execution, Release, and Retrospective. Initiation uses a Project One-pager to capture the problem, objective, success metrics, stakeholders, and a rough timeline to decide whether to move forward. Approved initiatives are turned into a prioritized backlog during Planning, with clear acceptance criteria, estimates, and a Definition of Done to guide work.

During Execution, teams operate in short increments and use a project board (Backlog → Ready → In Progress → In Review → QA → Done) to manage flow. Work emphasizes small, reviewable pull requests with explicit acceptance criteria; CI and automated tests must pass before reviews. The team runs regular standups for daily coordination, a weekly delivery sync for progress and risks, and demos at the end of sprints or milestones to share outcomes and gather feedback.

Quality and risk practices are embedded in the process: unit and integration tests, end-to-end smoke tests for critical flows, automated security scans in CI, and manual QA when needed. Pre-release checklists (passing CI/security scans, release notes, rollback plans, and smoke tests) reduce deployment risk. A simple Risk Register captures identified risks, mitigation plans, and owners, while escalation paths (team → PM → Product Lead → Sponsor) and incident communication templates support timely, blameless responses when issues arise.

## Key roles and communication

- Product Managers (PdM): define outcomes, prioritize the backlog, and measure success.
- Project Managers (PM): coordinate schedules, risks, stakeholder communication, and meeting cadence.
- Developers: implement features, write tests, and participate in reviews and design discussions.
- QA/Testing: validate acceptance criteria and sign off on releases.

Communication cadence includes daily standups, weekly PM+PdM syncs, weekly delivery syncs, regular demos, and monthly stakeholder updates. The project README/docs act as the single source of truth for processes and updates.

## Documents (links)

- [Project Management Overview](docs/octoacme-project-management-overview.md)
- [Project Initiation Guide](docs/octoacme-project-initiation.md)
- [Project Planning](docs/octoacme-project-planning.md)
- [Execution & Tracking](docs/octoacme-execution-and-tracking.md)
- [Risks & Communication](docs/octoacme-risks-and-communication.md)
- [Release & Deployment](docs/octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](docs/octoacme-retrospective-and-continuous-improvement.md)
- [Roles & Personas](docs/octoacme-roles-and-personas.md)

## Where to propose updates

Propose changes via the repository's "Add Content to Project Management Process Docs" issue template (.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) and include the suggested content, rationale, and acceptance criteria.
