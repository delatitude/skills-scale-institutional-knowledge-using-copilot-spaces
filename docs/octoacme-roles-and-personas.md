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

## QA / Testing

### Role Summary
QA/Testing professionals validate that delivered features meet acceptance criteria, quality standards, and user expectations before release.

### Responsibilities
- Review acceptance criteria and define test plans
- Execute manual and automated tests (functional, regression, smoke)
- Report defects and track resolution
- Sign off on release readiness from a quality perspective
- Champion testability in design and planning discussions

### Goals
- Prevent regressions and quality escapes from reaching production
- Reduce defect cycle time through early and continuous testing
- Maintain a clear signal of release readiness

### Typical Interactions
- **Project Manager**: coordinates QA scheduling and release gate sign-off
- **Product Manager**: clarifies acceptance criteria and edge cases
- **Developers**: pairs on test coverage and defect resolution
- **Stakeholders**: reports quality status at demos and release reviews

---

## Stakeholders

### Role Summary
Stakeholders are individuals or groups with a vested interest in project outcomes. They provide direction, funding, approvals, and feedback throughout the project lifecycle.

### Responsibilities
- Provide business context and priority inputs during initiation and planning
- Review and approve key artifacts (one-pager, roadmap, release plan)
- Participate in demos and milestone reviews
- Escalation point for unresolved decisions or conflicts

### Goals
- Ensure projects deliver measurable business value
- Maintain visibility into status, risks, and decisions
- Enable teams with timely approvals and inputs

### Typical Interactions
- **Project Manager**: receives status updates and escalation paths
- **Product Manager**: aligns on roadmap priorities and trade-offs
- **Delivery/Program Coordinator**: coordinates milestone reviews and communications
- **Developers/QA**: attends demos and release reviews

---

## Delivery / Program Coordinator

### Role Summary
The Delivery/Program Coordinator manages logistics, communications, and cross-team dependencies to keep projects moving. This role often operates above individual project scope to coordinate programs or portfolios.

### Core Responsibilities
- Track delivery milestones and highlight cross-team dependencies
- Facilitate coordination meetings and escalate blockers
- Maintain program-level status dashboards and reporting
- Coordinate onboarding of new team members and handoffs between phases
- Drive consistency in how project artifacts are maintained

### Goals / Success Indicators
- No delivery milestone slips due to untracked dependencies
- Stakeholders have consistent, timely visibility into program health
- Handoffs between teams and lifecycle phases are smooth and documented

### Typical Interactions
- **Project Manager**: aligns on project-level plans and feeds into program view
- **Product Manager**: ensures roadmap milestones are reflected in program schedule
- **Technical Lead**: surfaces technical blockers that affect cross-team timelines
- **Stakeholders**: provides program status and coordinates review cadences
- **Developers/QA**: tracks delivery readiness and removes coordination friction

---

## Technical Lead / Engineering Lead

### Role Summary
The Technical Lead provides technical direction and oversight for the engineering team. They bridge product intent and engineering implementation, own architectural decisions, and ensure the team can deliver sustainably.

### Core Responsibilities
- Define and maintain technical architecture and standards
- Review and approve significant design and implementation decisions
- Identify and communicate technical risks early
- Mentor developers and ensure code quality through review practices
- Coordinate technical dependencies with other engineering teams

### Goals / Success Indicators
- Technical decisions are consistent, documented, and understood by the team
- Technical debt and risk are managed proactively
- Engineering capacity and velocity are predictable

### Typical Interactions
- **Project Manager**: communicates technical risks, capacity constraints, and schedule impacts
- **Product Manager**: translates product requirements into technical trade-offs
- **Delivery/Program Coordinator**: surfaces cross-team technical dependencies
- **Developers**: leads design reviews, code reviews, and technical direction
- **Security/Compliance Representative**: ensures security requirements are addressed in design

---

## UX / Design Representative

### Role Summary
The UX/Design Representative ensures that user experience and design quality are considered throughout the project lifecycle, from early problem framing through to release.

### Core Responsibilities
- Define and maintain UX standards, patterns, and design systems
- Conduct and synthesize user research to inform product decisions
- Deliver wireframes, prototypes, and design specifications
- Review implementations for design fidelity and accessibility
- Advocate for user needs in planning and prioritization discussions

### Goals / Success Indicators
- Features are usable, accessible, and consistent with design standards
- Design feedback is incorporated before development begins
- User research insights are reflected in product decisions

### Typical Interactions
- **Product Manager**: collaborates on problem framing, user stories, and acceptance criteria
- **Technical Lead**: aligns on technical constraints that affect design
- **Developers**: provides specifications and reviews implementations
- **QA/Testing**: includes accessibility and UX checks in test plans
- **Stakeholders**: presents research findings and design proposals

---

## Security / Compliance Representative

### Role Summary
The Security/Compliance Representative ensures that the project meets security, privacy, and regulatory requirements throughout the lifecycle, not just at release.

### Core Responsibilities
- Review designs, architectures, and code changes for security risks
- Define and maintain security requirements and compliance controls
- Conduct or coordinate security assessments and threat models
- Ensure compliance with relevant regulations (e.g., data privacy, audit requirements)
- Own the security incident escalation path for the project

### Goals / Success Indicators
- Security and compliance requirements are identified and addressed early
- No unmitigated high-severity security findings at release
- The team understands and follows security standards

### Typical Interactions
- **Technical Lead**: reviews architecture for security risks and controls
- **Developers**: provides guidance on secure coding and reviews sensitive changes
- **Project Manager**: communicates compliance gates and security timelines
- **QA/Testing**: ensures security scanning and penetration testing are included in test plans
- **Stakeholders**: reports on compliance posture and risk acceptance decisions

---

## Operations / Support Representative

### Role Summary
The Operations/Support Representative ensures that delivered software can be reliably operated and supported in production. They bring an operational lens to planning and release decisions.

### Core Responsibilities
- Define observability, alerting, and on-call requirements
- Review release plans for operational readiness
- Manage and document incident response runbooks
- Represent support/operational concerns in planning and retrospectives
- Coordinate post-release monitoring and issue triage

### Goals / Success Indicators
- New features are deployed with documented runbooks and alerting in place
- Mean time to detect (MTTD) and mean time to resolve (MTTR) are within targets
- Support teams are prepared for new feature impacts before release

### Typical Interactions
- **Technical Lead**: aligns on observability instrumentation and infrastructure changes
- **Project Manager**: confirms operational readiness as part of release gate criteria
- **Developers**: reviews runbooks and on-call documentation
- **Security/Compliance Representative**: coordinates on incident response and security operations
- **Stakeholders**: communicates operational health and incident impacts

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- See [octoacme-role-collaboration-checklist.md](octoacme-role-collaboration-checklist.md) for a practical ownership and handoff template that references these roles.

