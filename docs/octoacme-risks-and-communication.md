# OctoAcme — Risk Management & Communication

## Purpose
Explain how to identify, manage, and communicate risks and dependencies.

## Risk Register
Maintain a simple table with:
- ID
- Description
- Impact (High/Med/Low)
- Likelihood (High/Med/Low)
- Owner
- Mitigation plan
- Status

## Risk Lifecycle
- Identify: during planning and ongoing execution
- Assess: estimate impact and likelihood
- Mitigate: reduced via actions, contingency plans
- Monitor: review at weekly syncs and update status

## Stakeholder Communication
- Identify stakeholder groups and communication needs (e.g., engineering, sales, support)
- Provide regular updates (weekly or milestone-based)
- Use a single source of truth (project README or release doc) for status

## Communication Templates
Weekly Status Template:
- Progress this week:
- Next steps:
- Risks & blockers:
- Ask / decisions needed:

Incident Communication
- Triage summary
- Actions being taken
- Expected timeline
- Post-incident blameless retrospective scheduled

## Escalation Paths
- Team-level -> PM -> Product Lead -> Sponsor
- For security incidents, follow the security incident runbook and notify Security/Compliance Representative and on-call
- For operational/production issues, notify Operations/Support Representative and follow the incident runbook
- For cross-team dependency blockers, escalate through Delivery/Program Coordinator

## Risk Ownership by Role
| Risk Type | Primary Owner | Escalation |
|---|---|---|
| Schedule / resource | Project Manager | Sponsor |
| Technical / architecture | Technical Lead | Product Lead |
| Security / compliance | Security/Compliance Representative | Sponsor / Legal |
| Operational / reliability | Operations/Support Representative | Technical Lead |
| UX / usability | UX/Design Representative | Product Manager |
| Cross-team dependency | Delivery/Program Coordinator | Project Manager |
