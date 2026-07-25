# OctoAcme Project Management Overview

## Purpose
Provide a concise, shareable introduction to how OctoAcme runs projects so new teammates can quickly understand our approach, roles, and key artifacts.

## Scope
Applies to all cross-functional projects that deliver product features, services, or integrations.

## Principles
- Customer-first: prioritize customer value and usability.
- Iterative delivery: deliver small, testable increments.
- Clear ownership: each project has a named Project Manager (PM) and Product Lead.
- Data-informed decisions: measure impact and iterate based on evidence.
- Psychological safety: encourage feedback and learning.

## Core Roles
- Project Manager (PM): coordinates delivery, schedules, risk, communications.
- Product Manager (PdM): defines outcomes, prioritizes backlog, and measures success.
- Developers: implement features, collaborate on design and testability.
- QA/Testing: validate quality and acceptance criteria.
- Stakeholders: provide inputs and approvals.

## Key Artifacts
- Project Charter / One-pager
- Roadmap and Release Plan
- Sprint/Iteration Backlog
- Acceptance Criteria & Definition of Done
- Definition of Ready checklist
- Decision Log
- RACI / Ownership Matrix
- Risk Register
- Handoff / Operational Readiness checklist
- Retrospective notes and action items

## Governance Standards
- Every active project must have a named owner for scope, delivery, and release readiness.
- Use a project-level [RACI / Ownership Matrix](octoacme-raci-template.md) for major workstreams and decisions.
- Capture key approvals, tradeoffs, and reversals in a [Decision Log](octoacme-decision-log-template.md).
- Use standard artifact names (`project-charter`, `decision-log`, `risk-register`, `release-notes`) to keep handoffs consistent.
- Store project artifacts in one source of truth (project repo `docs/` folder or linked workspace).

## Lifecycle (high-level)
1. Initiation: problem statement, stakeholders, high-level timeline.
2. Planning: scope, resources, milestones, dependencies.
3. Execution: build, test, review, iterate.
4. Release: deploy, verify, announce.
5. Close & Retrospective: capture learnings and next steps.

## Communication Cadence
- Weekly sync between PM + PdM
- Twice-weekly standups for delivery team (or as agreed)
- Monthly stakeholder updates
- Ad-hoc escalations as needed

## How to use these docs
- Keep the Project Charter updated in the project repo.
- Copy and tailor templates for each project:
  - [Definition of Ready Checklist](octoacme-definition-of-ready-checklist.md)
  - [RACI Template](octoacme-raci-template.md)
  - [Decision Log Template](octoacme-decision-log-template.md)
  - [Handoff / Operational Readiness Checklist](octoacme-handoff-operational-readiness-checklist.md)
- Add process-specific docs into `.copilot/` if you want Copilot Spaces to use them as context.
