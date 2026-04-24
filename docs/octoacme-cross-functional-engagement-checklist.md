# OctoAcme — Cross-Functional Engagement Checklist

This checklist ensures the right roles are engaged at each phase of the project lifecycle. Use it alongside the [Roles & Personas](./octoacme-roles-and-personas.md) doc to assign owners and prevent handoff gaps.

---

## RACI Key

| Symbol | Meaning |
|--------|---------|
| **R** | Responsible — does the work |
| **A** | Accountable — final decision/sign-off |
| **C** | Consulted — provides input before decisions |
| **I** | Informed — kept up to date |

---

## Lifecycle Phase Matrix

| Activity | Project Manager | Product Manager | Developers | UX Designer | Data Analyst | Security Lead | Customer Success | Technical Writer |
|---|---|---|---|---|---|---|---|---|
| Define problem statement & success metrics | C | **A/R** | C | C | **C** | I | **C** | I |
| Stakeholder identification | **R** | A | I | I | I | C | C | I |
| Risk Register creation & updates | **A/R** | C | C | I | C | **C** | I | I |
| Backlog prioritization | C | **A/R** | C | C | **C** | C | **C** | I |
| UX research & design handoff | I | C | **C** | **A/R** | I | I | **C** | I |
| Security requirements & threat modeling | C | C | **C** | I | I | **A/R** | I | I |
| Sprint / iteration planning | **A/R** | C | **R** | C | I | C | I | I |
| Implementation & code review | I | I | **A/R** | C | I | **C** | I | I |
| Analytics instrumentation | I | C | **R** | I | **A** | I | I | I |
| QA / acceptance testing | C | C | **R** | **C** | I | C | C | I |
| Release notes authoring | I | **C** | C | I | I | I | **C** | **A/R** |
| Security scan review & sign-off | I | I | C | I | I | **A/R** | I | I |
| Deployment & rollback coordination | **A/R** | I | **R** | I | I | **C** | I | I |
| Customer-facing release communication | **C** | **A** | I | I | I | I | **R** | **C** |
| Post-release monitoring & metrics review | C | **A** | C | I | **R** | C | **C** | I |
| Incident response coordination | **A** | I | **R** | I | I | **R** | **C** | I |
| Security incident communications | **C** | I | I | I | I | **A/R** | **C** | I |
| Retrospective facilitation | **A/R** | C | C | C | C | C | C | C |
| Process doc & retrospective updates | C | C | C | I | I | C | I | **R** |

---

## Handoff Checklist

Use this checklist at key project transitions to confirm that all relevant stakeholders have been engaged.

### Initiation → Planning
- [ ] Problem statement and success metrics reviewed with Data Analyst
- [ ] UX Designer engaged for discovery and research (if user-facing)
- [ ] Security Lead consulted on security requirements
- [ ] Customer Success asked for known user pain points or feature requests
- [ ] Technical Writer notified of upcoming documentation scope

### Planning → Execution
- [ ] UX design specs and prototypes reviewed and accepted by Developers
- [ ] Security requirements captured in backlog items with acceptance criteria
- [ ] Analytics instrumentation plan agreed between Data Analyst and Developers
- [ ] Documentation tasks added to backlog (owner: Technical Writer)
- [ ] Customer Success aligned on expected release timeline and customer impact

### Execution → Release
- [ ] Security scans passing; Security Lead has reviewed critical findings
- [ ] UX Designer has reviewed implemented UI against design specs
- [ ] Release notes drafted and reviewed by Technical Writer, Product Manager, and Customer Success
- [ ] Data Analyst has validated analytics instrumentation in staging
- [ ] Customer Success has prepared support materials and FAQs

### Release → Close & Retrospective
- [ ] Customer-facing release announcement sent (owner: Customer Success, approved by Product Manager)
- [ ] Post-release metrics reviewed with Data Analyst within 1 week
- [ ] Security Lead confirms no open vulnerabilities from the release
- [ ] Technical Writer has published final user-facing documentation
- [ ] Retrospective scheduled and retrospective notes shared with all personas

---

## Security Incident Escalation

When a security incident is identified:

1. **Security Lead** is the primary owner — leads triage, investigation, and remediation.
2. **Project Manager** coordinates cross-team communication and timeline tracking.
3. **Developers** implement fixes under Security Lead direction.
4. **Customer Success** prepares customer-facing communications (reviewed by Security Lead).
5. **Product Manager** and **Stakeholders** are kept informed per the cadence below.

| Severity | Initial notification | Status updates | Post-incident review |
|---|---|---|---|
| Critical | Immediate (< 1 hour) | Every 2 hours until resolved | Within 48 hours |
| High | Within 4 hours | Daily | Within 1 week |
| Medium/Low | Within 1 business day | Weekly | Next retrospective |

---

## References
- [Roles & Personas](./octoacme-roles-and-personas.md)
- [Risk Management & Communication](./octoacme-risks-and-communication.md)
- [Release & Deployment Guide](./octoacme-release-and-deployment.md)
- [Execution & Tracking](./octoacme-execution-and-tracking.md)
