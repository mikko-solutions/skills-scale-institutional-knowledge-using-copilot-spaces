# OctoAcme Project Management Docs

OctoAcme uses a structured, iterative project management approach designed for cross-functional teams delivering product features, services, and integrations. Every project begins with a lightweight initiation phase to validate the business need, align stakeholders, and define measurable success criteria before any planning or development work begins. This gate-based approach ensures that only well-understood, prioritized work moves forward, reducing waste and keeping teams focused on customer value.

Once a project is approved, a dedicated planning phase translates the initiative into a prioritized backlog, release milestones, and a clear Definition of Done. Execution is managed through short iterations with daily standups, weekly delivery syncs, and end-of-sprint demos, all supported by a standard PR workflow, continuous integration, and layered quality practices. Risk and dependency tracking runs in parallel throughout, with a maintained Risk Register reviewed weekly and a defined escalation path from team level through to sponsor.

Releases follow a standardized checklist covering staging verification, automated pipelines, rollback plans, and stakeholder announcements. After each sprint, release, or significant milestone the team holds a retrospective to capture learnings and convert them into backlog action items, closing the loop on continuous improvement. Across all phases, clear role definitions for Project Managers, Product Managers, Developers, QA, and Stakeholders ensure accountability and reduce ambiguity.

These practices are underpinned by five core principles: customer-first delivery, iterative increments, clear ownership, data-informed decisions, and psychological safety. The documents in this folder elaborate each phase and cross-cutting practice in detail, providing templates, checklists, and examples to help teams apply the approach consistently.

---

## Documentation Index

| Document | Description |
|---|---|
| [Project Management Overview](octoacme-project-management-overview.md) | High-level introduction to OctoAcme's project management approach, principles, core roles, key artifacts, and lifecycle. |
| [Project Initiation](octoacme-project-initiation.md) | Steps to validate and authorize new work, align stakeholders, and produce the Project One-pager. |
| [Project Planning](octoacme-project-planning.md) | Turning an approved initiative into an actionable backlog, release plan, and milestone map. |
| [Execution & Tracking](octoacme-execution-and-tracking.md) | Day-to-day delivery guidance including team rhythm, PR workflow, quality practices, and blocker escalation. |
| [Risks & Communication](octoacme-risks-and-communication.md) | Risk Register format, risk lifecycle, stakeholder communication cadence, and escalation paths. |
| [Release & Deployment](octoacme-release-and-deployment.md) | Pre-release requirements, deployment checklist, rollback playbook, and release notes template. |
| [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) | Retrospective structure, running guidance, action item tracking, and continuous improvement culture. |
| [Roles & Personas](octoacme-roles-and-personas.md) | Detailed responsibilities, goals, and communication patterns for Developers, Product Managers, and Project Managers. |

---

## How the Docs Are Structured

The documentation is organized in four logical layers:

1. **Overview** — [`octoacme-project-management-overview.md`](octoacme-project-management-overview.md) provides the big picture: principles, core roles, key artifacts, and the end-to-end lifecycle. Start here.
2. **Lifecycle phases** — Four documents cover the sequential phases a project moves through: Initiation → Planning → Execution & Tracking → Release & Deployment.
3. **Cross-cutting practices** — Two documents address practices that apply throughout the entire lifecycle: Risk & Communication and Retrospective & Continuous Improvement.
4. **Roles & Personas** — One document defines the people involved, their responsibilities, and how they interact.

## How to Use These Docs

**Where to start:** New team members and stakeholders should read the [Project Management Overview](octoacme-project-management-overview.md) first, then the phase document most relevant to where the project currently stands.

**Keeping artifacts up to date:** Each phase document includes a checklist of minimum deliverables and a template (e.g., Project One-pager, Risk Register, Release Notes). Store completed artifacts in the project repository under `docs/` or `.copilot/` so they are discoverable and versioned alongside the code.

**Contributing updates:** To propose changes to any process document, open a pull request against the relevant file with a clear description of what changed and why. Reference the relevant issue number in the PR description. If a change affects multiple documents or introduces a new phase, update this README's index and structure sections accordingly.
