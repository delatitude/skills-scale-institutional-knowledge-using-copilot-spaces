# OctoAcme — Role Collaboration Checklist

A lightweight reference teams can use during planning, execution, and release phases to confirm ownership, required attendees, decision paths, and handoff readiness.

> For full role definitions, see [octoacme-roles-and-personas.md](octoacme-roles-and-personas.md).

---

## RACI-style Ownership Summary

**R** = Responsible (does the work) | **A** = Accountable (decision authority) | **C** = Consulted | **I** = Informed

| Activity | PM | PdM | Tech Lead | Developers | QA | UX/Design | Security | Ops/Support | Delivery Coord | Stakeholders |
|---|---|---|---|---|---|---|---|---|---|---|
| Project initiation / charter | A | C | C | I | I | I | I | I | I | C |
| Backlog prioritization | C | A | C | C | I | C | C | I | I | I |
| Technical architecture | C | I | A | R | I | C | C | C | I | I |
| UX/Design specs | I | C | C | R | C | A | I | I | I | I |
| Sprint planning | A | C | C | R | R | C | I | I | C | I |
| Security review | C | I | C | R | C | I | A | I | I | I |
| Test plan / QA sign-off | C | I | C | R | A | C | C | I | I | I |
| Risk register updates | A | C | C | C | I | I | C | C | R | I |
| Release readiness decision | A | C | C | I | C | C | C | C | R | I |
| Deployment | C | I | A | R | C | I | C | R | I | I |
| Post-release monitoring | I | I | C | R | I | I | C | A | I | I |
| Stakeholder status update | R | C | I | I | I | I | I | I | C | A |

---

## Required Attendees by Lifecycle Phase

### Initiation
- **Required**: Project Manager, Product Manager, Stakeholders
- **Recommended**: Technical Lead, Delivery/Program Coordinator
- **As needed**: Security/Compliance Representative (if high regulatory risk)

### Planning
- **Required**: Project Manager, Product Manager, Technical Lead, Developers
- **Recommended**: QA/Testing, UX/Design Representative, Delivery/Program Coordinator
- **As needed**: Security/Compliance Representative, Operations/Support Representative

### Sprint / Iteration Review (Demo)
- **Required**: Project Manager, Product Manager, Developers, QA/Testing
- **Recommended**: UX/Design Representative, Stakeholders
- **As needed**: Technical Lead, Security/Compliance Representative

### Release Gate Review
- **Required**: Project Manager, Technical Lead, QA/Testing, Operations/Support Representative
- **Recommended**: Product Manager, Security/Compliance Representative
- **As needed**: Delivery/Program Coordinator, Stakeholders

### Retrospective
- **Required**: Project Manager, Developers, QA/Testing
- **Recommended**: Product Manager, Technical Lead, UX/Design Representative, Operations/Support Representative
- **As needed**: Delivery/Program Coordinator

---

## Decision & Escalation Paths

| Decision Type | First Owner | Escalation 1 | Escalation 2 |
|---|---|---|---|
| Scope change | Product Manager | Project Manager | Sponsor/Stakeholders |
| Technical approach | Technical Lead | Project Manager | Product Lead |
| Security risk acceptance | Security/Compliance Rep | Project Manager | Sponsor / Legal |
| Release go/no-go | Project Manager | Product Manager | Sponsor |
| Cross-team dependency blocker | Delivery/Program Coordinator | Project Manager | Sponsor |
| Operational incident | Operations/Support Rep | Technical Lead | Sponsor |
| Design/UX trade-off | UX/Design Representative | Product Manager | Stakeholders |

---

## Handoff Readiness Checks

Use these checklists at phase transitions to confirm that the handoff is complete before moving forward.

### ✅ Planning → Execution
- [ ] Backlog prioritized with acceptance criteria on all planned items
- [ ] UX/Design specs delivered for features starting in the sprint
- [ ] Technical architecture reviewed and approved by Technical Lead
- [ ] Security requirements identified and added to backlog items
- [ ] Test plan drafted by QA/Testing
- [ ] Operational readiness criteria defined with Operations/Support Representative
- [ ] Cross-team dependencies tracked and owners confirmed

### ✅ Execution → Release
- [ ] All acceptance criteria met and PRs merged
- [ ] QA/Testing sign-off complete
- [ ] UX/Design review completed (design fidelity and accessibility)
- [ ] Security/Compliance Representative sign-off on any security-relevant changes
- [ ] Operations/Support Representative confirms runbooks, alerting, and monitoring are ready
- [ ] Release notes drafted and reviewed
- [ ] Rollback plan documented
- [ ] Deployment window communicated to stakeholders

### ✅ Release → Close & Retrospective
- [ ] Post-deploy verifications passed
- [ ] Announcement sent to stakeholders and support
- [ ] Operations/Support Representative confirms production health metrics
- [ ] Any post-release issues captured in the backlog
- [ ] Retrospective scheduled with required attendees

---

## Communication Plan Quick Reference

| Audience | Owner | Cadence | Channel |
|---|---|---|---|
| Delivery team | Project Manager | Daily standup | Standup meeting |
| Stakeholders | Project Manager / Delivery Coord | Weekly or milestone | Status report / meeting |
| Engineering team | Technical Lead | As needed | Design docs, PR reviews |
| Support/Ops | Operations/Support Rep | Pre/post release | Runbook updates, alerts |
| Security team | Security/Compliance Rep | Sprint or as triggered | Security review, incident channel |
