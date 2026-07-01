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

## Additional Personas (proposed additions)

Below are additional roles that clarify ownership for cross-cutting activities (releases, security, reliability, design, analytics, and customer outcomes). Add each as a subsection in the document; each entry includes Role Summary, Responsibilities, and Interactions with existing roles.

### Technical Program Manager (TPM)
- Role Summary: Coordinates complex, cross-team technical programs. Focuses on program-level planning, cross-team dependency tracking, and risk mitigation across engineering organizations.
- Responsibilities:
  - Own program-level timelines and milestones for multi-team technical initiatives.
  - Track and resolve cross-team dependencies and integration risks.
  - Run program-level risk reviews and coordinate mitigations.
  - Facilitate technical rollout planning with engineering leads, SRE, and release management.
- Interactions:
  - Works with Product Managers on scope alignment and success criteria.
  - Partners with Project Managers on scheduling and tracking.
  - Coordinates with Engineering Leads on technical approaches and integration.
  - Communicates status to Stakeholders.

### Release Manager
- Role Summary: Manages the release calendar and readiness for production deploys, ensuring releases meet quality, security, and operational requirements.
- Responsibilities:
  - Maintain release schedule and cutover plans.
  - Run release readiness checks (CI, QA, security scans, monitoring).
  - Own rollback/mitigation plans and coordinate post-release verification.
  - Coordinate release communications with Customer Support and Stakeholders.
- Interactions:
  - Works with Developers and QA to confirm readiness.
  - Partners with SRE/Operations for deployment steps and monitoring.
  - Coordinates with PM and Customer Support for rollout messaging.

### Engineering Lead / Tech Lead
- Role Summary: Owns the technical design and architectural decisions for features and systems; mentors the engineering team.
- Responsibilities:
  - Drive architecture and design decisions for assigned areas.
  - Review and approve major technical designs and trade-offs.
  - Support team-level planning and estimation.
  - Coach developers and ensure code quality and maintainability.
- Interactions:
  - Collaborates with Product Managers on technical feasibility and scope.
  - Works with QA to ensure testability and validation.
  - Partners with TPM/Project Manager to communicate estimates and dependencies.

### UX Designer / Researcher
- Role Summary: Drives user research, interaction design, and validates UX acceptance criteria to ensure a usable and delightful product.
- Responsibilities:
  - Conduct user research and usability testing.
  - Produce wireframes, mocks, and design specifications.
  - Define design-related acceptance criteria and success signals.
  - Validate implemented designs and provide feedback to development.
- Interactions:
  - Partners with Product Managers on requirements and success metrics.
  - Works with Developers during implementation to ensure design fidelity.
  - Shares findings with stakeholders to influence prioritization.

### Security & Privacy Lead
- Role Summary: Ensures the product meets security and privacy requirements and that risks are surfaced and mitigated early.
- Responsibilities:
  - Conduct security and privacy reviews for designs and releases.
  - Define security acceptance criteria and required checks.
  - Coordinate vulnerability assessments and compliance requirements.
  - Advise on secure implementation patterns and threat modeling.
- Interactions:
  - Works with Product Managers and Engineering Leads during planning.
  - Partners with Release Manager to confirm security gates are satisfied before launch.
  - Collaborates with SRE on incident response plans for security issues.

### Site Reliability Engineer (SRE) / Operations
- Role Summary: Owns production reliability, monitoring, on-call operations, and incident response.
- Responsibilities:
  - Define and maintain runbooks, monitoring, and alerting for services.
  - Support incident response and lead post-incident remediation.
  - Advise on operational impact of design and releases.
  - Work on scalability and reliability improvements.
- Interactions:
  - Collaborates with Developers to implement observability and resilient designs.
  - Works with Release Manager on deployment strategy and post-deploy checks.
  - Communicates incidents and mitigations to Project Managers and Stakeholders.

### Customer Success / Support Representative
- Role Summary: Provides customer impact context, helps validate supportability, and coordinates communications for releases and incidents.
- Responsibilities:
  - Triage customer issues and provide feedback to engineering and PM teams.
  - Validate release communication and runbooks for supportability.
  - Coordinate direct customer communications in partnership with PM and Release Manager.
- Interactions:
  - Works with QA to reproduce customer issues and validate fixes.
  - Partners with Product Manager for customer-facing messaging and prioritization.

### Data Analyst
- Role Summary: Defines and validates success metrics, builds dashboards, and performs post-release analysis to measure impact.
- Responsibilities:
  - Define key metrics and instrumentation needs for features.
  - Create dashboards and run regular analyses to track adoption and impact.
  - Validate data quality and partner with Developers to ensure telemetry is implemented.
- Interactions:
  - Partners with Product Managers to translate goals into measurable metrics.
  - Works with Developers and SRE to ensure telemetry and data pipelines are functioning.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- When adding a new persona, include a brief Role Summary, Responsibilities, and Interaction notes so teams understand typical handoffs.
