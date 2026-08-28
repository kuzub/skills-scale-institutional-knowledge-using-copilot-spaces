# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Developers

### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

### Interactions with Other Roles
- **Technical Lead/Architect**: Receives technical design guidance and mentorship; collaborates on complex architectural decisions
- **QA/Testing Lead**: Works with QA to ensure acceptance criteria are met and testable
- **Product Managers**: Implements features based on prioritized backlog and acceptance criteria
- **Project Managers**: Provides status updates and identifies blockers during standups and planning

---

## Product Managers

### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

### Interactions with Other Roles
- **Stakeholder/Sponsor**: Aligns on business priorities and success metrics; reports on progress and impact
- **UX/Design Lead**: Collaborates on user research, design validation, and acceptance criteria refinement
- **Technical Lead/Architect**: Discusses technical trade-offs and feasibility of features
- **Project Managers**: Coordinates on release planning and stakeholder communication

---

## Project Managers

### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

### Interactions with Other Roles
- **Stakeholder/Sponsor**: Escalates risks, obtains approvals, and communicates progress to leadership
- **Product Managers**: Aligns on priorities and release schedules
- **Technical Lead/Architect**: Identifies and manages technical risks and dependencies
- **QA/Testing Lead**: Coordinates quality gates and pre-release sign-offs
- **Developers**: Manages workload, resolves blockers, and maintains sprint pace

---

## QA/Testing Lead

### Role Summary
QA/Testing Leads own quality assurance strategy, test planning, and acceptance validation. They ensure that products meet quality standards before release and reduce defects reaching production.

### Responsibilities
- Create comprehensive test plans aligned with acceptance criteria
- Execute functional, integration, and system testing
- Validate that acceptance criteria are met before release
- Report quality metrics and defect trends
- Collaborate on test automation strategy
- Conduct acceptance testing before production deployment
- Identify and escalate quality risks

### Goals
- Ensure product meets quality standards before release
- Reduce defects in production and improve product reliability
- Enable fast, confident deployments through comprehensive testing
- Support continuous improvement of quality processes

### Typical Communication
- Sprint planning and acceptance criteria refinement
- Pull request reviews (from QA perspective)
- Pre-release sign-offs and deployment readiness reviews
- Quality metrics reporting in stakeholder updates
- Incident investigations and post-mortems

### Interactions with Other Roles
- **Developers**: Defines testable acceptance criteria; participates in code reviews to assess testability
- **Product Managers**: Refines acceptance criteria to ensure they are testable and measurable
- **Project Managers**: Provides quality metrics and signals release readiness
- **Technical Lead/Architect**: Collaborates on test strategy for complex architectural changes

---

## Stakeholder/Sponsor

### Role Summary
Stakeholders and Sponsors provide business context, approve scope and resources, and advocate for project outcomes. They represent business interests, governance requirements, and organizational strategy alignment.

### Responsibilities
- Define business requirements and success metrics in alignment with organizational goals
- Approve project charter, scope, and major resource allocation decisions
- Remove organizational blockers and provide cross-functional support
- Communicate project status, outcomes, and impact to leadership
- Approve go/no-go decisions at major gates (initiation, planning, release)
- Provide guidance on business priorities and trade-offs

### Goals
- Ensure project delivers business value and ROI
- Align project outcomes with organizational strategy and priorities
- Maintain governance and risk oversight
- Support team success through resource enablement and blocker removal

### Typical Communication
- Monthly stakeholder updates and executive briefings
- Decision gate reviews and approval meetings
- Escalation resolution and blocker removal
- Project charter and one-pager reviews
- Release announcements and business impact reporting

### Interactions with Other Roles
- **Project Managers**: Receives status updates, approves major decisions, escalates strategic issues
- **Product Managers**: Aligns on business priorities, success metrics, and customer impact
- **Technical Lead/Architect**: Reviews technical risks that impact business timelines
- **All Roles**: Provides strategic context and organizational enablement

---

## Technical Lead/Architect

### Role Summary
Technical Leads and Architects design technical solutions and ensure architectural quality across projects. They guide technical decisions, mentor developers, and identify technical risks that could impact project success.

### Responsibilities
- Define technical architecture and design decisions
- Review complex pull requests and technical designs
- Identify and mitigate technical risks
- Mentor developers on technical best practices
- Ensure solutions meet non-functional requirements (scalability, performance, security, maintainability)
- Guide technical trade-offs and feasibility assessments
- Support code quality and technical debt management

### Goals
- Build scalable, maintainable, and secure technical solutions
- Reduce technical debt and complexity over time
- Enable consistent, repeatable technical practices across the team
- Support team growth through mentorship and knowledge sharing

### Typical Communication
- Technical design reviews and architecture discussions
- Complex pull request reviews and guidance
- Risk assessments and technical feasibility discussions
- Technical onboarding and mentorship sessions
- Design documentation and technical decision records

### Interactions with Other Roles
- **Developers**: Provides guidance on technical design, mentors on best practices, and reviews complex PRs
- **Product Managers**: Assesses technical feasibility and discusses trade-offs
- **Project Managers**: Identifies technical risks and dependencies
- **QA/Testing Lead**: Collaborates on test strategy for architectural components

---

## UX/Design Lead

### Role Summary
UX/Design Leads define user experience and ensure usability and accessibility standards. They conduct user research, create design solutions, and validate design decisions to ensure products meet user needs and accessibility requirements.

### Responsibilities
- Conduct user research and define user personas and journeys
- Create wireframes, mockups, and design specifications
- Validate design decisions through usability testing
- Ensure design meets accessibility standards (WCAG, etc.)
- Support QA acceptance testing with design validation
- Collaborate on acceptance criteria to ensure usability is measurable
- Advocate for user needs throughout the project lifecycle

### Goals
- Deliver intuitive, accessible products that meet user needs
- Reduce friction in user experience through research-driven design
- Ensure accessibility standards are met for all users
- Support business objectives through user-centered design

### Typical Communication
- Product planning and feature definition sessions
- Design reviews and feedback sessions
- User research findings and usability testing results
- Acceptance criteria refinement (usability focus)
- Release announcements and user documentation

### Interactions with Other Roles
- **Product Managers**: Collaborates on user research, feature prioritization, and success metrics
- **Developers**: Provides detailed design specifications; works with developers to ensure pixel-perfect implementation
- **QA/Testing Lead**: Supports usability testing and design validation during QA phase
- **Stakeholder/Sponsor**: Communicates user impact and design decisions to leadership

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Cross-role interactions show how collaboration flows through OctoAcme projects across the full lifecycle.
