# OctoAcme Project Management Docs

Welcome to the OctoAcme project management process documentation. This folder contains the complete framework and guidance for running projects at OctoAcme—from initial concept through delivery and continuous improvement.

## Overview

OctoAcme follows a structured, customer-first project management approach designed to deliver iterative value while maintaining clear ownership, accountability, and psychological safety. Our framework emphasizes data-informed decisions, stakeholder alignment, and continuous learning from each project cycle.

### Core Principles
- **Customer-first**: Prioritize customer value and usability in all decisions
- **Iterative delivery**: Deliver small, testable increments regularly
- **Clear ownership**: Each project has named Project Manager and Product Lead roles
- **Data-informed**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback, learning, and blameless problem-solving

## Process Documentation

### Core Lifecycle

Follow these guides in sequence when managing a project:

1. **[Project Initiation](octoacme-project-initiation.md)** — Validate business need, align stakeholders, and authorize work
   - When to use: When a new project idea or feature proposal is ready to explore
   - Key deliverables: One-pager, stakeholder list, high-level timeline, initial risks

2. **[Project Planning](octoacme-project-planning.md)** — Break work into shippable increments and create actionable plans
   - Key activities: Kickoff, backlog creation, estimation, Definition of Done
   - Outputs: Prioritized backlog, release timeline, risk register

3. **[Execution & Tracking](octoacme-execution-and-tracking.md)** — Manage day-to-day execution and track progress toward milestones
   - Team rhythm: Daily standups, weekly delivery sync, sprint reviews
   - Key practices: GitHub Projects board, small PRs, automated CI, quality gates

4. **[Release & Deployment](octoacme-release-and-deployment.md)** — Standardize releases and deployments to reduce risk
   - Release types: Patch, Minor, Major
   - Pre-release requirements: Acceptance criteria met, CI passing, smoke tests prepared
   - Deployment checklist and rollback procedures

5. **[Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)** — Capture learnings and convert them into actionable improvements
   - Timing: After each sprint, release, or milestone
   - Structure: What went well, what could be improved, action items
   - Continuous improvement culture and measurement

### Supporting Resources

**[Project Management Overview](octoacme-project-management-overview.md)** — High-level introduction to OctoAcme approach
- Applies to all cross-functional projects
- Outlines core roles (PM, Product Manager, Developers, QA, Stakeholders)
- Describes key artifacts and lifecycle
- Best starting point for new team members

**[Risk Management & Communication](octoacme-risks-and-communication.md)** — Risk identification, escalation, and stakeholder communication
- Risk Register framework and lifecycle
- Three-level escalation paths
- Stakeholder communication templates and cadence
- Incident communication protocols

**[Roles & Personas](octoacme-roles-and-personas.md)** — Definition of core roles and responsibilities
- Project Manager: Coordinates delivery, schedules, risks, communications
- Product Manager: Defines outcomes, prioritizes backlog, measures success
- Developers: Implement features, collaborate on design and testability
- QA/Testing: Validates quality and acceptance criteria
- Stakeholders: Provide inputs and approvals

## Quality & Execution Standards

All projects at OctoAcme follow these quality practices:

- **Testing**: Unit tests for new logic, integration tests where applicable, end-to-end smoke tests for critical flows
- **Code review**: Small PRs (≤ 400 lines preferred), automated CI (tests, linting, security), at least one approval before merge
- **Metrics**: Track velocity, burndown, and success metrics identified in project charter
- **Communication**: Weekly syncs between PM and Product Manager, twice-weekly delivery standups, monthly stakeholder updates

## Quick Start

### For New Team Members
1. Start with [Project Management Overview](octoacme-project-management-overview.md) for a concise introduction
2. Review [Roles & Personas](octoacme-roles-and-personas.md) to understand team structure
3. Explore the specific process documents relevant to your role

### For Project Managers Starting a New Project
1. Read [Project Initiation](octoacme-project-initiation.md) to validate the business need
2. Follow [Project Planning](octoacme-project-planning.md) to create your project plan
3. Use [Risk Management & Communication](octoacme-risks-and-communication.md) to set up governance
4. Reference [Execution & Tracking](octoacme-execution-and-tracking.md) for day-to-day guidance

### For Developers Joining an Active Project
1. Review [Execution & Tracking](octoacme-execution-and-tracking.md) for sprint and PR workflows
2. Check your project's Definition of Done and acceptance criteria
3. Participate in daily standups and sprint planning
4. Reference specific process docs as needed for context

## Contributing to Process Documentation

We continuously improve our processes based on team feedback and learnings from each project. If you'd like to:
- **Suggest updates** to an existing process document
- **Propose new guidance** for emerging challenges
- **Clarify documentation** that is unclear

Please open an issue using the [Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) template.

## Key Artifacts by Phase

| Phase | Key Artifacts |
|-------|--------------|
| Initiation | Project One-pager, Stakeholder list, Approval decision |
| Planning | Project Charter, Prioritized backlog, Release plan, Definition of Done |
| Execution | Sprint backlog, Risk register, Status reports, Burndown charts |
| Release | Release notes, Deployment checklist, Smoke test results, Rollback plan |
| Close | Retrospective notes, Action items, Lessons learned |

---

**Last updated**: 2026  
**Questions?** Reach out to your Project Manager or Product Lead for clarification on any process.
