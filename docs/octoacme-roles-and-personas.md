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

## Release Managers

### Role Summary
Release Managers coordinate release planning and deployment readiness, ensuring that changes reach production safely and with clear communication.

### Responsibilities
- Plan release windows and sequence changes
- Confirm that acceptance criteria, CI checks, and security scans are complete
- Coordinate rollback and mitigation plans
- Lead go/no-go readiness checks and release communications
- Verify post-deployment checks and stakeholder announcements

### Goals
- Reduce deployment risk and downtime
- Make release decisions based on complete evidence
- Improve visibility and predictability of production changes

### Typical Communication
- Release readiness reviews with QA and Developers
- Schedule and risk updates with the Project Manager
- Rollout and support handoffs with Operations and Support teams

### Interactions with existing roles
- Work with Developers to confirm implementation and rollback readiness.
- Work with Product Managers to align release scope and customer impact.
- Work with Project Managers to track schedule, dependencies, and risks.
- Coordinate with QA/Testing on acceptance evidence and smoke-test results.

---

## UX/Design Leads

### Role Summary
UX/Design Leads represent customers and users in product decisions, create usable experiences, and validate that implementation meets design and accessibility expectations.

### Responsibilities
- Conduct or synthesize user research
- Create interaction designs, prototypes, and design standards
- Translate customer needs into clear experience requirements
- Participate in design reviews and usability validation
- Help identify usability and accessibility risks

### Goals
- Improve usability, accessibility, and customer satisfaction
- Maintain consistent, reusable design patterns
- Resolve experience trade-offs early

### Typical Communication
- Discovery and prioritization sessions with the Product Manager
- Design reviews and implementation pairing with Developers
- Usability and acceptance reviews with QA/Testing

### Interactions with existing roles
- Partner with Product Managers to clarify customer problems and desired outcomes.
- Collaborate with Developers on feasible designs and implementation details.
- Help QA/Testing define usability and accessibility acceptance criteria.
- Coordinate with Project Managers on design milestones and dependencies.

---

## Data/Analytics Leads

### Role Summary
Data/Analytics Leads ensure that projects define meaningful measures, collect reliable data, and use evidence to evaluate outcomes.

### Responsibilities
- Define success metrics and reporting requirements
- Design instrumentation and validation plans
- Review experiments and analyze project outcomes
- Identify data-quality, privacy, and measurement risks
- Translate findings into recommended decisions

### Goals
- Improve the accuracy of success measurement
- Enable timely, data-informed decisions
- Demonstrate whether delivered work creates customer or business value

### Typical Communication
- Metric definition and experiment reviews with Product Managers
- Instrumentation and validation planning with Developers
- Progress and measurement updates with Project Managers

### Interactions with existing roles
- Work with Product Managers to convert outcomes into measurable success criteria.
- Collaborate with Developers to add and verify telemetry.
- Provide QA/Testing with data validation needs and evidence expectations.
- Work with Project Managers to track reporting milestones and measurement risks.

---

## Security Leads

### Role Summary
Security Leads provide guidance and assurance for identifying threats, applying controls, meeting compliance needs, and prioritizing security remediation.

### Responsibilities
- Facilitate threat modeling and security risk reviews
- Define applicable security and compliance requirements
- Review security-sensitive designs and implementation
- Coordinate security testing, scanning, and remediation
- Guide incident and vulnerability escalation

### Goals
- Reduce security and compliance risk
- Make security requirements clear and actionable
- Integrate security checks into normal delivery workflows

### Typical Communication
- Threat modeling and design reviews with Developers
- Security acceptance reviews with QA/Testing
- Risk and escalation updates with Project Managers

### Interactions with existing roles
- Advise Product Managers on scope implications and security trade-offs.
- Help Developers implement secure designs and remediate findings.
- Work with QA/Testing on security test coverage and acceptance evidence.
- Coordinate with Project Managers on security risks, owners, and escalations.

---

## Support/Operations Leads

### Role Summary
Support/Operations Leads prepare products and teams for reliable production operation, effective support, and timely incident response.

### Responsibilities
- Define operational monitoring and support requirements
- Create or review runbooks and incident handoffs
- Plan support readiness, staffing, and training
- Identify operational risks and capacity constraints
- Coordinate production incidents and feedback into improvement work

### Goals
- Improve reliability and supportability
- Shorten incident detection and recovery times
- Ensure support teams are prepared before rollout

### Typical Communication
- Operational readiness reviews with Release Managers and Developers
- Support and escalation planning with Project Managers
- Incident updates and retrospectives with Product Managers and Stakeholder Sponsors

### Interactions with existing roles
- Partner with Release Managers on rollout readiness, monitoring, and rollback.
- Work with Developers on runbooks, telemetry, and operational fixes.
- Help Project Managers track operational risks and dependencies.
- Coordinate with Stakeholder/Executive Sponsors on high-impact service or incident decisions.

---

## Stakeholder/Executive Sponsors

### Role Summary
Stakeholder/Executive Sponsors provide strategic direction, remove organizational barriers, resolve major trade-offs, and approve significant scope, funding, or priority decisions.

### Responsibilities
- Sponsor the project's purpose and expected business outcomes
- Approve major scope, budget, priority, or resource decisions
- Resolve cross-organizational blockers and escalations
- Review progress, benefits, and material risks
- Reinforce accountability and organizational support

### Goals
- Ensure the project remains aligned with strategy
- Enable timely decisions on high-impact trade-offs
- Improve delivery by removing blockers beyond the team

### Typical Communication
- Strategic and outcome updates with Product Managers
- Milestone, risk, and decision reviews with Project Managers
- Escalation and incident briefings with Support/Operations Leads

### Interactions with existing roles
- Give Product Managers strategic context and decision authority for priority trade-offs.
- Receive delivery, risk, and escalation updates from Project Managers.
- Support Developers and UX/Design Leads by unblocking organizational dependencies.
- Review high-impact release or operational decisions with Release Managers and Support/Operations Leads.

---

## How personas are used

A project does not need to assign every persona separately. The appropriate roles should be identified during initiation and planning, and one person may hold more than one role when capacity is limited. Assignments should remain clear: each role needs named decision rights, deliverables, and escalation expectations. Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise, and as persona prompts for Copilot Spaces to shape role-specific guidance.
