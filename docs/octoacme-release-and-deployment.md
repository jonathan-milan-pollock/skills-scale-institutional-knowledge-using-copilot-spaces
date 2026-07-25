# OctoAcme — Release & Deployment Guide

## Purpose
Standardize how OctoAcme releases features to production to reduce risk and improve observability.

## Release Types
- Patch: hotfixes addressing critical production issues
- Minor: incremental features and improvements
- Major: significant functionality or breaking changes

## Pre-release requirements
- All acceptance criteria met and PRs merged
- Passing CI and security scans
- Release notes drafted
- Rollback / mitigation plan documented
- Smoke tests prepared
- [Handoff / Operational Readiness Checklist](octoacme-handoff-operational-readiness-checklist.md) completed
- Support owner and escalation contacts confirmed

## Deployment Checklist
- [ ] Deployment window scheduled (if needed)
- [ ] Backup or snapshot (if applicable)
- [ ] Deploy to staging and run smoke tests
- [ ] Deploy to production (automated pipeline preferred)
- [ ] Run post-deploy verifications
- [ ] Announce release to stakeholders and support

## Rollback & Incident Playbook
- If a deployment fails or causes a critical issue:
  - Trigger incident response and notify on-call
  - Rollback to last known-good release if necessary
  - Triage root cause and capture action items

## Handoff & Operational Readiness
- Confirm support handoff notes are published before production release.
- Ensure runbook updates, dashboards, and alerts are reviewed by owning teams.
- Capture go/no-go decisions and approvals in the [Decision Log](octoacme-decision-log-template.md).
- Use ownership assignments from the [RACI / Ownership Matrix](octoacme-raci-template.md) to avoid release-day ambiguity.

## Release Notes Template
- Release name / number:
- Date:
- Summary:
- Notable changes:
- Migration steps (if any):
- Known issues:
- Operational owner / on-call:
