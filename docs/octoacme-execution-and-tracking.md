# OctoAcme — Execution & Tracking

## Purpose
Guidance for managing day-to-day execution and tracking progress toward project milestones.

## Commitment Process

Before a sprint or iteration begins, the team follows a structured commitment process to ensure shared understanding and realistic planning:

1. **Backlog Refinement** (1–2 days before sprint start): PM, BA, and tech leads review and size upcoming stories; acceptance criteria are confirmed with developers
2. **Sprint Planning** (start of sprint): Team selects work they can commit to based on velocity and capacity; dependencies and risks are flagged
3. **Commitment Agreement**: Each team member verbally or explicitly confirms their sprint items; no item is in-flight without an owner
4. **Definition of Done Review**: Confirm the DoD checklist is understood and agreed upon before work begins

### Definition of Done (DoD) Checklist
- [ ] Code complete and reviewed (PR approved)
- [ ] Unit and integration tests written and passing
- [ ] Security scan run with no new critical/high findings
- [ ] Feature tested by QA against acceptance criteria
- [ ] Documentation updated (README, API docs, runbooks as applicable)
- [ ] Deployment to staging environment successful
- [ ] Product Manager sign-off received

## Time-Box Sprint Structure

Sprints are time-boxed to create a predictable cadence for delivery and feedback. Recommended sprint length: **2 weeks**.

| Phase | Duration | Activities |
|---|---|---|
| Sprint Planning | Day 1 (2–3 hrs) | Review backlog, confirm commitment, assign work |
| Execution | Days 2–8 | Daily standups, development, PR reviews, QA |
| Sprint Review / Demo | Day 9 (1 hr) | Demo completed work to stakeholders, gather feedback |
| Retrospective | Day 10 (1 hr) | Inspect process, identify improvements, update action items |

### Iterative Feedback Cycle
- Stakeholder demos at the end of each sprint enable early course corrections
- Feedback captured during the review feeds directly into the next sprint's backlog refinement
- Retrospective action items are tracked as team commitments with owners and due dates
- Mid-sprint check-ins (Wednesday sync) surface blockers before they impact the sprint goal

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
