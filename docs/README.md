# OctoAcme Project Management Docs

Welcome to OctoAcme's project management documentation. This is the central
entry point for understanding how OctoAcme plans, executes, and delivers
projects, and it links out to the detailed process guides in this folder.

## Quick Start

New to OctoAcme? Start with the [Project Management Overview](octoacme-project-management-overview.md)
for a high-level introduction, then explore the documents below based on
where you are in the project lifecycle:

| Document | Purpose |
| --- | --- |
| [octoacme-project-management-overview.md](octoacme-project-management-overview.md) | Concise, shareable introduction to OctoAcme's principles, roles, artifacts, and lifecycle. Best first read for new teammates. |
| [octoacme-project-initiation.md](octoacme-project-initiation.md) | Steps to validate and authorize new work, align stakeholders, and create a lightweight initial plan. |
| [octoacme-project-planning.md](octoacme-project-planning.md) | Turning an approved initiative into an actionable plan, backlog, milestones, and resourcing. |
| [octoacme-execution-and-tracking.md](octoacme-execution-and-tracking.md) | Day-to-day execution guidance: team rhythm, PR/board workflows, quality practices, and blocker escalation. |
| [octoacme-risks-and-communication.md](octoacme-risks-and-communication.md) | How to identify, track, and communicate risks and dependencies, including templates and escalation paths. |
| [octoacme-release-and-deployment.md](octoacme-release-and-deployment.md) | Standardized process for releasing features to production safely and with good observability. |
| [octoacme-retrospective-and-continuous-improvement.md](octoacme-retrospective-and-continuous-improvement.md) | Capturing learnings after a project or release and converting them into actionable improvements. |
| [octoacme-roles-and-personas.md](octoacme-roles-and-personas.md) | Detailed persona definitions (Developers, Product Managers, Project Managers) with responsibilities, goals, and communication patterns. |

## OctoAcme Project Management Process Summary

OctoAcme follows a structured, lifecycle-based approach to project
management grounded in five core principles: customer-first priorities,
iterative delivery, clear ownership, data-informed decisions, and
psychological safety. The organization applies this framework across all
cross-functional projects through a five-phase lifecycle: initiation
(validating business need and stakeholder alignment), planning (breaking
work into shippable increments), execution (building and testing), release
(deploying to production), and close/retrospective (capturing learnings).
This approach emphasizes lightweight governance with meaningful
checkpoints—particularly decision gates after initiation and before
planning—to ensure projects move forward with clarity and stakeholder
buy-in.

Three primary roles anchor OctoAcme's delivery model. Project Managers
coordinate schedules, risks, and communications to ensure on-time delivery
and maintain transparency; Product Managers define what should be built,
prioritize the backlog, and measure outcomes; and Developers implement
features, maintain code quality, and identify technical risks. Supporting
these core roles are QA/Testing and Stakeholder groups, each with defined
responsibilities for quality assurance and strategic input. Clear role
definition reduces ambiguity and ensures each party understands their
contribution to project success.

Execution and tracking rely on a rhythm of regular touchpoints: daily
standups (15 minutes focused on progress and blockers), weekly delivery
syncs with PM/PdM alignment, and milestone-based reviews or sprint demos.
Work is organized on project boards using a Backlog → Ready → In Progress →
In Review → QA → Done workflow, with pull requests kept small (≤400 lines
where possible) and required to include issue links and acceptance
criteria. Quality is embedded throughout via unit tests, integration tests,
end-to-end smoke tests, security scanning in CI, and manual QA for feature
acceptance—supported by a Definition of Done checklist that teams document
and follow.

Risk management and communication are woven into every phase. OctoAcme
maintains a Risk Register capturing ID, description, impact, likelihood,
owner, and mitigation status, reviewed weekly and escalated through a
structured path (team-level → PM → Product Lead → Sponsor). Stakeholder
communication is standardized through weekly status templates covering
progress, next steps, risks/blockers, and decisions needed, with a single
source of truth for project status. This combination of lightweight
governance, clear roles, consistent rhythm, embedded quality practices, and
transparent risk communication enables OctoAcme to deliver reliably while
maintaining flexibility and team morale.

## Core Project Lifecycle

1. **Initiation** — problem statement, stakeholders, high-level timeline. See [octoacme-project-initiation.md](octoacme-project-initiation.md).
2. **Planning** — scope, resources, milestones, dependencies. See [octoacme-project-planning.md](octoacme-project-planning.md).
3. **Execution** — build, test, review, iterate. See [octoacme-execution-and-tracking.md](octoacme-execution-and-tracking.md).
4. **Release** — deploy, verify, announce. See [octoacme-release-and-deployment.md](octoacme-release-and-deployment.md).
5. **Close & Retrospective** — capture learnings and next steps. See [octoacme-retrospective-and-continuous-improvement.md](octoacme-retrospective-and-continuous-improvement.md).

## Key Principles

- **Customer-first**: prioritize customer value and usability.
- **Iterative delivery**: deliver small, testable increments.
- **Clear ownership**: each project has a named Project Manager (PM) and Product Lead.
- **Data-informed**: measure impact and iterate based on evidence.
- **Psychological safety**: encourage feedback and learning.

## Core Roles

- **Project Manager (PM)**: coordinates delivery, schedules, risk, and communications.
- **Product Manager (PdM)**: defines outcomes, prioritizes the backlog, and measures success.
- **Developers**: implement features and collaborate on design and testability.
- **QA/Testing**: validate quality and acceptance criteria.
- **Stakeholders**: provide inputs and approvals.

See [octoacme-roles-and-personas.md](octoacme-roles-and-personas.md) for detailed persona definitions.

## Key Artifacts

- Project Charter / One-pager
- Roadmap and Release Plan
- Sprint/Iteration Backlog
- Acceptance Criteria & Definition of Done
- Risk Register
- Retrospective notes and action items

## Communication Cadence

- Daily standups (15 min) — progress, blockers, dependencies
- Weekly sync between PM + PdM
- Weekly delivery sync — updates and flagged risks
- Sprint planning and milestone demos/reviews
- Monthly stakeholder updates
- Ad-hoc escalations as needed

## Contributing to These Docs

- Keep documents accurate and up to date as processes evolve.
- When adding a new process document to `docs/`, add a corresponding entry
  to the Quick Start table above with a brief description of its purpose.
- Add process-specific docs into `.copilot/` if you want Copilot Spaces to
  use them as context.
- Keep the Project Charter updated in the project repo.
