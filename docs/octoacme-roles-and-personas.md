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

## Program Manager

### Role Summary
The Program Manager coordinates across multiple related projects and ensures they contribute to a coherent business outcome. They reconcile competing priorities, manage inter-project dependencies, and provide leadership visibility into program-level risks, sequencing, and trade-offs.

### Responsibilities
- Coordinate timelines, milestones, and dependencies across related projects or workstreams
- Reconcile competing priorities with Product Managers, Project Managers, and leadership
- Maintain program-level plans, dependency maps, and escalation paths
- Surface resource conflicts, sequencing risks, and cross-project blockers early
- Align release timing and shared outcomes across contributing teams

### Goals
- Keep related projects aligned to shared business goals and milestones
- Reduce delivery friction caused by dependency gaps or conflicting priorities
- Provide clear program-level visibility so decisions can be made quickly

### Interactions
- Works with Project Managers to align project schedules, risk tracking, and status reporting across the program
- Partners with Product Managers and Delivery Lead to reconcile scope trade-offs and milestone commitments
- Coordinates with Release Manager and Release Coordinator when multiple teams must meet a shared release target

### Example Scenarios / Handoffs
- During release readiness for a multi-team launch, consolidates open risks from each Project Manager and hands an agreed go/no-go recommendation to the Release Manager
- When one project slips and jeopardizes a downstream dependency, escalates options and trade-offs to leadership after aligning impacted teams on recovery scenarios

### Typical Communication
- Program status summaries, dependency maps, and milestone reviews
- Cross-project escalation notes and decision briefings
- Priority and sequencing updates shared with team leads and stakeholders

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
- Escalates production issues and partners with QA Lead / Test Lead on release verification
- Collaborates with Technical Lead/Architect on infrastructure and platform design

### Typical Communication
- Pipeline and infrastructure status updates
- Incident runbooks and postmortems
- Deployment readiness and environment health reports

---

## Developer Experience (DevEx) Engineer

### Role Summary
The Developer Experience (DevEx) Engineer improves the internal tools, workflows, and documentation that developers rely on every day. They focus on reducing friction in local development, CI/CD, onboarding, and feedback loops so teams can ship changes more safely and quickly.

### Responsibilities
- Improve local development workflows, templates, and onboarding guidance
- Optimize CI/CD ergonomics, developer feedback loops, and common automation
- Identify and remove recurring friction in build, test, and review workflows
- Partner with teams to standardize internal tooling and self-service patterns
- Measure developer productivity signals and prioritize improvements accordingly

### Goals
- Reduce developer toil and waiting time across the delivery lifecycle
- Shorten the time from code change to validated feedback
- Improve onboarding speed and consistency for new engineers

### Interactions
- Works with Developers to identify high-friction tooling and workflow pain points
- Partners with DevOps/Platform Engineer on CI/CD automation, environment consistency, and self-service tooling
- Collaborates with Technical Writer/Documentation Owner to keep internal workflow documentation accurate and easy to use

### Example Scenarios / Handoffs
- Before a major release cycle, streamlines CI checks and hands updated workflow guidance to Developers so teams can resolve failures faster
- When onboarding feedback shows repeated setup issues, converts that feedback into improved templates and documentation for team leads to adopt

### Typical Communication
- Tooling improvement proposals and internal workflow updates
- CI/CD friction reports and developer productivity findings
- Onboarding guides, runbooks, and self-service documentation

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
- Coordinates with QA Lead / Test Lead to confirm testing sign-off before release
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

## Legal / Compliance Liaison

### Role Summary
The Legal / Compliance Liaison ensures product and delivery decisions account for regulatory, contractual, and policy obligations before they become release blockers. They help teams translate compliance requirements into actionable reviews, approvals, and launch constraints.

### Responsibilities
- Review proposed features and releases for legal, regulatory, and contractual implications
- Advise teams on data handling, retention, privacy, and approval requirements
- Identify compliance dependencies that must be tracked in planning and release readiness
- Coordinate required reviews, sign-offs, and evidence collection with relevant stakeholders
- Help translate obligations into practical delivery guidance and release constraints

### Goals
- Prevent late-stage compliance surprises that delay releases or create rework
- Ensure delivery plans reflect regulatory and contractual obligations early
- Improve confidence that launches meet agreed legal and compliance requirements

### Interactions
- Works with Product Managers and Business Analyst / Product Operations to review feature requirements and customer commitments
- Partners with Data Analyst and Developers when data collection or processing changes may affect compliance posture
- Coordinates with Release Manager and Project Managers to ensure required approvals are complete before release

