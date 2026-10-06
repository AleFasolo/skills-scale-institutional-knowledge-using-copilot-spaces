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

## QA / Testing Lead

### Role Summary
QA / Testing Leads ensure that product changes meet quality standards, acceptance criteria, and release readiness before work is promoted to production.

### Responsibilities
- Define the test strategy, coverage goals, and quality gates for each release
- Collaborate with developers and Product Managers to validate acceptance criteria
- Plan and coordinate functional, integration, and regression testing
- Escalate quality risks, defects, or release blockers early
- Support smoke testing and final verification before go-live

### Goals
- Reduce defects reaching production
- Improve confidence in milestone and release readiness
- Align testing efforts with business and user outcomes

### Typical Communication
- Quality reviews and bug triage with engineering teams
- Acceptance validation with Product Managers and stakeholders
- Release readiness updates to Project Managers and leadership

### Interaction with existing roles
- Works closely with Developers to review testability, automation gaps, and defect severity
- Partners with Product Managers to confirm that acceptance criteria are measurable and complete
- Provides Project Managers with release confidence and risk updates for decision-making

---

## Technical Lead / Architect

### Role Summary
Technical Leads and Architects guide the system design, technical direction, and architectural trade-offs needed to deliver reliable and scalable solutions.

### Responsibilities
- Define system architecture, design patterns, and technical standards
- Review high-risk technical decisions and design trade-offs with the team
- Identify dependencies, integration risks, and modernization opportunities
- Support estimation and technical planning with delivery teams
- Mentor engineers and help resolve complex technical blockers

### Goals
- Keep the solution aligned with long-term maintainability and scalability goals
- Reduce avoidable technical debt and architectural drift
- Support predictable delivery through well-defined technical direction

### Typical Communication
- Design reviews and architecture discussions with engineers
- Technical risk updates with Project Managers and stakeholders
- Sponsorship of engineering decisions that affect roadmap or dependencies

### Interaction with existing roles
- Works with Developers to ensure implementation aligns with the agreed architecture
- Collaborates with Product Managers to translate product goals into feasible technical options
- Helps Project Managers flag dependencies, sequencing issues, and cross-system risks early

---

## Release Manager

### Role Summary
Release Managers coordinate deployment readiness, communication, and verification to reduce release risk and ensure consistency across environments.

### Responsibilities
- Manage release planning, deployment windows, and communication timing
- Confirm that release checklists, smoke tests, and rollback plans are complete
- Coordinate handoffs between engineering, QA, support, and stakeholders
- Summarize deployment status, known issues, and post-release follow-up
- Support incident response and service restoration when a release causes disruption

### Goals
- Deliver predictable, low-risk releases
- Improve visibility for stakeholders and support teams
- Ensure rollback and mitigation plans are ready before production deployment

### Typical Communication
- Release readiness meetings and go/no-go checkpoints
- Status updates to Project Managers, stakeholders, and support teams
- Post-release summaries and incident communications when needed

### Interaction with existing roles
- Partners with QA / Testing Leads to confirm readiness before deployment
- Coordinates with Developers on release timing, rollback readiness, and production validation
- Keeps Project Managers and stakeholders informed on release scope, risks, and outcomes

---

## Security Officer

### Role Summary
Security Officers protect the organization by ensuring secure coding practices, proactive review of risks, and compliance with required security controls across projects.

### Responsibilities
- Review security requirements, threats, and controls relevant to the project
- Ensure security scanning, code review, and vulnerability management are built into delivery workflows
- Support secure design reviews and incident triage during critical events
- Coordinate with engineering and leadership on remediation priorities and risk acceptance
- Help define secure release criteria and escalation paths for security issues

### Goals
- Reduce security exposure and operational risk
- Ensure security is treated as part of project delivery, not as a separate activity
- Improve response speed for incidents and vulnerability management

### Typical Communication
- Security reviews and design discussions with engineers and architects
- Risk and incident updates with Project Managers and leadership
- Security posture reporting for stakeholders and compliance needs

### Interaction with existing roles
- Works with Developers to review risks in implementation and ensure secure coding practices
- Collaborates with QA / Testing Leads on vulnerability checks and secure release criteria
- Supports Project Managers and stakeholders in escalation, mitigation, and incident communication

---

## Stakeholder / Sponsor

### Role Summary
Stakeholders and Sponsors provide business context, strategic alignment, and leadership support to ensure the project remains valuable, funded, and well-prioritized.

### Responsibilities
- Confirm the business problem, desired outcomes, and project priority
- Approve milestones, scope trade-offs, and resource commitments
- Help resolve cross-team conflicts and unblock decisions that affect project delivery
- Review status, risks, and escalations with leadership visibility
- Support the business case and expected value realization of the initiative

### Goals
- Ensure the initiative remains aligned with organizational strategy
- Support successful delivery with clear priorities and timely decisions
- Maintain confidence in the project through transparent communication

### Typical Communication
- Executive updates, steering meetings, and milestone reviews
- Decision-making discussions with Product Managers and Project Managers
- Status reporting on business value, risks, and funding or resource needs

### Interaction with existing roles
- Provides direction to Product Managers and Project Managers on scope and priority
- Receives readiness, release, and risk updates from delivery leads and project coordinators
- Engages with Technical Leads and Security Officers when strategic decisions affect architecture or risk posture

---

## Scrum Master / Agile Coach

### Role Summary
Scrum Masters and Agile Coaches help teams improve collaboration, delivery flow, and continuous improvement while maintaining healthy agile practices.

### Responsibilities
- Facilitate sprint ceremonies, backlog refinement, and team-level coordination
- Help remove blockers that slow delivery and reduce friction across teams
- Support continuous improvement through retrospectives and team learning cycles
- Promote agile practices that improve predictability and shared understanding
- Help connect team health, delivery flow, and communication patterns with project goals

### Goals
- Improve team effectiveness and delivery rhythm
- Support a culture of transparency, learning, and accountability
- Reduce process friction so the team can focus on value delivery

### Typical Communication
- Sprint planning, review, and retrospective facilitation
- Team coaching and process improvement conversations
- Escalation support with Project Managers and stakeholders when delivery flow is blocked

### Interaction with existing roles
- Supports Developers and Product Managers in keeping work clear, prioritized, and ready for execution
- Works alongside Project Managers to surface risks, impediments, and team health issues
- Helps stakeholders understand team capacity, delivery patterns, and improvement opportunities

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- The full set of personas reflects how accountability is distributed across delivery, quality, security, release, and leadership functions.

