# OctoAcme — Execution & Tracking

## Purpose
Guidance for managing day-to-day execution and tracking progress toward project milestones.

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

## Decision & Change Tracking
- Record material scope, architecture, timeline, and risk decisions in the [Decision Log](octoacme-decision-log-template.md).
- Include decision references in PRs when changes alter approved scope or release timing.
- Reconfirm owners in the [RACI / Ownership Matrix](octoacme-raci-template.md) when team composition changes.

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

## Handoff Readiness During Execution
- Track production readiness tasks before code-complete, not after release freeze.
- Keep runbooks, support notes, and monitoring updates in sync with feature delivery.
- Use the [Handoff / Operational Readiness Checklist](octoacme-handoff-operational-readiness-checklist.md) for release candidates.

## Execution Checklist
- [ ] Branching and PR conventions documented in repo
- [ ] CI configured for tests and lint
- [ ] Regular demos scheduled
- [ ] Risk register updated weekly
- [ ] Decision log updated for major scope/timeline changes
- [ ] RACI ownership reviewed at milestone boundaries
- [ ] Handoff / operational readiness checklist started before release
