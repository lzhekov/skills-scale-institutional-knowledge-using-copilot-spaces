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

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

---

## Extended Personas

Note: these additional personas are included to reduce handoff ambiguity, improve accountability for cross-cutting concerns (release, security, data, operations), and ensure clear interactions with the core roles above. Add these as subsections when they apply to a project.

### Technical Program Manager (TPM)
Responsibilities
- Own cross-team sequencing for multi-team work, integration plans, and release dependency tracking.
- Maintain an integration/technical milestones timeline and coordinate cross-team risk mitigations.
- Ensure end-to-end visibility of critical paths and unblock dependent teams.

Interactions
- Works with Project Manager/PM to align milestones and schedules.
- Coordinates with Developers and QA to resolve technical dependencies.
- Communicates status and risks to Product and Stakeholders.

### Release Engineer / Platform Engineer
Responsibilities
- Own deployment pipelines, automation, release configuration, and rollback strategies.
- Maintain CI/CD reliability, release tagging, and release verification scripts.
- Execute and/or validate production deployments and coordinate deployment windows.

Interactions
- Works with Developers and QA to ensure release artifacts meet deployment requirements.
- Coordinates with PM/Project Manager for release windows and communications.
- Collaborates with Support/SRE for operational readiness and rollbacks.

### QA Lead / Test Architect
Responsibilities
- Define test strategies (unit, integration, E2E, regression) and guardrails for releases.
- Own the test plan for major features and maintain regression/e2e suites.
- Coordinate test environments and release smoke tests.

Interactions
- Works with Developers for testability and automation.
- Communicates acceptance criteria and test readiness to PM and Release Engineer.
- Coordinates with Product for acceptance and release bake verification.

### Security Reviewer / AppSec Liaison
Responsibilities
- Review architecture and PRs for security vulnerabilities and compliance issues.
- Maintain security checklists and coordinate required scans (SAST/DAST, dependency checks).
- Track remediation priorities and follow up on security findings.

Interactions
- Works with Developers and CI owners to integrate security scanning into pipelines.
- Advises PM/Product on risk and required mitigation timelines.
- Escalates to security on-call or leadership for high-impact findings.

### Data Analyst / Insights Lead
Responsibilities
- Define success metrics and acceptance criteria related to telemetry and product impact.
- Validate instrumentation and provide pre/post-release analysis.
- Produce dashboards and post-release insight reports.

Interactions
- Collaborates with Product to define measurable outcomes.
- Works with Engineers to ensure telemetry is implemented correctly.
- Shares findings with Stakeholders to inform future prioritization.

### Support Lead / SRE Liaison
Responsibilities
- Own on-call handoffs, incident intake, and operational runbooks for the feature.
- Define escalation patterns and conduct readiness checks before releases.
- Track operational metrics and coordinate post-incident follow-ups.

Interactions
- Works with Developers and Release Engineer to prepare operational playbooks.
- Communicates support readiness and on-call expectations to PM and Stakeholders.
- Leads incident response and post-incident retrospectives when necessary.

### UX Researcher / Designer Liaison
Responsibilities
- Ensure user research and design validation are integrated into planning and acceptance criteria.
- Provide design review and research summaries to inform implementation decisions.
- Help validate feature UX during planning, QA, and post-release evaluation.

Interactions
- Works with PdM to define user needs and success criteria.
- Collaborates with Developers to clarify UI/UX expectations and acceptance tests.
- Shares research findings with Stakeholders and Product.

---
