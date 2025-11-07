# OctoAcme Project Management Docs

This folder centralizes OctoAcme’s project management process documentation. The guidance here captures how we turn ideas into measured outcomes: a stage-based lifecycle (Initiation → Planning → Execution → Release → Close), clear role definitions, lightweight artifacts that travel with the project, and a predictable communication cadence to keep stakeholders aligned. Use this README as the single entry point to find the detailed guides for each stage and the templates the team uses day-to-day.

OctoAcme emphasizes small, testable increments and clear ownership. Work is tracked on a project board (Backlog → Ready → In Progress → In Review → QA → Done) and delivered through disciplined pull request and CI practices: small PRs when possible, linked issues and acceptance criteria in PRs, automated tests and security scans in CI, and at least one reviewer before merging. Releases follow a checklist (staging smoke tests, rollback plan, release notes) and pair automated pipelines with post-deploy verifications. Quality assurance combines automated unit and integration tests, end-to-end smoke tests for critical flows, security scans, and manual QA for human-validated acceptance.

Roles and responsibilities are explicit so decisions and handoffs are fast and low-friction. Product Managers (PdMs) own outcomes and prioritization; Project Managers (PMs) coordinate delivery, timelines, communication, and risks; Developers implement and test changes; QA validates acceptance; Stakeholders provide inputs and approvals. These personas are described in the Roles & Personas doc, and the docs explain where each role typically contributes (e.g., who drafts the one-pager, who maintains the risk register, who runs retrospectives).

Communication and continuous improvement are formalized with a regular cadence and templates: daily standups for blockers, a weekly PM + PdM alignment, regular delivery syncs and demos, and monthly stakeholder updates. Risks and dependencies live in a Risk Register and are reviewed in the weekly sync with clear escalation paths. Retrospectives after sprints, releases, or incidents capture action items that are tracked back into the backlog so improvements are measurable and iteratively delivered.

Docs in this folder
- Project overview: docs/octoacme-project-management-overview.md
- Project initiation: docs/octoacme-project-initiation.md
- Project planning: docs/octoacme-project-planning.md
- Execution & tracking: docs/octoacme-execution-and-tracking.md
- Risk management & communication: docs/octoacme-risks-and-communication.md
- Release & deployment: docs/octoacme-release-and-deployment.md
- Retrospective & continuous improvement: docs/octoacme-retrospective-and-continuous-improvement.md
- Roles & personas: docs/octoacme-roles-and-personas.md

How to use and contribute
- Keep the Project One-pager and project README updated in the project repo as the single source of truth.
- To propose changes to these process docs, use the ".github/ISSUE_TEMPLATE/Add Content to Project Management Process Docs" issue template.
- For Copilot Spaces context: add process-specific docs to `.copilot/` if you want the space to include them as part of context.
