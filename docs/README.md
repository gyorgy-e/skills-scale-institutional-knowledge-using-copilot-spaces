# OctoAcme Project Management Docs

Welcome to the OctoAcme project management documentation. These guides provide standardized processes, roles, and best practices for running successful projects at OctoAcme.

## Quick Start

- **New to OctoAcme projects?** Start with the [Project Management Overview](./octoacme-project-management-overview.md)
- **Starting a new project?** Read the [Project Initiation Guide](./octoacme-project-initiation.md)
- **Planning and executing work?** See [Project Planning](./octoacme-project-planning.md) and [Execution & Tracking](./octoacme-execution-and-tracking.md)
- **Managing risks?** Check [Risk Management & Communication](./octoacme-risks-and-communication.md)
- **Releasing to production?** Follow the [Release & Deployment Guide](./octoacme-release-and-deployment.md)
- **Learning from experience?** See [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)
- **Understanding roles?** Review [OctoAcme Personas](./octoacme-roles-and-personas.md)

## Core Project Lifecycle

OctoAcme projects follow these phases:

1. **Initiation** — Validate business need, align stakeholders, create project charter
2. **Planning** — Define scope, estimate work, plan dependencies and releases
3. **Execution** — Build, test, and iterate with regular demos and risk tracking
4. **Release** — Deploy to production with safety checks and rollback plans
5. **Close & Retrospective** — Capture learnings and drive continuous improvement

## Key Principles

- **Customer-first**: prioritize customer value and usability
- **Iterative delivery**: ship small, testable increments
- **Clear ownership**: each project has named PM and Product Lead
- **Data-informed**: measure impact and iterate based on evidence
- **Psychological safety**: encourage feedback and learning

## OctoAcme Project Management Overview

OctoAcme follows a structured, lifecycle-based approach to project management grounded in five core principles: customer-first priorities, iterative delivery, clear ownership, data-informed decisions, and psychological safety. The organization applies this framework across all cross-functional projects through a five-phase lifecycle spanning initiation (validating business need and stakeholder alignment), planning (breaking work into shippable increments), execution (building and testing), release (deploying to production), and close/retrospective (capturing learnings).

**Three primary roles** anchor OctoAcme's delivery model:
- **Project Managers** coordinate schedules, risks, and communications to ensure on-time delivery and maintain transparency
- **Product Managers** define what should be built, prioritize the backlog, and measure outcomes
- **Developers** implement features, maintain code quality, and identify technical risks

**Execution and tracking** rely on a consistent rhythm of regular touchpoints: daily standups (15 minutes focused on progress and blockers), weekly delivery syncs with PM/Product Manager alignment, and milestone-based reviews or sprint demos. Work is organized on project boards using a Backlog → Ready → In Progress → In Review → QA → Done workflow, with pull requests kept small (≤400 lines where possible) and required to include issue links and acceptance criteria. Quality is embedded throughout via unit tests, integration tests, end-to-end smoke tests, security scanning in CI, and manual QA for feature acceptance.

**Risk management and communication** are woven into every phase. OctoAcme maintains a Risk Register capturing ID, description, impact, likelihood, owner, and mitigation status, reviewed weekly and escalated through a structured path (team-level → PM → Product Lead → Sponsor). Stakeholder communication is standardized through weekly status templates covering progress, next steps, risks/blockers, and decisions needed, with a single source of truth for project status.

## Core Roles

OctoAcme projects typically include the following roles:

- **Project Manager (PM)**: Coordinates delivery, schedules, risk, and communications
- **Product Manager (PdM)**: Defines outcomes, prioritizes backlog, and measures success
- **Developers**: Implement features, collaborate on design and testability
- **QA/Testing**: Validate quality and acceptance criteria
- **Stakeholders**: Provide inputs and approvals

## Key Artifacts

Across all projects, you'll create and maintain:

- Project Charter / One-pager
- Roadmap and Release Plan
- Sprint/Iteration Backlog
- Acceptance Criteria & Definition of Done
- Risk Register
- Retrospective notes and action items

## Communication Cadence

- **Weekly sync** between PM and Product Manager
- **Twice-weekly standups** for delivery team (or as agreed)
- **Monthly stakeholder updates**
- **Ad-hoc escalations** as needed

## Contributing to These Docs

To propose updates or additions to the OctoAcme project management documentation:

1. Use the [Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) issue template
2. Provide a clear summary of the change and rationale
3. Include suggested content if applicable
4. Submit for review and feedback from the team

These documents are living artifacts. Your feedback and improvements help keep our processes relevant and effective.
