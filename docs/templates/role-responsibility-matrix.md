# Role Responsibility Matrix (RACI)

## Purpose
This matrix clarifies who is Responsible, Accountable, Consulted, and Informed (RACI) for key project activities. Use this to ensure clear ownership and reduce confusion about roles.

## RACI Definitions
- **Responsible (R)**: Does the work to complete the task
- **Accountable (A)**: Ultimately answerable for the task; approves completion
- **Consulted (C)**: Provides input and expertise; two-way communication
- **Informed (I)**: Kept up-to-date on progress; one-way communication

---

## Project Initiation Phase

| Activity | PM | PdM | Product Owner | Scrum Master | Developers | UX/UI Designer | QA Lead | DevOps Engineer | Stakeholders |
|----------|----|----|---------------|--------------|------------|----------------|---------|-----------------|--------------|
| Define problem statement | C | A | R | I | C | C | I | I | C |
| Approve project charter | A | R | C | I | I | I | I | I | C |
| Identify stakeholders | R | A | C | I | I | I | I | I | I |
| Set high-level timeline | A | C | I | C | C | C | C | C | I |

---

## Project Planning Phase

| Activity | PM | PdM | Product Owner | Scrum Master | Developers | UX/UI Designer | QA Lead | DevOps Engineer | Stakeholders |
|----------|----|----|---------------|--------------|------------|----------------|---------|-----------------|--------------|
| Facilitate kickoff | R | C | C | R | I | I | I | I | I |
| Prioritize backlog | C | C | A | C | C | C | C | I | I |
| Estimate work | C | I | C | C | R | R | R | R | I |
| Define DoD | C | C | C | R | R | C | A | C | I |
| Identify dependencies | R | C | C | C | C | C | C | R | I |
| Create release plan | A | C | C | C | C | C | C | C | I |
| Design test strategy | C | I | C | C | C | C | A | C | I |
| Plan infrastructure | C | I | I | C | C | I | C | A | I |

---

## Execution & Tracking Phase

| Activity | PM | PdM | Product Owner | Scrum Master | Developers | UX/UI Designer | QA Lead | DevOps Engineer | Stakeholders |
|----------|----|----|---------------|--------------|------------|----------------|---------|-----------------|--------------|
| Facilitate daily standup | I | I | C | A | R | R | R | R | I |
| Implement features | I | I | C | C | A | C | C | C | I |
| Design UI/UX | I | C | C | C | C | A | I | I | I |
| Review & approve PRs | I | I | I | I | A | C | C | C | I |
| Execute tests | I | I | I | C | C | C | A | C | I |
| Manage CI/CD | I | I | I | C | C | I | C | A | I |
| Track progress | A | C | C | R | C | C | C | C | I |
| Triage blockers | C | C | C | A | R | R | R | R | I |
| Update stakeholders | A | C | C | C | I | I | I | I | I |

---

## Release & Deployment Phase

| Activity | PM | PdM | Product Owner | Scrum Master | Developers | UX/UI Designer | QA Lead | DevOps Engineer | Stakeholders |
|----------|----|----|---------------|--------------|------------|----------------|---------|-----------------|--------------|
| Validate acceptance criteria | C | C | A | I | C | C | R | I | I |
| Execute smoke tests | C | I | C | C | C | C | A | C | I |
| Approve release | A | C | C | I | I | I | C | C | I |
| Deploy to production | C | I | I | C | C | I | C | A | I |
| Verify deployment | C | I | C | C | C | C | R | R | I |
| Draft release notes | A | C | C | I | C | I | C | C | I |
| Announce release | A | C | C | I | I | I | I | I | I |

---

## Retrospective Phase

| Activity | PM | PdM | Product Owner | Scrum Master | Developers | UX/UI Designer | QA Lead | DevOps Engineer | Stakeholders |
|----------|----|----|---------------|--------------|------------|----------------|---------|-----------------|--------------|
| Facilitate retrospective | C | C | C | A | C | C | C | C | I |
| Contribute learnings | C | C | C | C | R | R | R | R | C |
| Define action items | C | C | C | R | C | C | C | C | I |
| Track improvements | R | C | C | C | C | C | C | C | I |

---

## How to Use This Matrix

1. **Review at project kickoff** to align on expectations
2. **Update for project-specific needs** — not all roles may apply to every project
3. **Reference during planning** to ensure clear ownership for each activity
4. **Revisit during retrospectives** if role confusion or gaps arise

For detailed role descriptions, see [Roles & Personas](../octoacme-roles-and-personas.md).
