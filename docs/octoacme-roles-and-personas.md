# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises. Role assignments may be combined or shared depending on project size, but decision rights and handoffs should remain explicit.

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

## Additional Project Roles

The following roles make ownership, decision rights, and handoffs explicit across initiation, planning, execution, release, and retrospective activities. A person may fill more than one role, but the project should identify who is accountable for each responsibility.

## Project Sponsor / Executive Sponsor

### Role Summary
The Project Sponsor provides strategic sponsorship and organizational support. They authorize or stop work, secure funding and capacity, resolve executive-level conflicts, and ensure the project remains connected to business outcomes.

### Responsibilities and Decision Rights
- Approve the project’s initiation, priority, funding, and major scope changes
- Confirm the business outcomes and success measures with the Product Manager
- Make or sponsor decisions when trade-offs exceed the team’s authority
- Remove organizational obstacles and provide executive escalation
- Review milestone health, risks, and benefits realization

### Lifecycle Participation and Deliverables
- **Initiation:** approve the one-pager and go/no-go decision
- **Planning:** confirm scope, resources, milestones, and priority trade-offs
- **Execution:** review status and intervene on material risks or dependencies
- **Release:** support readiness decisions for high-impact launches
- **Retrospective:** review outcomes and authorize follow-up investment

### Collaboration and Handoffs
Partners with the Project Manager on authorization, escalation, and governance; with the Product Manager on value, priority, and outcomes; and with stakeholders on alignment. The Project Manager supplies status, risks, and decisions needed, while the Sponsor makes decisions that require executive authority.

---

## Technical Lead / Architect

### Role Summary
The Technical Lead or Architect owns the technical direction and helps the team make sustainable design and implementation decisions.

### Responsibilities and Decision Rights
- Define and communicate the technical approach and architecture boundaries
- Review designs, estimates, dependencies, and technical assumptions
- Identify technical risks, integration points, and mitigation options
- Set or advise on engineering quality, reliability, and observability standards
- Make technical design decisions within the agreed product and project constraints

### Lifecycle Participation and Deliverables
- **Initiation:** assess feasibility, constraints, and early technical risks
- **Planning:** break work into increments, estimate complexity, and map dependencies
- **Execution:** guide Developers, review designs and PRs, and manage technical decisions
- **Release:** confirm technical readiness, migration plans, and rollback considerations
- **Retrospective:** identify architectural or engineering improvements

### Collaboration and Handoffs
Works with the Product Manager to translate outcomes into feasible solutions, the Project Manager to surface dependencies and schedule impacts, Developers to guide implementation, and QA/Testing to make quality risks testable. Hands release risks and operational requirements to the Release/DevOps Engineer and escalates unresolved technical risks through the Project Manager.

---

## UX / Design Lead

### Role Summary
The UX/Design Lead represents user needs, usability, accessibility, and interaction quality throughout delivery.

### Responsibilities and Decision Rights
- Research user needs and turn them into usable, accessible designs
- Define user flows, interaction patterns, prototypes, and design acceptance criteria
- Validate designs with users or stakeholders where appropriate
- Identify usability and accessibility risks before implementation
- Maintain design decisions and shared patterns for the project

### Lifecycle Participation and Deliverables
- **Initiation:** contribute user problems, research insights, and experience goals
- **Planning:** provide designs, journey maps, estimates for design work, and acceptance criteria
- **Execution:** collaborate with Developers and QA/Testing to resolve design questions
- **Release:** support usability checks, release content, and feedback collection
- **Retrospective:** review adoption and experience feedback for improvements

### Collaboration and Handoffs
Partners with the Product Manager on user outcomes and prioritization, Developers on feasible implementation, and QA/Testing on usability and accessibility validation. Provides design artifacts and decisions to the team; the Product Manager resolves product priority conflicts and the Project Manager coordinates design dependencies.

---

## Security / Privacy Lead

### Role Summary
The Security/Privacy Lead identifies security, privacy, regulatory, and compliance needs and helps the team manage them throughout the delivery lifecycle.

### Responsibilities and Decision Rights
- Identify security, privacy, data handling, and compliance requirements
- Facilitate threat, privacy, and risk assessments
- Define required controls, reviews, evidence, and security acceptance criteria
- Advise on vulnerability remediation and incident readiness
- Escalate unresolved security or privacy risks and recommend release conditions

### Lifecycle Participation and Deliverables
- **Initiation:** identify regulatory constraints, sensitive data, and security risks
- **Planning:** add controls, security tasks, and verification activities to the backlog
- **Execution:** advise Developers and Technical Leads and review scan findings
- **Release:** confirm required security checks, approvals, and incident readiness
- **Retrospective:** capture security or privacy lessons and corrective actions

### Collaboration and Handoffs
Works with the Technical Lead on architecture and threat mitigation, Developers on secure implementation, QA/Testing on verification, and the Release/DevOps Engineer on scanning and deployment controls. Coordinates with the Project Manager on risk-register status and escalation; release-blocking concerns are communicated before deployment.

---

## Release / DevOps Engineer

### Role Summary
The Release/DevOps Engineer owns deployment automation, environments, operational readiness, observability, and rollback support.

### Responsibilities and Decision Rights
- Maintain deployment pipelines, environments, configuration, and release automation
- Define operational readiness, monitoring, alerting, and rollback requirements
- Coordinate release sequencing, deployment verification, and recovery actions
- Document operational handoffs and support procedures
- Report deployment or service risks and recommend mitigation or delay when needed

