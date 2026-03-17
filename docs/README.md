# OctoAcme — Project Management Processes

This folder contains the program-process documentation used by OctoAcme. The goal is to keep practical, searchable guidance for project initiation, planning, execution, release, risk management, and continuous improvement.

Summary overview
- Purpose: Provide consistent, repeatable processes to plan, deliver, and learn from cross-functional projects.
- Principles: Customer-first, iterative delivery, clear ownership, data-informed decisions, psychological safety.
- Core flow: Initiation → Planning → Execution & Tracking → Release & Deployment → Retrospective & Improvement.

Key process docs
- Project Initiation: One-pager, stakeholder alignment, decision gate for planning.
- Project Planning: Kickoff, prioritized backlog, estimates, Definition of Done, release plan.
- Execution & Tracking: Team rhythm (standups, delivery syncs), PR/CI conventions, blocker escalation and execution checklist.
- Release & Deployment: Pre-release checks, deployment checklist, rollback & incident playbook, release notes template.
- Risk & Communication: Simple risk register, stakeholder communications, escalation paths.
- Retrospectives: Structure, action items, tracking, and follow-up.

Roles & responsibilities
- Project Manager (PM): plan, communicate, manage risks and timelines.
- Product Manager (PdM): define outcomes, prioritize, measure success.
- Developers & QA: deliver code, tests, and quality assurance.
- Stakeholders: provide input and approvals.

How to use these docs
- Each project should store its project-specific artifacts (One-pager, roadmap, risk register, retrospective notes) in the project repo.
- Add process-specific or project policies into `.copilot/` when you want Copilot Spaces to use them as context.
- Use the `.github/ISSUE_TEMPLATE/` templates for requesting updates to process docs.

Where to edit or request changes
- Use the "Add Content to Project Management Process Docs" issue template at `.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml` to propose new content or updates.
- For quick edits, open a PR that updates the appropriate file in `docs/`. For larger changes, start with an issue using the template to gather stakeholder input.

Notes
- Keep documents concise and actionable; prefer checklists and templates where possible.
- Review process docs yearly or whenever team practices change.
