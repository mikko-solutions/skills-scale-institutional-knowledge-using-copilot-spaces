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

## Risk Mitigation Plan Template

Use this template for each high or medium risk item in the risk register:

| Field | Details |
|---|---|
| Risk ID | e.g., RISK-001 |
| Description | Short description of the risk |
| Impact | High / Medium / Low |
| Likelihood | High / Medium / Low |
| Owner | Name or role responsible |
| Mitigation Actions | Specific steps to reduce likelihood or impact |
| Contingency Plan | What to do if the risk materializes |
| Target Resolution Date | Date by which mitigation should be in place |
| Status | Open / In Progress / Mitigated / Closed |

**Example Risk Mitigation Plan:**

| Field | Details |
|---|---|
| Risk ID | RISK-001 |
| Description | Third-party API dependency may have breaking changes in v2 upgrade |
| Impact | High |
| Likelihood | Medium |
| Owner | DevOps Engineer |
| Mitigation Actions | Pin current API version; monitor vendor changelog; write adapter layer |
| Contingency Plan | Roll back to previous version; notify Support Lead for customer communication |
| Target Resolution Date | End of Sprint 4 |
| Status | In Progress |

## Escalation Paths

### Standard Escalation Path

| Level | Trigger | Escalate To | Expected Response Time |
|---|---|---|---|
| Level 1 | Blocker affecting one team member | Team triage in daily standup | Same day |
| Level 2 | Blocker affecting team velocity or milestone | PM escalates to Product Lead and dependent teams | Within 24 hours |
| Level 3 | Business-impacting issue or unresolved L2 | PM and Product Lead escalate to Sponsor | Within 4 hours |

### Security Incident Escalation Path

| Step | Action | Owner |
|---|---|---|
| 1 | Identify and confirm the incident | Security Champion / Developer |
| 2 | Notify Security on-call and PM immediately | Security Champion |
| 3 | Contain impact (e.g., disable affected service) | DevOps Engineer |
| 4 | Assess scope and affected users | Security Champion + Support Lead |
| 5 | Communicate status to stakeholders | PM + Support Lead |
| 6 | Remediate and verify fix | Developers + Security Champion |
| 7 | Post-incident blameless retrospective | PM facilitates |

## Success Metrics Examples

Use these examples to define measurable outcomes for projects and milestones:

| Metric | Description | Target Example |
|---|---|---|
| Deployment Frequency | How often code is deployed to production | >= 1 deployment per sprint |
| Lead Time for Changes | Time from commit to production deployment | < 2 days average |
| Change Failure Rate | Percentage of deployments causing incidents | < 5% |
| Mean Time to Recovery (MTTR) | Average time to restore service after an incident | < 1 hour |
| Sprint Velocity | Story points completed per sprint | Within 10% of team average |
| Defect Escape Rate | Bugs found in production vs. total bugs | < 15% |
| Customer Satisfaction (CSAT) | Post-release satisfaction score | >= 4.0 / 5.0 |
| Requirement Coverage | Percentage of requirements with acceptance criteria | 100% |
