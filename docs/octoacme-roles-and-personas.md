# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Developers

### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

---

## Product Managers

### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

---

## Project Managers

### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

---

## Product Owner

### Role Summary
The Product Owner represents stakeholders and the business, ensuring that the team builds the right features to meet customer and business needs. They prioritize requirements, maintain the product backlog, and ensure deliverables align with the product vision.

### Responsibilities
- Define and communicate the product vision and strategy
- Prioritize and maintain the product backlog based on business value
- Create and refine user stories with clear acceptance criteria
- Collaborate with stakeholders to gather requirements and feedback
- Work closely with the Scrum Master and development team during sprint planning
- Accept or reject completed work based on acceptance criteria
- Make trade-off decisions between scope, time, and resources

### Goals
- Maximize the value of the product and return on investment
- Ensure features meet customer needs and business objectives
- Maintain a healthy, prioritized product backlog
- Foster strong collaboration between business and technical teams

### Typical Communication
- Daily availability for team questions and clarifications
- Sprint planning and backlog refinement sessions
- Sprint reviews and demonstrations to stakeholders
- Regular stakeholder meetings to gather feedback and communicate progress

### Interactions with Other Roles
- **Product Managers**: Aligns on product strategy and coordinates on broader product initiatives
- **Scrum Master**: Partners to ensure the team follows agile practices and removes impediments
- **Developers**: Provides clarification on requirements and acceptance criteria
- **UX/UI Designer**: Collaborates on user-centered design and validates against user needs
- **QA Lead**: Works together to ensure acceptance criteria are testable and met

---

## Scrum Master

### Role Summary
The Scrum Master facilitates agile ceremonies, ensures adherence to agile principles, and removes blockers that impede team progress. They serve the team by fostering an environment conducive to high performance and continuous improvement.

### Responsibilities
- Facilitate sprint ceremonies (planning, daily standups, reviews, retrospectives)
- Coach the team on agile principles and practices
- Remove impediments and blockers that hinder team progress
- Shield the team from external distractions and interruptions
- Foster a culture of continuous improvement and psychological safety
- Track team velocity and help with predictable delivery
- Facilitate communication and collaboration within the team and with stakeholders

### Goals
- Enable the team to be self-organizing and high-performing
- Ensure consistent adherence to agile practices
- Maximize team velocity and predictability
- Foster continuous learning and improvement

### Typical Communication
- Daily standups to identify and address blockers
- Sprint ceremonies facilitation and time-boxing
- One-on-ones with team members to address concerns
- Coordination meetings with other Scrum Masters and leadership

### Interactions with Other Roles
- **Product Owner**: Collaborates to maintain a healthy backlog and facilitate sprint planning
- **Project Managers**: Coordinates on cross-team dependencies and resource allocation
- **Developers**: Coaches on agile practices and removes impediments
- **DevOps Engineer**: Works together to improve deployment processes and automation
- **QA Lead**: Ensures quality practices are integrated into the sprint workflow

---

## UX/UI Designer

### Role Summary
The UX/UI Designer ensures user-centric design by creating intuitive, accessible, and visually appealing interfaces. They conduct user research, develop prototypes, and work closely with product and engineering teams to align designs with requirements and technical constraints.

### Responsibilities
- Conduct user research and usability testing to understand user needs
- Create wireframes, mockups, and interactive prototypes
- Design user interfaces that are intuitive, accessible, and brand-consistent
- Collaborate with Product Owner and developers to ensure design feasibility
- Develop and maintain design systems and style guides
- Iterate on designs based on user feedback and analytics
- Advocate for the user throughout the product development process

### Goals
- Deliver user experiences that are intuitive and delightful
- Ensure accessibility and usability standards are met
- Maintain design consistency across the product
- Balance user needs with business goals and technical constraints

### Typical Communication
- Design reviews and critique sessions with the team
- User research findings and insights presentations
- Collaboration sessions with Product Owner and developers
- Handoff meetings to ensure design specifications are understood

### Interactions with Other Roles
- **Product Owner**: Collaborates on understanding user needs and prioritizing design work
- **Product Managers**: Aligns design work with product strategy and roadmap
- **Developers**: Works closely during implementation to ensure design fidelity
- **QA Lead**: Partners to ensure design specifications are met and validated
- **Scrum Master**: Participates in sprint planning to estimate and commit to design work

---

## QA Lead

### Role Summary
The QA Lead oversees quality assurance planning and execution, coordinates defect triage, and ensures that releases meet quality standards. They establish testing strategies, mentor QA engineers, and work cross-functionally to maintain high product quality.

### Responsibilities
- Develop and maintain the overall test strategy and plan
- Coordinate test execution across manual and automated testing
- Lead defect triage and prioritization with the team
- Define and track quality metrics and release criteria
- Mentor and guide QA engineers on testing best practices
- Ensure test coverage for critical user flows and edge cases
- Collaborate with development and operations on quality gates

### Goals
- Ensure releases meet quality standards and acceptance criteria
- Minimize production defects and customer-impacting issues
- Continuously improve test coverage and efficiency
- Foster a quality-first culture across the team

### Typical Communication
- Daily standups to report on testing status and blockers
- Defect triage meetings to prioritize and assign bugs
- Test plan reviews with Product Owner and development team
- Release readiness meetings to assess go/no-go decisions

### Interactions with Other Roles
- **Product Owner**: Validates that acceptance criteria are met and features are ready
- **Developers**: Collaborates on testability, test automation, and defect resolution
- **DevOps Engineer**: Works together on test automation infrastructure and CI/CD pipelines
- **UX/UI Designer**: Validates design specifications and user experience quality
- **Project Managers**: Provides testing status and risk assessments for project tracking

---

## DevOps Engineer

### Role Summary
The DevOps Engineer designs and manages CI/CD pipelines, automates deployments, and maintains infrastructure to enable reliable and efficient software delivery. They bridge development and operations, ensuring smooth deployments and system reliability.

### Responsibilities
- Design, implement, and maintain CI/CD pipelines
- Automate build, test, and deployment processes
- Manage infrastructure as code (IaC) and cloud resources
- Monitor system performance, reliability, and security
- Implement and maintain observability tools (logging, metrics, alerts)
- Collaborate with development teams on deployment strategies
- Respond to production incidents and participate in on-call rotations

### Goals
- Enable fast, reliable, and frequent deployments
- Minimize deployment failures and rollback incidents
- Ensure infrastructure scalability and cost-efficiency
- Maintain high system availability and performance

### Typical Communication
- Daily standups to report on infrastructure status and deployment readiness
- Deployment planning and coordination meetings
- Incident response and post-mortems
- Infrastructure and tooling updates to the team

### Interactions with Other Roles
- **Developers**: Collaborates on build processes, deployment scripts, and infrastructure needs
- **QA Lead**: Provides test automation infrastructure and ensures quality gates in CI/CD
- **Scrum Master**: Coordinates on removing infrastructure-related blockers
- **Project Managers**: Communicates deployment schedules and infrastructure risks
- **Product Owner**: Ensures deployment strategies align with feature rollout plans

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

