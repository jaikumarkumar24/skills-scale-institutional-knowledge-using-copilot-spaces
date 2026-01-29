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

## Risk Lifecycle
- Identify: during planning and ongoing execution
- Assess: estimate impact and likelihood
- Mitigate: reduced via actions, contingency plans
- Monitor: review at weekly syncs and update status

## Stakeholder Communication
- Identify stakeholder groups and communication needs (e.g., engineering, sales, support)
- PM coordinates communication with input from Product Owner
- Provide regular updates (weekly or milestone-based)
- Use a single source of truth (project README or release doc) for status
- UX/UI Designer shares design decisions and rationale with stakeholders
- DevOps Engineer communicates infrastructure changes and deployment schedules

## Communication Templates
Weekly Status Template:
- Progress this week:
- Next steps:
- Risks & blockers:
- Ask / decisions needed:

Incident Communication
- Triage summary
- Actions being taken
- Expected timeline
- Post-incident blameless retrospective scheduled

## Escalation Paths
- Team-level -> Scrum Master -> PM -> Product Lead -> Sponsor
- Scrum Master removes blockers and coordinates with PM for escalations
- For security incidents, DevOps Engineer follows the security incident runbook and notifies Security on-call
- QA Lead escalates quality risks that may impact release timeline