### Example Scenarios / Handoffs
- During release readiness, reviews a new telemetry feature and hands required approval conditions back to the Project Manager for tracking before go-live
- When a customer contract introduces new obligations, translates those requirements into acceptance criteria and release checks for the delivery team

### Typical Communication
- Compliance review notes and approval requirements
- Risk summaries tied to regulatory or contractual obligations
- Release sign-off decisions and evidence requests shared with delivery leads

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
- Works with Developers and QA Lead / Test Lead to review acceptance criteria and verify implementation
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

## Product Marketing Manager (PMM)

### Role Summary
The Product Marketing Manager (PMM) owns launch messaging, positioning, and customer-facing communications for significant releases. They ensure the market narrative, enablement materials, and launch timing are aligned with the product value being delivered.

### Responsibilities
- Define product positioning, messaging, and launch narratives for releases
- Coordinate customer-facing announcements, enablement materials, and launch plans
- Align go-to-market timing with release readiness and feature scope
- Prepare FAQs, competitive talking points, and internal enablement content
- Gather launch feedback from customer-facing teams and feed it back into planning

### Goals
- Ensure launches communicate clear customer value and differentiation
- Improve readiness of sales, support, and customer-facing teams before launch
- Reduce confusion caused by mismatched release scope and external messaging

### Interactions
- Partners with Product Managers to align launch messaging with product value, scope, and target users
- Works with Change / Adoption Manager and Customer Success / Support Representative on training, FAQs, and rollout communications
- Coordinates with Release Coordinator and Technical Writer / Documentation Owner to align announcement timing, release notes, and supporting content

### Example Scenarios / Handoffs
- Before a customer-visible release, finalizes launch messaging after the Product Manager confirms scope and hands announcement content to Customer Success and Support teams
- If release scope changes late, updates external messaging and enablement materials in coordination with the Release Coordinator and Technical Writer

### Typical Communication
- Launch briefs, messaging frameworks, and release announcements
- Sales and support enablement content, FAQs, and talk tracks
- Post-launch feedback summaries shared with Product Managers and stakeholders

---

## Accessibility Lead

### Role Summary
The Accessibility Lead owns WCAG compliance and accessible design across the product. They embed accessibility standards into the development lifecycle so that features are usable by people with a range of abilities from the outset, rather than retrofitted later.

### Responsibilities
- Define and maintain the accessibility standards and WCAG compliance targets for the product
- Review designs, prototypes, and implemented features for accessibility conformance
- Conduct and coordinate accessibility audits and assistive-technology testing
- Provide guidance and training to Developers, UX Designers, and QA on accessible patterns
- Track and prioritize accessibility defects and remediation efforts
- Contribute accessibility acceptance criteria to user stories and feature specs

### Goals
- Ensure all shipped features meet the agreed WCAG conformance level
- Reduce accessibility defects discovered late in delivery or in production
- Build team capability so accessibility is considered at every stage of design and development

### Interactions
- Collaborates with UX Researcher/Designer to embed accessible design patterns into wireframes and prototypes
- Works with Developers to review implementations and provide remediation guidance
- Partners with QA Lead / Test Lead to include accessibility checks in test plans and quality gates
- Coordinates with Product Managers to prioritize accessibility work on the roadmap
- Informs Release Manager of any outstanding accessibility issues that should inform go/no-go decisions

### Typical Communication
- Accessibility audit reports and WCAG conformance summaries
- Accessibility acceptance criteria attached to user stories
- Remediation backlogs and progress dashboards shared with Product Managers and Project Managers

---

## Product Security Engineer / Security Reviewer

### Role Summary
The Product Security Engineer embeds security expertise directly into the product lifecycle. They perform threat modeling, review code and designs for vulnerabilities, and define security gates that must be met before release. See also: [Risk Management & Communication](octoacme-risks-and-communication.md).

### Responsibilities
- Conduct threat modeling for new features and significant architectural changes
- Perform security design reviews and code reviews focused on vulnerability identification
- Define and maintain security acceptance criteria and release gates
- Track and prioritize security findings and coordinate remediation with Developers
- Stay current on relevant CVEs, compliance requirements, and security best practices
- Contribute to incident response when security vulnerabilities are exploited in production

### Goals
- Prevent security vulnerabilities from reaching production
- Ensure security is a first-class requirement across all delivery work
- Reduce the cost and impact of security remediation by identifying issues early

### Interactions
- Partners with Technical Lead/Architect on architecture reviews and security-focused design decisions
- Works with Developers to remediate vulnerabilities identified in threat models and code reviews
- Collaborates with DevOps/Platform Engineer on hardening CI/CD pipelines, secrets management, and infrastructure security
- Coordinates with Release Manager to ensure security gates are satisfied before release
- Informs Project Managers and Product Managers of security risks and their impact on scope and timelines

