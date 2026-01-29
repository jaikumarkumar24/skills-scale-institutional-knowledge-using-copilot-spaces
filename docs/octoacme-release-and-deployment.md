# OctoAcme — Release & Deployment Guide

## Purpose
Standardize how OctoAcme releases features to production to reduce risk and improve observability.

## Release Types
- Patch: hotfixes addressing critical production issues
- Minor: incremental features and improvements
- Major: significant functionality or breaking changes

## Pre-release requirements
- All acceptance criteria met and PRs merged (validated by Product Owner and QA Lead)
- Passing CI and security scans (monitored by DevOps Engineer)
- Release notes drafted (by PM with input from Product Owner)
- Rollback / mitigation plan documented (by DevOps Engineer)
- Smoke tests prepared and executed (by QA Lead)
- Design specifications verified (by UX/UI Designer for UI changes)

## Deployment Checklist
- [ ] Deployment window scheduled (if needed) - coordinated by PM and DevOps Engineer
- [ ] Backup or snapshot (if applicable) - executed by DevOps Engineer
- [ ] Deploy to staging and run smoke tests - QA Lead coordinates testing
- [ ] Deploy to production (automated pipeline preferred) - managed by DevOps Engineer
- [ ] Run post-deploy verifications - QA Lead validates critical flows
- [ ] Monitor system metrics and alerts - DevOps Engineer watches observability dashboards
- [ ] Announce release to stakeholders and support - PM communicates with Product Owner approval

## Rollback & Incident Playbook
- If a deployment fails or causes a critical issue:
  - Trigger incident response and notify on-call (DevOps Engineer leads)
  - Scrum Master facilitates team coordination during incident
  - Rollback to last known-good release if necessary (executed by DevOps Engineer)
  - Triage root cause and capture action items (PM coordinates with QA Lead and Developers)
  - Conduct blameless post-mortem (facilitated by Scrum Master)

## Release Notes Template
- Release name / number:
- Date:
- Summary:
- Notable changes:
- Migration steps (if any):
- Known issues:
