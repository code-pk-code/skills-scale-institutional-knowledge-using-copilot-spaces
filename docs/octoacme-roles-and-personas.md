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

---

## Additional Personas (proposed)

These personas fill gaps around release coordination, security/compliance, platform ownership, analytics, and UX. Add each as a subsection in this document; the entries below follow the same formatting as the existing roles.

### Release Manager

#### Role Summary
Owns release planning and execution to ensure safe, predictable releases.

#### Responsibilities
- Create and run the release checklist (pre-release, deploy, and post-release steps)
- Schedule deployment windows and communicate timing to stakeholders
- Coordinate rollback/mitigation plans and ensure they are tested
- Ensure release notes and stakeholder communications are prepared and distributed

#### Goals
- Reduce release-related incidents and rollback frequency
- Ensure predictable, observable deployments

#### Typical Communication
- Works with PM for scheduling, with Developers and QA for release readiness, and with SRE for deployment support.

#### Interactions / When to involve
- Involve at least one sprint before a milestone release for planning.
- Escalate to Project Manager or Sponsor for release-impacting decisions.

---

### Delivery Lead (Engineering Lead)

#### Role Summary
Coordinates day-to-day technical delivery and removes implementation-level blockers.

#### Responsibilities
- Lead technical planning and sprint execution
- Resolve cross-team engineering blockers
- Ensure technical debt is tracked and prioritized
- Mentor engineers and support design reviews

#### Goals
- Maintain steady delivery velocity and code quality
- Reduce context switching for engineers by coordinating technical priorities

#### Typical Communication
- Regular syncs with PM and PdM; communicates technical constraints and impacts.

#### Interactions / When to involve
- Involve during planning, design reviews, and when cross-team technical coordination is needed.

---

### Program Architect (Technical Architect)

#### Role Summary
Provides cross-project technical guidance and owns architecture patterns.

#### Responsibilities
- Define integration patterns and high-level architecture decisions
- Review designs for consistency and scalability
- Provide guidance on cross-project technical dependencies

#### Goals
- Ensure architectural consistency and reduce duplicated effort
- Balance scalability, security, and delivery speed

#### Typical Communication
- Works with Delivery Leads, SRE, and Developers to align on long-term technical choices.

#### Interactions / When to involve
- Involve early for designs that affect multiple systems or external integrations.

---

### Security Liaison

#### Role Summary
Coordinates security reviews and ensures security best practices are integrated into the lifecycle.

#### Responsibilities
- Coordinate threat modeling and security reviews
- Ensure static/dynamic security scans and compliance checks run in CI/CD
- Advise teams on security findings and mitigations

#### Goals
- Reduce security vulnerabilities reaching production
- Ensure compliance requirements are considered early

#### Typical Communication
- Engages with Developers during design; notifies PM/PdM when security trade-offs affect scope.

#### Interactions / When to involve
- Involve during design and before major architecture decisions or public launches.

---

### Site Reliability Engineer (SRE) / Platform Owner

#### Role Summary
Maintains production stability, monitoring, and runbooks.

#### Responsibilities
- Own monitoring, alerting, and incident response playbooks
- Run post-deploy verifications and support root-cause analysis
- Maintain platform automation and deployment pipelines

#### Goals
- Improve system availability and mean time to recovery (MTTR)
- Ensure robust observability for production issues

#### Typical Communication
- Works with Release Manager on deploys, Developers for runbook updates, and PM for incident communications.

#### Interactions / When to involve
- Involve during releases, for on-call rotation handoffs, and when performance/availability is at risk.

---

### Data Analyst / Metrics Owner

#### Role Summary
Owns measurement plans and delivers data needed to evaluate outcomes.

#### Responsibilities
- Define success metrics and measurement plans for features
- Instrument telemetry and build dashboards
- Produce post-release analysis and recommendations

#### Goals
- Ensure decisions are data-informed and measurable
- Provide timely insight into feature impact

#### Typical Communication
- Partners with PdM to define metrics and with Developers to ensure telemetry is implemented.

#### Interactions / When to involve
- Involve during planning to agree on measurement and tracking requirements.

---

### UX Researcher / Designer

#### Role Summary
Leads user research and ensures product usability and accessibility.

#### Responsibilities
- Conduct user research and usability testing
- Provide UX designs and acceptance criteria
- Ensure accessibility and design consistency

#### Goals
- Validate user value and reduce rework from design issues

#### Typical Communication
- Works closely with PdM and Developers to iterate on designs and acceptance criteria.

#### Interactions / When to involve
- Involve early in feature conception and before final acceptance testing.

---

### Compliance / Privacy Lead

#### Role Summary
Ensures regulatory and privacy requirements are identified and met.

#### Responsibilities
- Track regulatory requirements and maintain audit documentation
- Coordinate privacy reviews and data-handling assessments
- Provide guidance on data retention, consent, and third-party data sharing

#### Goals
- Minimize legal and regulatory exposure
- Ensure compliant documentation is in place for audits

#### Typical Communication
- Coordinates with Security Liaison, PM, and Legal/Compliance teams.

#### Interactions / When to involve
- Involve early for projects with regulatory scope (e.g., PII, GDPR, HIPAA).

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.