### Typical Communication
- Threat model documents and security review findings
- Security gate checklists included in release readiness artifacts
- Vulnerability reports and remediation tracking shared with Project Managers

---

## Security Champion

### Role Summary
The Security Champion is an embedded team member who reinforces secure development practices within a delivery team. They help the team apply security guidance day to day, follow through on threat modeling outcomes, and escalate concerns to dedicated security specialists when deeper review is needed.

### Responsibilities
- Represent security considerations in planning, design, and day-to-day delivery discussions
- Help translate security requirements and threat model findings into team actions
- Coordinate follow-up on security bugs, hardening tasks, and secure coding improvements
- Promote secure development practices, awareness, and lightweight peer reviews within the team
- Escalate higher-risk findings to the Product Security Engineer / Security Reviewer when specialist support is needed

### Goals
- Make security a routine part of team delivery instead of a late-stage checkpoint
- Reduce the time between identifying a security issue and starting remediation
- Improve team ownership of secure coding and operational hygiene

### Interactions
- Works closely with Developers and Technical Lead / Architect to embed secure patterns into design and implementation
- Partners with Product Security Engineer / Security Reviewer on threat modeling, vulnerability triage, and release gates
- Coordinates with QA Lead / Test Lead and DevOps / Platform Engineer on security validation and operational hardening tasks

### Example Scenarios / Handoffs
- After a threat model review, converts the identified mitigations into backlog items and hands any high-risk questions to the Product Security Engineer for deeper review
- During release readiness, confirms team-level security fixes are complete before the Release Manager checks formal security gates

### Typical Communication
- Security action-item summaries in backlog and planning reviews
- Threat model follow-up notes and remediation status updates
- Team-facing secure development guidance and release readiness confirmations

---

## Observability & Monitoring Engineer

### Role Summary
The Observability & Monitoring Engineer ensures that systems are instrumented with meaningful metrics, logs, and traces so that teams can detect, diagnose, and resolve issues quickly. They own the observability strategy and work with Developers and DevOps to implement it.

### Responsibilities
- Define the observability strategy: metrics, logging standards, distributed tracing, and alerting thresholds
- Review and approve instrumentation included in feature work to ensure consistent, useful signals
- Build and maintain observability dashboards and alert configurations
- Collaborate on on-call runbooks and escalation paths based on alert signals
- Evaluate and evolve observability tooling and platforms
- Provide observability findings and SLO/SLI reports to stakeholders

### Goals
- Ensure every production system has sufficient instrumentation to detect and diagnose issues rapidly
- Reduce mean time to detect (MTTD) and mean time to resolve (MTTR) for incidents
- Build confidence in deployments by establishing clear SLOs and error budgets

### Interactions
- Collaborates with Developers to define and implement instrumentation requirements as part of feature delivery
- Works with DevOps/Platform Engineer to maintain and evolve the observability platform and alerting infrastructure
- Partners with Data Analyst to align on metrics definitions and ensure telemetry is accurate and consistent
- Coordinates with Release Manager to verify observability coverage as part of release readiness checks
- Supports Project Managers and Product Managers with SLO and reliability reporting

### Typical Communication
- Observability standards and instrumentation guidelines shared with development teams
- SLO/SLI dashboards and error budget reports
- Alert runbooks and on-call escalation documentation

---

## Incident Commander

### Role Summary
The Incident Commander leads response efforts during high-severity incidents. They create structure under pressure by setting priorities, coordinating responders, managing escalation paths, and ensuring that customer-impacting decisions and communications stay aligned until the incident is stabilized.

### Responsibilities
- Lead high-severity incident response and establish clear roles, priorities, and timelines
- Coordinate engineering, platform, security, and support responders during active incidents
- Drive escalation, decision-making, and status updates while keeping the response focused
- Ensure incident communications, mitigation actions, and follow-up tasks are tracked clearly
- Hand off post-incident actions, retrospectives, and improvement items once the incident is resolved

### Goals
- Restore service quickly while minimizing customer and business impact
- Reduce confusion and duplicated effort during urgent response situations
- Ensure incidents produce clear follow-up actions that improve future resilience

### Interactions
- Works with DevOps / Platform Engineer and Observability & Monitoring Engineer to assess impact, mitigation options, and system health
- Coordinates with Product Security Engineer / Security Reviewer when an incident has security implications
- Partners with Customer Success / Support Representative and Project Managers to align stakeholder and customer communications

### Example Scenarios / Handoffs
- When production alerts escalate into a sev-1 outage, assumes command, assigns responders, and hands approved customer updates to Customer Success and Support teams
- After service is restored, transfers the follow-up action list to the Project Manager and relevant leads for retrospective tracking and completion

