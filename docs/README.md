# OctoAcme Project Management Docs

Welcome to the OctoAcme Project Management documentation hub. This folder contains comprehensive guides to our project management processes, roles, and best practices.

## Project Management Approach

OctoAcme follows a customer-first, iterative delivery model with clear ownership and data-informed decisions. Our approach emphasizes psychological safety and continuous improvement across all cross-functional projects.

### Core Principles
- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Each project has a named Project Manager (PM) and Product Lead
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning

## Project Lifecycle

OctoAcme projects follow a structured five-phase lifecycle:

1. **Initiation** – Validate business need, align stakeholders, and create a lightweight plan
2. **Planning** – Break work into shippable increments with clear dependencies and timelines
3. **Execution** – Build, test, and track progress through daily standups and weekly syncs
4. **Release** – Deploy to production with standardized checklists and rollback procedures
5. **Close & Retrospective** – Capture learnings and drive continuous improvement

## Core Roles

- **Product Manager (PdM)** – Defines outcomes, prioritizes backlog, and measures success
- **Project Manager (PM)** – Coordinates delivery, manages schedules, risks, and communications
- **Developers** – Implement features, collaborate on design, and ensure code quality
- **QA/Testing** – Validate quality and acceptance criteria
- **Stakeholders** – Provide inputs, feedback, and approvals

## Key Artifacts

- Project Charter / One-pager
- Risk Register
- Prioritized backlog with acceptance criteria
- Definition of Done
- Release plan and milestones
- Retrospective notes and action items

## Communication Cadence

- **Daily**: Team standups (15 min) – progress, blockers, dependencies
- **Weekly**: Delivery sync – show progress, updates, and flagged risks
- **Weekly**: PM + PdM alignment
- **Monthly**: Stakeholder updates
- **Ad-hoc**: Escalations and incident response

## Quick Start

**New to OctoAcme?** Begin with [OctoAcme Project Management Overview](./octoacme-project-management-overview.md) for a high-level introduction.

**Starting a project?** Jump to [Project Initiation](./octoacme-project-initiation.md).

**In delivery mode?** Reference [Execution and Tracking](./octoacme-execution-and-tracking.md) for day-to-day guidance.

## Documentation Map

| Document | Purpose |
|----------|---------|
| [Project Management Overview](./octoacme-project-management-overview.md) | High-level introduction to OctoAcme's approach, roles, and key artifacts |
| [Project Initiation](./octoacme-project-initiation.md) | Starting a new project—validation, stakeholder alignment, go/no-go decision |
| [Project Planning](./octoacme-project-planning.md) | Planning and scoping guidance—backlog, dependencies, and release timelines |
| [Execution and Tracking](./octoacme-execution-and-tracking.md) | Building and tracking progress—workflows, quality, metrics, and escalation |
| [Risks and Communication](./octoacme-risks-and-communication.md) | Managing risks and stakeholder communication—registers, escalation paths, templates |
| [Release and Deployment](./octoacme-release-and-deployment.md) | Release procedures and deployment—pre-release requirements, rollback playbooks |
| [Retrospective and Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) | Learning from projects—retrospective structure and action item tracking |
| [Roles and Personas](./octoacme-roles-and-personas.md) | Team roles and responsibilities—detailed persona definitions and goals |

## Quality &amp; Testing Standards

OctoAcme emphasizes quality at every stage:
- Unit tests for new logic
- Integration tests where applicable
- End-to-end smoke tests for critical flows
- Security scanning in CI
- Manual QA for feature acceptance when needed
- Small, reviewable pull requests (≤ 400 lines)
- Automated testing and linting before PR review
- Minimum one approval before merging

## Risk Management

Every project maintains a **Risk Register** throughout execution, tracking:
- Risk ID, description, impact, and likelihood
- Owner and mitigation plan
- Status updates reviewed at weekly syncs

Escalation follows a three-tier model:
1. **Level 1**: Team-level triage in daily standup
2. **Level 2**: PM escalates to Product Lead and dependent teams
3. **Level 3**: Sponsor-level escalation for business-impacting issues

## Contributing to These Docs

To suggest updates or add new content to the OctoAcme process documentation:

1. Open an issue using the **[Add Content to Project Management Process Docs](.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml)** template
2. Describe the new content, why it's needed, and any suggested text
3. Reference relevant existing docs to ensure alignment
4. Include acceptance criteria from the template

## Additional Resources

- **Issue templates**: See [.github/ISSUE_TEMPLATE](../.github/ISSUE_TEMPLATE/) for structured process improvement requests
- **Copilot Spaces**: These docs are optimized for use with Copilot Spaces to provide context-specific guidance during project work
