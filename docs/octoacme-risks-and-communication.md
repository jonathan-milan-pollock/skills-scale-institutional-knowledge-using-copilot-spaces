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

## Ownership & Accountability
- Every risk and dependency must have one directly responsible owner.
- Confirm roles and escalation ownership using the [RACI / Ownership Matrix](octoacme-raci-template.md).
- If ownership changes, update the risk register and communicate in the next status update.

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
- Decision log updates:

Incident Communication
- Triage summary
- Actions being taken
- Expected timeline
- Post-incident blameless retrospective scheduled

## Escalation Paths
- Team-level -> PM -> Product Lead -> Sponsor
- For security incidents, follow the security incident runbook and notify Security on-call

## Decision Logging Standard
- Log high-impact decisions (scope, timeline, staffing, risk acceptance) in the [Decision Log](octoacme-decision-log-template.md).
- Use a unique decision ID in communications when requesting approval or raising escalation.
- Include rationale and revisit trigger to make future handoffs and retrospectives easier.
