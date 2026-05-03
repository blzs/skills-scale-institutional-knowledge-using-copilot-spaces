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

## QA / Testing

### Role Summary
QA/Testing engineers validate that features meet acceptance criteria, quality standards, and user expectations before release.

### Responsibilities
- Write and execute test plans, test cases, and regression suites
- Perform functional, integration, and acceptance testing
- File, track, and verify bug fixes
- Collaborate on the Definition of Done and acceptance criteria
- Support usability testing with UX Designer

### Goals
- Prevent defects from reaching production
- Reduce feedback cycles between development and acceptance
- Maintain comprehensive test coverage across all critical flows

### Typical Communication
- Sprint planning and demo feedback
- Bug reports and test-result summaries
- Coordination with Developers and UX on acceptance and usability criteria

---

## Stakeholders

### Role Summary
Stakeholders are individuals or groups with a business interest in the project's outcomes. They provide direction, approve decisions, and receive regular status updates.

### Responsibilities
- Provide clear business requirements and priorities
- Attend milestone reviews and demos
- Approve go/no-go decisions at key gates
- Communicate changes in business context that affect scope

### Goals
- Ensure the project delivers measurable business value
- Stay informed on progress, risks, and blockers
- Provide timely input so the team can move forward

### Typical Communication
- Monthly or milestone-based status briefings
- Review and sign-off at initiation and release gates
- Ad-hoc input on priority and scope changes

---

## UX Designer

### Role Summary
UX Designers shape user experience and ensure solutions meet usability and accessibility standards. They bridge user needs with technical implementation, ensuring the product is intuitive and valuable to end-users.

### Responsibilities
- Conduct user interviews, surveys, and feedback sessions
- Create wireframes, mockups, and interactive prototypes
- Define and document user journeys and interaction patterns
- Collaborate with Product and Development on interfaces and flows
- Validate outcomes with end-users through usability testing
- Ensure accessibility standards (e.g., WCAG) are met

### Goals
- Deliver intuitive, accessible experiences that users value
- Reduce usability defects discovered late in development
- Build a shared understanding of user needs across the team

### Typical Communication
- Design reviews and prototype walkthroughs with Product and Engineering
- Usability test results shared with QA and Product Manager
- Design system updates and accessibility notes in PRs

### Interactions with Existing Roles
- **Developers:** Reviews technical feasibility of designs; provides annotated specs and responds to implementation questions.
- **Product Managers:** Translates product requirements into user flows; validates designs against success metrics.
- **Project Managers:** Flags UX-related risks (e.g., unvalidated designs in scope); provides effort estimates for design tasks.
- **QA / Testing:** Collaborates on usability test plans; reviews UX-related bug reports and acceptance criteria.
- **Stakeholders:** Presents prototypes and usability findings at milestone demos; incorporates stakeholder feedback.

---

## DevOps Engineer

### Role Summary
DevOps Engineers manage build, deployment, and monitoring infrastructure to ensure a stable, repeatable, and scalable delivery pipeline. They enable the team to ship reliably and recover quickly from incidents.

### Responsibilities
- Maintain and improve CI/CD pipelines and build automation
- Provision and manage environments (staging, production)
- Implement infrastructure-as-code and configuration management
- Monitor system health, performance, and alerts
- Coordinate deployment windows and execute releases
- Lead incident response and post-incident recovery
- Document runbooks and deployment procedures

### Goals
- Maximise deployment frequency and reduce lead time to production
- Minimise unplanned downtime and mean time to recovery (MTTR)
- Ensure environments are consistent, secure, and auditable

### Typical Communication
- Pre-release deployment plans and rollback procedures shared with PM
- Incident status updates and post-mortems
- CI/CD configuration changes communicated via PR and release notes

### Interactions with Existing Roles
- **Developers:** Partners on branch strategy, build failures, and deployment tooling; reviews infrastructure-impacting code changes.
- **Product Managers:** Communicates deployment windows and release readiness; flags infrastructure constraints on roadmap items.
- **Project Managers:** Reports deployment status and incident timelines; contributes to risk register for infrastructure risks.
- **QA / Testing:** Provides and maintains test environments; assists in reproducing environment-related defects.
- **Stakeholders:** Communicates release schedules and service availability; reports incident resolution status.

---

## Security Champion

### Role Summary
The Security Champion advocates for security best practices within the team and acts as the first responder for potential threats. They embed security thinking throughout the development lifecycle rather than treating it as a gate at the end.

### Responsibilities
- Conduct security reviews and threat-modelling sessions for new features
- Maintain and triage security scanning results in CI/CD (SAST, dependency checks)
- Recommend and track mitigation plans for identified risks
- Deliver security awareness sessions for the team
- Coordinate with engineering and operations on vulnerability remediation
- Own the security section of the Risk Register
- Act as the team's point of contact for the security incident runbook

### Goals
- Shift security left — identify and resolve issues early in development
- Reduce the attack surface and exposure of production systems
- Build a security-aware team culture

### Typical Communication
- Security review findings documented in GitHub issues or the Risk Register
- Incident alerts and escalations via the security incident runbook
- Awareness updates shared in team syncs and Slack/chat channels

### Interactions with Existing Roles
- **Developers:** Leads threat-modelling and secure code review sessions; reviews security-sensitive PRs; provides guidance on secure patterns.
- **Product Managers:** Identifies security implications of product decisions; raises security items that may affect roadmap or scope.
- **Project Managers:** Contributes security risks to the Risk Register; escalates unresolved vulnerabilities that impact timelines.
- **QA / Testing:** Defines security-specific test cases; reviews pen-test or SAST findings together.
- **Stakeholders:** Reports on security posture and compliance status at milestone reviews.

---

## Data Analyst

### Role Summary
Data Analysts translate data into actionable insights to inform decisions and measure project success. They ensure the team has reliable metrics and visibility into product performance.

### Responsibilities
- Define and instrument success metrics aligned with project KPIs
- Design and maintain dashboards for key business and product signals
- Perform exploratory analyses to answer product and business questions
- Validate data integrity and flag instrumentation gaps to Developers
- Present findings and recommendations to Product Managers and Stakeholders

### Goals
- Enable data-driven decision-making across the team
- Ensure success metrics are measurable from day one
- Reduce time to insight for post-release evaluation

### Typical Communication
- Dashboard links and metric summaries shared in weekly status reports
- Analysis findings presented at sprint demos or stakeholder briefings
- Instrumentation requirements communicated to Developers via backlog items

### Interactions with Existing Roles
- **Developers:** Specifies data instrumentation requirements; validates that events and metrics are captured correctly in code.
- **Product Managers:** Collaborates on defining KPIs and success metrics; provides analysis to support prioritisation decisions.
- **Project Managers:** Supplies metric data for status reports; helps measure whether project goals are being met.
- **QA / Testing:** Verifies that tracking and analytics code is correctly implemented as part of test coverage.
- **Stakeholders:** Presents dashboards and insight summaries; translates data into business-relevant narratives.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- When scoping resources for a new project, use the [Role RACI & Responsibility Checklist](octoacme-role-raci-checklist.md) to confirm required roles.
- Use the [Cross-Functional Readiness Checklist](octoacme-cross-functional-readiness-checklist.md) to verify UX, DevOps, Security, and Analytics considerations before execution begins.

