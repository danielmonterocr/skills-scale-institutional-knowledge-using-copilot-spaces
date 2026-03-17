# Role Handoff Checklists

This file contains practical, copy-paste checklists teams can use to standardize handoffs between personas listed in octoacme-roles-and-personas.md.

---

## UX → PdM / Dev: Design Handoff Checklist
- [ ] Design prototype (link) uploaded and versioned
- [ ] Key user journeys documented with acceptance criteria
- [ ] Accessibility requirements noted
- [ ] Design assets and specs (Figma/Zeplin) linked
- [ ] Interaction notes and edge-cases documented
- [ ] Stakeholder sign-off (if required)
- [ ] Design review scheduled with Dev and QA
- [ ] Handoff ticket created with links to artifacts

---

## DevOps: Pre-release Checklist
- [ ] CI pipeline green for release branch
- [ ] Infrastructure-as-code reviewed and applied to staging
- [ ] Smoke tests for critical flows defined and passing in staging
- [ ] Rollback plan documented and tested
- [ ] Monitoring/dashboards updated for new changes
- [ ] Runbook/incident playbook updated
- [ ] Secrets and credentials validated
- [ ] Release window and communication plan confirmed

---

## Security Review Checklist
- [ ] Threat model completed for feature/epic
- [ ] Static analysis / SCA scan results reviewed
- [ ] Known vulnerabilities triaged or documented with mitigation plan
- [ ] Sensitive data flows documented
- [ ] Security sign-off or open issues tracked in Risk Register

---

## Data Instrumentation & Metrics Checklist
- [ ] Metrics and success criteria defined (owner: PdM/Analyst)
- [ ] Event names and schemas documented
- [ ] Devs have tickets for instrumentation work
- [ ] Test data validated in staging
- [ ] Dashboards and alerts created/updated
- [ ] Analyst sign-off on data quality before analysis

---

## BA → Delivery: Requirements Acceptance Checklist
- [ ] Business rules and workflows documented
- [ ] Acceptance criteria explicit and testable
- [ ] UAT scenarios listed and owners assigned
- [ ] Stakeholder acceptance criteria and sign-offs documented
- [ ] Any regulatory/compliance needs listed

---

Usage:
- Copy the relevant checklist into your project backlog item or release playbook.
- Check items during planning and pre-release activities. Assign an owner for each checked item.
