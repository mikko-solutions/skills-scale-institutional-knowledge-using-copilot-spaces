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

## UX Designer

### Role Summary
UX Designers ensure products are usable, accessible, and deliver an optimal user experience. They bridge the gap between user needs and technical implementation.

### Responsibilities
- Conduct user research, interviews, and usability testing
- Create wireframes, prototypes, and design systems
- Collaborate with Product Managers, Developers, and QA on feature design
- Provide input on usability acceptance criteria and interaction patterns
- Advocate for accessibility and inclusive design standards

### Goals
- Deliver intuitive, accessible, and delightful user experiences
- Reduce user friction and support adoption
- Align design decisions with product goals and user feedback

### Typical Communication
- Design reviews and prototype walkthroughs with Product and Engineering
- Usability test reports shared with PM and QA
- Design system documentation and annotated wireframes

### Interactions with Existing Roles
- **Product Managers**: Collaborate to translate product vision into user-centered designs
- **Developers**: Provide design specifications and review implementations for fidelity
- **QA Engineers**: Define usability acceptance criteria and participate in UAT

---

## DevOps Engineer

### Role Summary
DevOps Engineers build and maintain deployment infrastructure and automation, implementing CI/CD processes to ensure reliable, repeatable releases.

### Responsibilities
- Design and manage build, test, and deployment pipelines (CI/CD)
- Ensure stability, reproducibility, and security compliance of releases
- Monitor infrastructure health, performance, and availability
- Automate environment provisioning and configuration management
- Collaborate on incident response and on-call rotation

### Goals
- Maximize deployment frequency while minimizing failure rate
- Reduce mean time to recovery (MTTR) for incidents
- Ensure environments are consistent and infrastructure-as-code is maintained

### Typical Communication
- Infrastructure runbooks and deployment guides
- Incident retrospectives and post-mortems
- Coordination with Developers and Security Champion during releases

### Interactions with Existing Roles
- **Developers**: Support local dev environment parity and CI configuration
- **QA Engineers**: Maintain test infrastructure and staging environments
- **Security Champion**: Implement security controls in pipelines and environments

---

## Support Lead

### Role Summary
The Support Lead coordinates post-release support, monitors incidents, and ensures customer issues are tracked and resolved in a timely manner.

### Responsibilities
- Triage and prioritize incoming support requests and bug reports
- Communicate known issues and workarounds to customers and the team
- Provide a feedback loop to Product and Development on recurring pain points
- Escalate critical incidents to the appropriate team members
- Track support metrics and report on trends

### Goals
- Minimize customer-impacting issues and resolution time
- Surface actionable product feedback from support data
- Maintain a high level of customer satisfaction

### Typical Communication
- Support ticket summaries and escalation notifications
- Weekly support trend reports shared with PM and Engineering
- Incident communication and status updates during outages

### Interactions with Existing Roles
- **Product Managers**: Surface customer pain points to inform prioritization
- **Developers**: Escalate bugs and provide reproduction steps
- **DevOps Engineers**: Coordinate during infrastructure-related incidents

---

## Business Analyst

### Role Summary
Business Analysts bridge the gap between business requirements and technical delivery, ensuring that solutions address the right problems for stakeholders.

### Responsibilities
- Elicit and document requirements from business stakeholders
- Translate business needs into actionable specifications and testable outcomes
- Support backlog refinement with the PM and development team
- Assist with user acceptance testing (UAT) and sign-off processes
- Identify process gaps and improvement opportunities

### Goals
- Ensure delivered solutions meet documented business requirements
- Reduce rework caused by ambiguous or incomplete requirements
- Enable effective stakeholder communication and alignment

### Typical Communication
- Requirements documents, user stories, and process flow diagrams
- Meeting notes and decision logs from stakeholder sessions
- UAT test plans and acceptance sign-off reports

### Interactions with Existing Roles
- **Product Managers**: Collaborate on requirements gathering and backlog prioritization
- **Developers**: Clarify acceptance criteria and resolve requirement ambiguities
- **Project Managers**: Align on scope, dependencies, and delivery timelines

---

## Security Champion

### Role Summary
The Security Champion advocates for secure design and implementation across the team, helping identify and mitigate security risks throughout the development lifecycle.

### Responsibilities
- Review requirements and designs for potential security concerns
- Educate team members on security best practices and threat modeling
- Coordinate identification and mitigation of security vulnerabilities
- Liaise between the development team and the central Security Team
- Participate in security incident response when needed

### Goals
- Embed security awareness into every phase of development
- Reduce the risk of security vulnerabilities reaching production
- Maintain compliance with applicable security standards and policies

### Typical Communication
- Security review notes in PRs, design docs, and threat models
- Security bulletins and awareness updates to the team
- Incident reports and remediation tracking for identified vulnerabilities

### Interactions with Existing Roles
- **Developers**: Provide guidance on secure coding and review code for vulnerabilities
- **DevOps Engineers**: Ensure security controls are integrated into CI/CD pipelines
- **Project Managers**: Communicate security risks and timelines for remediation

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

