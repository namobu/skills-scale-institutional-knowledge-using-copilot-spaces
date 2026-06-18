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

## Technical Lead

### Role Summary
Technical Leads provide technical direction and own architecture and design decisions for a project or component. They mentor developers and drive technical quality.

### Responsibilities
- Define and own architecture and design choices for the project
- Review and approve significant technical designs and proposals
- Mentor developers and set engineering standards
- Identify technical risks and propose mitigations
- Ensure maintainability, scalability, and performance considerations are addressed

### Interaction
- Works closely with Developers on design and implementation details
- Coordinates with Project Manager on technical risks and timelines
- Escalates unresolved technical blockers to the Product Manager or Engineering Manager
- Partners with QA and SRE to ensure testability and operability

### Typical Communication
- Design review sessions
- Architecture decision records (ADR)
- Technical risk and dependency updates in weekly syncs

---

## Engineering Manager

### Role Summary
Engineering Managers oversee team capacity, career development, and organizational aspects of delivering projects. They remove organizational impediments and support team health.

### Responsibilities
- Balance resource allocation and team capacity
- Support performance coaching and career development
- Resolve organizational impediments and cross-team staffing issues
- Assist with hiring and staffing decisions when needed

### Interaction
- Partners with Project Manager on resourcing and timeline trade-offs
- Works with Product Manager to balance priorities against capacity
- Supports Technical Lead with staffing, mentorship, and performance issues

### Typical Communication
- Capacity planning and 1:1s
- Staffing and resourcing updates in planning meetings

---

## Design Lead / Product Designer

### Role Summary
Design Leads own the user experience, validate designs with research, and provide design assets and acceptance criteria for implementation.

### Responsibilities
- Define interaction and visual designs that meet user needs
- Validate solutions through user research or usability testing
- Produce design assets and annotated specifications for developers
- Collaborate on acceptance criteria related to UX

### Interaction
- Collaborates with Product Manager on user needs and prioritization
- Works with Developers during implementation to ensure design fidelity
- Participates in reviews and acceptance criteria definition with QA and PM

### Typical Communication
- Design walkthroughs and handoff documents
- Usability findings and design decision notes

---

## QA Lead / Test Owner

### Role Summary
QA Leads define the test strategy, coordinate manual and exploratory testing, and own release readiness from a quality perspective.

### Responsibilities
- Define test strategy and test plans for the project
- Coordinate manual QA, exploratory testing, and acceptance testing
- Ensure test coverage and automate where appropriate
- Maintain release acceptance criteria related to quality

### Interaction
- Coordinates with Developers for test coverage and defect triage
- Integrates with CI and Release Manager for pre-release checks
- Updates Project Manager on quality risks and release readiness

### Typical Communication
- Test plans, bug triage notes, and QA sign-off for releases

---

## Release Manager

### Role Summary
Release Managers coordinate deployments, maintain release plans and rollback strategies, and own post-deploy verification activities.

### Responsibilities
- Coordinate deployment schedules and release plans
- Maintain rollback and mitigation strategies for releases
- Ensure staging and production verification steps are executed
- Communicate release status to stakeholders and support teams

### Interaction
- Works with Project Manager, SRE/On-call, and QA Lead to schedule and validate releases
- Coordinates communications with Product Manager and support teams during releases

### Typical Communication
- Release runbooks, deployment checklists, and post-release reports

---

## SRE / On-call Engineer

### Role Summary
SREs maintain production reliability, own runbooks and monitoring, respond to incidents, and drive post-incident analysis and improvements.

### Responsibilities
- Define and maintain monitoring, alerting, and runbooks
- Respond to incidents and escalate as needed
- Participate in post-incident reviews and remediation
- Improve operability and automation to reduce toil

### Interaction
- Engages with Developers for production fixes and remediation plans
- Informs Project Manager and Product Manager about production-impacting issues
- Collaborates with Release Manager on deployment safety and rollback

### Typical Communication
- Incident notifications, post-incident reports, and on-call handover notes

---

## Data Analyst

### Role Summary
Data Analysts define and track success metrics, provide insights for prioritization, and support measurement of outcomes.

### Responsibilities
- Define tracking and success metrics aligned to product goals
- Produce analysis and reports to inform prioritization and retrospectives
- Validate data-related acceptance criteria and instrumentation

### Interaction
- Works with Product Manager to measure outcomes and set targets
- Supports Project Manager with reports and metrics for status updates
- Informs Developers and QA of data instrumentation requirements

### Typical Communication
- Dashboards, metric reports, and analysis notes for planning and retrospectives

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- When documenting projects, include a short list of the specific named people filling these roles (if known) in the project README or project one-pager to make handoffs explicit.
