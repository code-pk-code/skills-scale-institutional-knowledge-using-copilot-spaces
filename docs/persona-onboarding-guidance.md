# Persona Onboarding & When to Involve Roles

Purpose: Practical guidance on when to involve specific personas and how to hand off responsibilities.

Guidance summary
- Involve Product Manager (PdM) when defining goals, metrics, and prioritization.
- Involve Project Manager (PM) when scheduling, triaging risks, or coordinating cross-team dependencies.
- Involve Delivery Lead and Program Architect for technical designs, integrations, and implementation planning.
- Involve Release Manager and SRE for any production deployment planning and verification.
- Involve Security Liaison and Compliance early if the project touches sensitive data, third-party integrations, or regulatory scope.
- Involve Data Analyst before the implementation begins to lock down telemetry and tracking requirements.
- Involve UX Research/Design during discovery and prior to final acceptance criteria.

Short "When to involve" cheat-sheet (one-liners)
- Release Manager: Prior to any production release or major change to deployment cadence.
- Delivery Lead: During sprint planning and for cross-team technical coordination.
- Program Architect: For cross-system designs or performance/scalability decisions.
- Security Liaison: During design and before any data-sensitivity decisions are finalized.
- SRE/Platform: For deployments, changes to infrastructure, or performance improvements.
- Data Analyst: During planning to define success metrics and instrumentation.
- UX Researcher: During discovery, prototyping, and validation stages.
- Compliance Lead: For projects with regulatory or data privacy requirements.

How to include these in repository
- Add these documents under docs/ and reference them in the main project README and project one-pager.
- Link personas in PR templates and checklist items (e.g., a release PR should include "Release Manager: @team-member" in the PR description when applicable).