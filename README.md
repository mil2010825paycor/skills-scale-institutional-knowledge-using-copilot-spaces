# OctoAcme Project Management

This README is the central entry point to OctoAcme’s project management guidance. Use it to onboard to the way we work, find the process for your current project phase, and navigate ongoing delivery. Keep project-specific status and artifacts in the project repository so this remains a useful guide and the project’s own README or release document can serve as its single source of truth.

## Our approach

OctoAcme applies these principles to cross-functional projects delivering features, services, or integrations:

- **Customer-first delivery:** Prioritize customer value and usability.
- **Iterative delivery:** Deliver small, testable increments and learn from feedback.
- **Clear ownership:** Name a Project Manager (PM) and Product Lead for each project.
- **Data-informed decisions:** Define success measures, monitor impact, and adapt based on evidence.
- **Psychological safety:** Make space for candid feedback, learning, and blameless improvement.

## Project lifecycle

1. **Initiation:** Validate the need, define a measurable outcome, identify stakeholders, and decide whether to proceed.
2. **Planning:** Turn approved work into a prioritized, estimated backlog with acceptance criteria, ownership, dependencies, and a release plan.
3. **Execution:** Build, test, review, and iterate in small increments while tracking progress, risks, and quality.
4. **Release:** Confirm readiness, deploy, verify the result, and communicate the release.
5. **Close & Retrospective:** Capture what went well and what to improve; assign and follow up on actions.

## Find the right guide

### Getting started

- [Project Management Overview](docs/octoacme-project-management-overview.md) — Summary of OctoAcme’s principles, roles, artifacts, lifecycle, and communication cadence. **Use when** onboarding or looking for the overall model.

### Lifecycle guides

- [Project Initiation](docs/octoacme-project-initiation.md) — Validates and authorizes a project, with a one-pager template and decision gate. **Use when** exploring a new project idea or feature proposal.
- [Project Planning](docs/octoacme-project-planning.md) — Defines the backlog, estimates, Definition of Done, dependencies, and release milestones. **Use when** an initiative is approved and needs an actionable delivery plan.
- [Execution & Tracking](docs/octoacme-execution-and-tracking.md) — Covers team rhythms, board and pull request workflows, quality, metrics, and blocker escalation. **Use when** coordinating day-to-day delivery.
- [Release & Deployment](docs/octoacme-release-and-deployment.md) — Provides readiness requirements, deployment and verification steps, rollback guidance, and a release-notes template. **Use when** preparing or carrying out a production release.
- [Retrospective & Continuous Improvement](docs/octoacme-retrospective-and-continuous-improvement.md) — Guides team reflection and tracking owned improvement actions. **Use after** a sprint, release, milestone, or incident.

### Cross-cutting guidance

- [Risks & Communication](docs/octoacme-risks-and-communication.md) — Describes the risk register, stakeholder updates, communication templates, and escalation paths. **Use throughout** planning and execution, and whenever a risk, dependency, or incident needs attention.
- [Roles & Personas](docs/octoacme-roles-and-personas.md) — Defines the responsibilities and goals of Developers, Product Managers, and Project Managers. **Use when** clarifying ownership or tailoring collaboration to a role.

## Start by role

- **Developers:** Start with [Execution & Tracking](docs/octoacme-execution-and-tracking.md) for the team workflow and quality expectations; use [Project Planning](docs/octoacme-project-planning.md) for backlog and acceptance criteria.
- **Product Managers / Product Leads:** Start with [Project Initiation](docs/octoacme-project-initiation.md) to define the problem and success measures, then [Project Planning](docs/octoacme-project-planning.md) to prioritize and shape delivery. Refer to [Roles & Personas](docs/octoacme-roles-and-personas.md) for responsibilities.
- **Project Managers:** Start with the [Project Management Overview](docs/octoacme-project-management-overview.md), then use [Risks & Communication](docs/octoacme-risks-and-communication.md) and [Execution & Tracking](docs/octoacme-execution-and-tracking.md) to coordinate delivery.

## Key project artifacts

Create and maintain the artifacts needed for the project in its repository or project board:

- **Project Charter / One-pager:** Problem, SMART objective, success metrics, stakeholders, timeline, and initial risks.
- **Roadmap and Release Plan:** Milestones, release scope, and timing.
- **Sprint / Iteration Backlog:** Prioritized, estimated work with owners and acceptance criteria.
- **Acceptance Criteria and Definition of Done:** Shared expectations for completion and quality.
- **Risk Register:** Risks and dependencies with impact, likelihood, owner, mitigation, and status.
- **Retrospective Notes and Action Items:** Learnings, accountable owners, due dates, and follow-up.

Use the process guides above for the relevant templates and checklists. Keep status, decisions, risks, and release information current in the project’s chosen source of truth; add process-specific documents to `.copilot/` when they should provide context for Copilot Spaces.