### Typical Communication
- Incident timelines, severity declarations, and responder assignments
- Executive and stakeholder status updates during active incidents
- Post-incident summaries, action-item owners, and retrospective handoff notes

---

## Technical Writer / Documentation Owner

### Role Summary
The Technical Writer or Documentation Owner is accountable for the quality, accuracy, and completeness of end-user documentation, API references, and operational runbooks. They work closely with Developers and Product Managers to ensure documentation ships alongside features.

### Responsibilities
- Author and maintain end-user documentation, help content, and API references
- Create and update operational runbooks and incident response playbooks
- Collaborate with Developers and Product Managers to gather content and validate technical accuracy
- Define documentation standards and templates for the team
- Review release notes for clarity and completeness before publication
- Track documentation debt and prioritize updates in alignment with the roadmap

### Goals
- Ensure users and operators have accurate, up-to-date documentation to support self-service
- Reduce support burden by improving the quality and discoverability of documentation
- Ship documentation alongside features so that no release is undocumented

### Interactions
- Works with Developers and Technical Lead/Architect to document features, APIs, and system behavior accurately
- Collaborates with Product Managers to align documentation scope with release content and user needs
- Partners with Customer Success/Support Representative to identify documentation gaps based on user feedback
- Coordinates with Release Manager to include release notes and updated docs in release readiness checks. See also: [Release & Deployment](octoacme-release-and-deployment.md)
- Shares runbooks and playbooks with DevOps/Platform Engineer and the on-call team

### Typical Communication
- Documentation plans and content drafts shared for review before publication
- Release notes reviewed and approved as part of the release readiness process
- Documentation gap analysis and debt backlog shared with Product Managers and Project Managers

---

## Release Coordinator

### Role Summary
The Release Coordinator supports release logistics by tracking readiness tasks, coordinating communication across teams, and ensuring all pre-release checklist items are completed. They complement the Release Manager by owning the operational details of release preparation. See also: [Release & Deployment](octoacme-release-and-deployment.md).

### Responsibilities
- Track and chase release readiness tasks across contributing teams
- Maintain and update pre-release and post-release checklists
- Coordinate scheduling of release windows with team leads and stakeholders
- Draft and distribute release communications to internal and external audiences
- Log release outcomes, issues encountered, and lessons learned for continuous improvement
- Support rollback coordination by ensuring rollback plans are documented and understood by all participants

### Goals
- Ensure all release prerequisites are met on time with no last-minute surprises
- Reduce ambiguity around release timing, responsibilities, and communication
- Improve release reliability by maintaining thorough checklists and post-release reviews

### Interactions
- Works directly with Release Manager to track readiness status and surface blockers
- Coordinates with Project Managers and Delivery Lead to align release windows with delivery schedules
- Liaises with DevOps/Platform Engineer and QA Lead / Test Lead to confirm environment readiness and testing sign-off
- Partners with Technical Writer/Documentation Owner to ensure release notes are prepared and approved
- Communicates release timelines and status updates to Product Managers and Customer Success/Support Representative

### Typical Communication
- Release readiness checklists and status updates shared with all contributing teams
- Pre-release and post-release communications distributed to stakeholders
- Release retrospective notes and lessons-learned summaries

---

## Change / Adoption Manager

### Role Summary
The Change/Adoption Manager drives successful user adoption of new features and process changes. They develop enablement plans, coordinate training, and track adoption metrics to ensure that releases deliver their intended business value. See also: [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md).

### Responsibilities
- Develop change management and feature adoption plans for significant releases
- Coordinate training, enablement materials, and internal communications for new features
- Track adoption metrics and surface insights to Product Managers and stakeholders
- Identify and manage change resistance or adoption blockers across user groups
- Facilitate feedback loops between end users and the product team post-release
- Collaborate on rollout strategies, including phased rollouts and feature-flag plans

### Goals
- Maximize adoption of new features and process changes to realize intended business outcomes
- Reduce user friction and resistance during transitions
- Ensure teams and users are prepared before changes go live

### Interactions
- Collaborates with Product Managers to understand feature value propositions and define adoption success metrics
- Works with Customer Success/Support Representative to coordinate user-facing communications and training
- Partners with Release Manager and Release Coordinator on rollout timing and go-live communications
- Coordinates with Technical Writer/Documentation Owner to ensure enablement materials are accurate and available at launch
- Reports adoption progress and blockers to Project Managers and stakeholders

### Typical Communication
- Change management and adoption plans shared with Product Managers and Project Managers
- Enablement materials, training guides, and FAQs distributed to affected user groups
- Adoption metric reports and post-rollout feedback summaries

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