### Lifecycle Participation and Deliverables
- **Initiation:** identify environment, operational, and integration constraints
- **Planning:** estimate deployment work and define release dependencies
- **Execution:** maintain CI/CD, environments, and test deployment paths
- **Release:** run deployment, smoke tests, post-deploy verification, and rollback plans
- **Retrospective:** report operational outcomes and improve automation or reliability

### Collaboration and Handoffs
Works with Developers and the Technical Lead on build and deployment requirements, QA/Testing on environment and smoke-test readiness, and the Security/Privacy Lead on pipeline controls. Coordinates with the Project Manager on release timing and risks, and with Customer/Support representatives on operational handoff and communications.

---

## Data / Analytics Lead

### Role Summary
The Data/Analytics Lead ensures that instrumentation and analysis can demonstrate whether the project achieves its intended outcomes.

### Responsibilities and Decision Rights
- Define measurement plans, events, data quality expectations, and reporting needs
- Translate Product Manager success metrics into observable signals
- Design dashboards or analyses for usage, impact, errors, and performance
- Validate instrumentation with Developers and QA/Testing
- Explain results and recommend evidence-based iteration

### Lifecycle Participation and Deliverables
- **Initiation:** validate that success metrics are measurable and define baselines
- **Planning:** add instrumentation and analysis work to the backlog
- **Execution:** review event implementation and data quality
- **Release:** establish dashboards and monitor early outcome signals
- **Retrospective:** analyze results and recommend improvements or follow-up work

### Collaboration and Handoffs
Partners with the Product Manager on outcomes and interpretation, Developers on instrumentation, and QA/Testing on data validation. Provides dashboards and findings to the Project Manager and stakeholders, who use them for status, decisions, and retrospective actions.

---

## Customer / Support Representative

### Role Summary
The Customer/Support Representative brings customer feedback and operational experience into planning and ensures support teams are prepared for delivery changes.

### Responsibilities and Decision Rights
- Represent customer needs, recurring issues, and support impact
- Identify affected customer groups and operational workflows
- Contribute support acceptance criteria, knowledge-base needs, and readiness checks
- Coordinate support feedback during pilots or early release monitoring
- Escalate customer-impacting risks and unresolved service issues

### Lifecycle Participation and Deliverables
- **Initiation:** provide customer problem evidence and impact context
- **Planning:** identify affected workflows, support effort, and readiness tasks
- **Execution:** review customer-facing behavior and prepare support materials
- **Release:** confirm support readiness, monitor feedback, and route incidents
- **Retrospective:** share customer outcomes and recurring issues for improvement

### Collaboration and Handoffs
Works with the Product Manager on customer value and prioritization, the Project Manager on readiness and escalations, QA/Testing on acceptance scenarios, and Release/DevOps on operational handoffs. Shares feedback with the team and receives release notes, known issues, and support guidance from the responsible leads.

---

## Change Management / Communications Lead

### Role Summary
The Change Management/Communications Lead prepares people and organizations to understand, adopt, and support project outcomes.

### Responsibilities and Decision Rights
- Develop stakeholder, launch, training, and adoption communication plans
- Tailor messages to sponsors, internal teams, customers, and support groups
- Coordinate release announcements, enablement materials, and change impacts
- Track adoption risks, feedback, and communication dependencies
- Escalate gaps that could affect readiness or stakeholder alignment

### Lifecycle Participation and Deliverables
- **Initiation:** identify impacted audiences and communication needs
- **Planning:** create the communication, training, and adoption plan
- **Execution:** prepare updates, demos, enablement content, and feedback channels
- **Release:** coordinate announcements, training, and stakeholder messaging
- **Retrospective:** assess adoption and communication effectiveness

### Collaboration and Handoffs
Partners with the Project Manager on cadence and status communications, the Product Manager on value and product messaging, the Sponsor on executive alignment, and Customer/Support representatives on readiness content. Uses release details from Release/DevOps and known issues from Developers and QA/Testing to keep communications accurate.

---

## Lifecycle Responsibility and Interaction Guide

The Project Manager coordinates the overall lifecycle, while the Product Manager owns product value and prioritization. Specialist roles contribute decision-ready inputs and own their domains:

| Lifecycle stage | Primary coordination and contributions |
| --- | --- |
| Initiation | Sponsor authorizes; Product Manager defines the problem and outcomes; Project Manager coordinates the one-pager; Technical, UX, Security/Privacy, Data, Customer/Support, and Change leads identify constraints and affected audiences. |
| Planning | Product Manager prioritizes; Project Manager builds the plan and manages dependencies; Technical Lead estimates feasibility; UX defines experience requirements; Security/Privacy, Data, Release/DevOps, Support, and Change leads add readiness and risk work. |
| Execution | Developers implement; Technical Lead guides engineering; UX, Security/Privacy, Data, and QA/Testing validate their concerns; Project Manager tracks delivery; Support and Change leads prepare adoption and operational readiness. |
| Release | Release/DevOps coordinates deployment and verification; Developers and QA/Testing confirm quality; Security/Privacy confirms controls; Product Manager and Customer/Support review customer readiness; Change Lead coordinates announcements and enablement; Project Manager records the decision and risks. |
| Retrospective | Project Manager facilitates; Product Manager and Data/Analytics Lead review outcomes; all specialists contribute lessons and action items with owners and due dates. |

When responsibilities overlap, the accountable role should be named in the project plan or backlog. The Project Manager maintains the coordination view and escalation path, while domain leads retain decision rights for their areas and promptly surface decisions that affect scope, schedule, quality, risk, or release readiness.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
