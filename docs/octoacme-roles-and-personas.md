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

## Additional Personas

> **How to use these personas in team setups:** Not every team will include all of these roles. Use this section as a reference to identify which personas apply to your context, assign responsibilities clearly, and avoid gaps in coverage. When forming a team or planning a project, select the personas that match your delivery model and ensure each has a named owner.

---

## Delivery Lead

### Role Summary
The Delivery Lead coordinates day-to-day delivery across multiple teams or workstreams. They maintain cross-team schedules, surface dependencies, and ensure readiness artifacts (release notes, runbooks, go/no-go criteria) are in place before releases.

### Responsibilities
- Coordinate delivery activities across multiple teams or streams
- Maintain cross-team schedules, dependencies, and release windows
- Drive readiness checks and ensure artifacts are prepared before releases
- Identify and escalate blockers that span team boundaries
- Provide delivery status visibility to stakeholders and leadership

### Goals
- Keep cross-team delivery on track and predictable
- Reduce inter-team handoff delays and dependency risks
- Ensure teams are aligned on shared milestones and commitments

### Interactions
- Works with Project Managers to align timelines and risk mitigation
- Coordinates with Release Manager and DevOps/Platform Engineer for deployment readiness
- Partners with Product Managers to flag scope and timeline trade-offs

### Typical Communication
- Cross-team delivery syncs and dependency reviews
- Risk and dependency logs shared across teams
- Go/no-go readiness summaries before releases

---

## Technical Lead / Architect

### Role Summary
The Technical Lead or Architect provides architecture guidance and makes technical decisions for cross-cutting concerns. They ensure the system evolves in a sustainable, scalable direction and mentor Developers on design practices.

### Responsibilities
- Provide architecture guidance and make decisions on cross-cutting technical concerns
- Review designs for scalability, security, and maintainability
- Own technical debt prioritization and architectural runway
- Establish and communicate technical standards and patterns
- Identify and mitigate long-term technical risks

### Goals
- Maintain a coherent and sustainable technical architecture
- Reduce technical debt and long-term maintenance burden
- Enable Developers to make sound design decisions independently

### Interactions
- Partners with Developers on design reviews and code quality standards
- Advises Product Managers and Project Managers on technical risks and trade-offs
- Collaborates with DevOps/Platform Engineer on infrastructure and deployment architecture

### Typical Communication
- Architecture decision records (ADRs) and design documents
- Technical review sessions and code review feedback
- Periodic technical health and debt assessments

---

## UX Researcher / Designer

### Role Summary
The UX Researcher/Designer leads user research and validates product decisions with user insights. They produce wireframes, prototypes, and UX-related acceptance criteria to ensure delivered features are usable and meet user needs.

### Responsibilities
- Plan and conduct user research (interviews, usability tests, surveys)
- Produce wireframes, prototypes, and design specifications
- Define UX acceptance criteria and usability standards
- Synthesize research findings into actionable product recommendations
- Advocate for user needs throughout the product lifecycle

### Goals
- Ensure features are intuitive and meet real user needs
- Reduce usability issues discovered late in delivery
- Build a shared understanding of users across the team

### Interactions
- Collaborates with Product Managers on problem framing, acceptance criteria, and roadmap priorities
- Works with Developers and QA to ensure designs are implementable and validated
- Shares research insights with Project Managers to inform planning and prioritization

### Typical Communication
- Research reports and usability findings
- Design files and prototype links shared via collaboration tools
- Design review sessions with engineering and product

---

## DevOps / Platform Engineer

### Role Summary
The DevOps/Platform Engineer maintains CI/CD pipelines, infrastructure-as-code, and operational tooling. They own platform reliability, observability, and deployment automation to enable fast and safe delivery.

### Responsibilities
- Build and maintain CI/CD pipelines and deployment automation
- Manage infrastructure-as-code and cloud environments
- Ensure platform reliability, monitoring, and alerting are in place
- Support incident response with operational tooling and runbooks
- Collaborate on release processes and deployment verification

### Goals
- Enable frequent, low-risk deployments
- Maintain platform reliability and observability
- Reduce toil through automation and self-service tooling

### Interactions
- Works with Developers and Release Manager to streamline and verify deployments
- Escalates production issues and partners with QA Lead on release verification
- Collaborates with Technical Lead/Architect on infrastructure and platform design

### Typical Communication
- Pipeline and infrastructure status updates
- Incident runbooks and postmortems
- Deployment readiness and environment health reports

---

## Release Manager

### Role Summary
The Release Manager orchestrates release schedules, cuts releases, and verifies rollout steps. They coordinate rollback plans and communicate release status to all stakeholders to ensure smooth and predictable releases.

### Responsibilities
- Maintain the release calendar and coordinate release windows
- Orchestrate release readiness checks and go/no-go decisions
- Cut releases, verify rollout steps, and confirm successful deployment
- Coordinate rollback procedures when needed
- Communicate release status, outcomes, and post-release monitoring summaries

