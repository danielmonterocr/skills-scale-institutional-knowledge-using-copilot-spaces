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

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

---

## Additional Cross-functional Personas (added)

The following personas are commonly present on cross-functional projects at OctoAcme but are not always documented in project-level artifacts. Adding these clarifies accountabilities and handoff points.

### UX Designer

Role Summary:
Ensures the product is intuitive, accessible, and user-centered throughout development.

Responsibilities:
- Lead user research and usability testing
- Produce wireframes, prototypes, and visual assets
- Translate research into user stories and acceptance criteria for PdM
- Define accessibility baseline and track accessibility tasks
- Validate implemented UI with usability checks

Interaction:
- Works closely with Product Managers (PdMs) to define user problems and success criteria
- Partners with Developers and QA to ensure designs are feasible and testable
- Handoffs: provides design specs and acceptance criteria before implementation; participates in design reviews and demos

### DevOps Engineer

Role Summary:
Builds and maintains deployment pipelines, infrastructure, and CI/CD practices to enable reliable delivery.

Responsibilities:
- Automate builds, deployments, and monitoring
- Maintain infrastructure as code and environment consistency
- Define and operate observability and incident runbooks
- Harden deployment pipelines and manage secrets/credentials

Interaction:
- Coordinates with Developers for environment requirements and troubleshooting
- Works with QA to ensure environments allow repeatable testing
- Supports Releases and on-call incident response
- Handoffs: validates release readiness and runbook updates prior to production deploys

### Data Analyst

Role Summary:
Provides data-driven insights to inform product decisions and measure progress.

Responsibilities:
- Define key metrics and build dashboards for the product and project
- Instrument events and validate telemetry alongside Developers
- Analyze experiments (A/B tests) and support success criteria evaluation
- Translate findings into recommended actions and backlog items

Interaction:
- Partners with PdMs to define metrics and success criteria
- Works with Developers to implement reliable instrumentation
- Delivers reports to stakeholders and feeds results back into planning

### Security Lead

Role Summary:
Protects systems, data, and users from security threats across the project lifecycle.

Responsibilities:
- Define security requirements and review designs
- Conduct threat modeling and security-focused code reviews
- Ensure compliance checks and coordinate penetration testing where needed
- Respond to security incidents and coordinate disclosures

Interaction:
- Early engagement in planning for threat modeling with PdM/PM and Architects
- Collaborates with Developers to remediate vulnerabilities
- Coordinates with DevOps for secure deployment practices and secret management
- Handoffs: performs security sign-off for releases that meet the defined control set

### Business Analyst (BA)

Role Summary:
Translates business needs into actionable and testable requirements.

Responsibilities:
- Elicit and document business requirements, workflows, and rules
- Break down high-level requirements into acceptance criteria
- Validate requirements with stakeholders and the delivery team
- Support UAT and sign-off activities

Interaction:
- Works closely with PdMs and Stakeholders to clarify goals
- Partners with Developers and QA to ensure acceptance criteria are testable
- Handoffs: delivers detailed requirement artifacts prior to sprint planning and supports clarification during implementation

---

## Notes on usage and ownership
- These persona entries are intended to be lightweight, practical, and actionable.
- When you name roles on a project one person should be the primary owner for that responsibility (can be shared but ownership should be clear).
- Use the role-handoff-checklists.md (in docs/) for specific handoff and checklist templates to make interactions repeatable and visible.
