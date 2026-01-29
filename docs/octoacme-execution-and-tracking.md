# OctoAcme — Execution & Tracking

## Purpose
Guidance for managing day-to-day execution and tracking progress toward project milestones.

## Team Rhythm
- **Daily standups (15 min)** — facilitated by Scrum Master; focus on progress, blockers, dependencies
- **Weekly delivery sync** — show progress, updates, and flagged risks; attended by PM, PdM, Product Owner, and team leads
- **Demo/Review at the end of each sprint or milestone** — presented to stakeholders, Product Owner validates acceptance criteria
- **Design reviews** — UX/UI Designer presents designs to team and stakeholders for feedback
- **Defect triage meetings** — QA Lead coordinates prioritization of bugs with development team

## Workflows
- Use the project board (e.g., GitHub Projects) with columns: Backlog, Ready, In Progress, In Review, QA, Done
- Pull Request workflow:
  - Small PRs (<= 400 lines when possible)
  - Include issue link and acceptance criteria in PR description
  - Run automated tests and linting in CI before requesting review
  - Require at least one approval before merging (or team-defined policy)

## Quality & Testing
- **Unit tests** for new logic (written by Developers)
- **Integration tests** where applicable (coordinated by QA Lead)
- **End-to-end smoke tests** for critical flows before release (executed by QA team)
- **Security scanning** in CI (configured by DevOps Engineer)
- **Manual QA** for feature acceptance when needed (led by QA Lead)
- **Usability testing** for new UX features (conducted by UX/UI Designer)
- **Test automation infrastructure** maintained by DevOps Engineer and QA Lead

## Reporting & Metrics
- Track velocity and burndown
- Monitor success metrics identified in the Project One-pager
- Use dashboards for key signals (errors, latency, usage)

## Blocker Escalation
- **Level 1**: Team-level triage in daily standup (facilitated by Scrum Master)
- **Level 2**: PM escalates to Product Lead and dependent teams; Scrum Master coordinates removal
- **Level 3**: Sponsor-level escalation for business-impacting issues
- **Infrastructure blockers**: DevOps Engineer provides assessment and timeline

## Execution Checklist
- [ ] Branching and PR conventions documented in repo
- [ ] CI configured for tests and lint
- [ ] Regular demos scheduled
- [ ] Risk register updated weekly