### Goals
- Deliver releases on schedule with minimal disruption
- Ensure all release prerequisites and rollback plans are in place
- Maintain clear stakeholder visibility throughout release windows

### Interactions
- Works closely with Project Managers, Delivery Lead, and DevOps/Platform Engineer during release windows
- Coordinates with QA Lead to confirm testing sign-off before release
- Updates Product Managers and stakeholders on release status and outcomes

### Typical Communication
- Release schedules, readiness checklists, and go/no-go decisions
- Release notes and post-release status updates
- Rollback plans and incident communications when releases encounter issues

---

## QA Lead / Test Lead

### Role Summary
The QA Lead or Test Lead defines the overall test strategy and ensures adequate test coverage for critical flows. They coordinate testing activities across teams and track quality metrics to support release gate decisions.

### Responsibilities
- Define and maintain the test strategy, including test types, coverage targets, and quality gates
- Coordinate testing activities across development teams and QA contributors
- Track and report quality metrics (defect rates, test coverage, flaky tests)
- Triage and prioritize defects with Developers and Project Managers
- Own test environment management and testing infrastructure

### Goals
- Maintain high-quality standards and prevent regressions in production
- Ensure release quality gates are met before deployment
- Reduce time to detect and resolve defects

### Interactions
- Partners with Developers to triage flaky tests and address defects efficiently
- Works with Project Managers and Release Manager to gate releases on quality criteria
- Collaborates with Product Managers to align test coverage with acceptance criteria

### Typical Communication
- Test plans and quality gate reports
- Defect triage and resolution summaries
- Sprint and release quality dashboards

---

## Data Analyst

### Role Summary
The Data Analyst defines metrics, instruments events, and analyzes post-release impact. They support Product Managers with experiments, dashboards, and data-driven recommendations to measure and improve product outcomes.

### Responsibilities
- Define success metrics and KPIs in collaboration with Product Managers
- Instrument product events and ensure correct telemetry implementation
- Build and maintain dashboards and reports for delivery and product metrics
- Analyze post-release impact and surface actionable insights
- Design and interpret experiments (A/B tests, feature flags)

### Goals
- Enable data-driven product and delivery decisions
- Ensure product changes are measurable and outcomes are understood
- Provide timely, accurate insights to stakeholders

### Interactions
- Works with Product Managers on defining success metrics and interpreting experiment results
- Collaborates with Developers to ensure correct telemetry and data instrumentation
- Shares insights with Project Managers and stakeholders to inform roadmap and delivery decisions

### Typical Communication
- Metric definitions and instrumentation specifications
- Post-release analysis reports and experiment results
- Dashboards and data summaries shared in stakeholder updates

---

## Business Analyst / Product Operations

### Role Summary
The Business Analyst or Product Operations practitioner translates stakeholder requirements into user stories and acceptance criteria. They maintain traceability between business requirements and implementation to ensure delivered solutions meet stated needs.

### Responsibilities
- Elicit, document, and prioritize stakeholder requirements
- Translate requirements into user stories, acceptance criteria, and process flows
- Maintain traceability between business requirements and delivered features
- Facilitate requirement reviews and sign-off with stakeholders
- Identify process gaps and recommend operational improvements

### Goals
- Ensure stakeholder requirements are clearly understood and accurately implemented
- Reduce ambiguity and rework caused by unclear specifications
- Bridge the gap between business expectations and technical delivery

### Interactions
- Liaises between stakeholders, Product Managers, and development teams to clarify scope and resolve ambiguities
- Works with Developers and QA Lead to review acceptance criteria and verify implementation
- Collaborates with Project Managers on scope management and change control

### Typical Communication
- User stories, acceptance criteria, and process flow documentation
- Requirement review and sign-off sessions with stakeholders
- Scope change requests and impact assessments

---

## Customer Success / Support Representative

### Role Summary
The Customer Success or Support Representative provides the voice of the customer by surfacing critical issues, feedback, and adoption signals from users. They coordinate communication for customer-impacting incidents and contribute to feature adoption plans.

### Responsibilities
- Collect, synthesize, and escalate user feedback and critical issues
- Act as a liaison between customers and the product/engineering team
- Contribute to release communications and customer-facing documentation
- Support feature adoption through training, enablement, and proactive outreach
- Monitor customer health metrics and flag at-risk accounts or recurring issues

### Goals
- Ensure customer needs and pain points are visible to the product and delivery team
- Reduce customer impact from defects and degraded experiences
- Drive successful adoption of new features and releases

### Interactions
- Works with Product Managers and Project Managers to prioritize customer-impacting issues and inform release communications
- Coordinates with Release Manager on customer notifications and rollout timing
- Provides feedback loops to Developers and QA to improve quality and usability

### Typical Communication
- Customer feedback summaries and escalation reports
- Release and incident communications to customer-facing teams
- Adoption and usage reports shared with Product Managers

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

