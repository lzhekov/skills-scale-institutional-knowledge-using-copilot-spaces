# Process improvements — checklists & templates

This doc contains small, copy-ready checklists and templates intended to be added to project workflows and documentation to close common process gaps.

## 1 — Role Assignment checklist (add to planning kickoff)
- [ ] Primary Project Manager assigned
- [ ] Product Lead assigned
- [ ] Development lead / tech owner assigned
- [ ] QA owner assigned
- [ ] Release/Platform contact assigned
- [ ] Security/AppSec contact assigned
- [ ] Data / Analytics contact assigned
- [ ] Support / SRE contact assigned
- [ ] UX/Research contact assigned
Notes: ensure contact names and backup on-call/responsible persons are recorded in the project README.

## 2 — PR & Merge checklist (add to PR template)
- [ ] Issue link and acceptance criteria present
- [ ] Tests added/updated and passing locally
- [ ] CI green
- [ ] Security scan/auto-checks run (or documented exception)
- [ ] Data instrumentation validated (if applicable)
- [ ] QA smoke tests documented
- [ ] Release/Platform owner informed (if release-affecting)

## 3 — Release readiness checklist (pre-deploy)
- [ ] Acceptance criteria met and signed off by Product
- [ ] QA smoke tests passed in staging
- [ ] Rollback plan documented
- [ ] Release Engineer/Platform confirmed pipeline readiness
- [ ] Support/SRE on-call notified and runbooks updated
- [ ] Telemetry and dashboards prepared for post-deploy validation
- [ ] Stakeholders notified of expected impact and communication plan

## 4 — Post-release checklist
- [ ] Post-deploy verifications completed
- [ ] Key metrics validated by Data Analyst
- [ ] Any incidents or anomalies logged and triaged
- [ ] Retrospective action items tracked as backlog issues

## 5 — Template: "Extended Personas" section to add to docs
- Title: Extended Personas
- Purpose: Clarify operational and cross-functional roles for improved ownership and interaction visibility.
- Content: brief responsibilities and interactions (TPM, Release Engineer, QA Lead, Security Reviewer, Data Analyst, Support Lead, UX Researcher).
- Suggested placement: docs/octoacme-roles-and-personas.md (append as a new section) and reference from project README.

## How to use these checklists
- Add the Role Assignment checklist to kickoff templates and planning sessions.
- Add PR & Merge checklist to the repository PR template.
- Add Release readiness checks to runbooks and release docs.
- Keep the Extended Personas section in docs as a living reference; update for project-specific deviations.
