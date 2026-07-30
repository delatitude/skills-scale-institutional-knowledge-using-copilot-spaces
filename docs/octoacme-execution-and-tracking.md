# OctoAcme — Execution & Tracking

## Purpose
Guidance for managing day-to-day execution and tracking progress toward project milestones.

## Team Rhythm
- Daily standups (15 min) — focus on progress, blockers, dependencies
- Weekly delivery sync — show progress, updates, and flagged risks
- Demo/Review at the end of each sprint or milestone

## Workflows
- Use the project board (e.g., GitHub Projects) with columns: Backlog, Ready, In Progress, In Review, QA, Done
- Pull Request workflow:
  - Small PRs (<= 400 lines when possible)
  - Include issue link and acceptance criteria in PR description
  - Run automated tests and linting in CI before requesting review
  - Require at least one approval before merging (or team-defined policy)

## Quality & Testing
- Unit tests for new logic
- Integration tests where applicable
- End-to-end smoke tests for critical flows before release
- Security scanning in CI
- Manual QA for feature acceptance when needed

## Reporting & Metrics
- Track velocity and burndown
- Monitor success metrics identified in the Project One-pager
- Use dashboards for key signals (errors, latency, usage)

## Blocker Escalation
- Level 1: Team-level triage in daily standup
- Level 2: PM escalates to Product Lead and dependent teams
- Level 3: Sponsor-level escalation for business-impacting issues

## Execution Checklist
- [ ] Branching and PR conventions documented in repo
- [ ] CI configured for tests and lint
- [ ] Regular demos scheduled
- [ ] Risk register updated weekly
- [ ] Security scanning configured in CI (Security/Compliance sign-off)
- [ ] Observability and alerting in place (Operations/Support sign-off)
- [ ] UX/Design review completed before feature acceptance

## Cross-functional Collaboration at Execution
- **Technical Lead** leads code and design reviews; communicates technical risks to PM.
- **UX/Design Representative** reviews implementations for fidelity and accessibility before QA sign-off.
- **Security/Compliance Representative** reviews PRs involving sensitive data, auth, or infrastructure changes.
- **Operations/Support Representative** is consulted on observability instrumentation and runbook preparation.
- **Delivery/Program Coordinator** tracks cross-team dependencies and escalates blockers to the PM.

> See [octoacme-role-collaboration-checklist.md](octoacme-role-collaboration-checklist.md) for execution-phase ownership and handoff guidance.
