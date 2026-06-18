# OctoAcme Project Management Docs

> A single index with short summaries and links to process documents used across projects. Use these docs to onboard, align stakeholders, and run consistent delivery processes.

---

## Overview

OctoAcme follows a structured, lifecycle-based approach to project management that spans five key phases: **Initiation, Planning, Execution, Release, and Retrospective**. Every project begins with a lightweight one-pager that captures the problem statement, SMART objectives, success metrics, and stakeholder alignment before any planning begins. Work is only greenlit when success metrics are clear, stakeholders agree on priority, and team availability is confirmed. From there, planning converts the approved initiative into a prioritized, estimated backlog with a defined Definition of Done, a release milestone map, and a risk register — ensuring the team has a shared, actionable foundation before writing a single line of code.

Day-to-day execution is governed by a consistent team rhythm built around **15-minute daily standups**, weekly delivery syncs, and end-of-sprint demos. Work flows through a GitHub Projects board (Backlog → Ready → In Progress → In Review → QA → Done), with small pull requests (≤400 lines where possible), CI-enforced tests and linting, and at least one required approval before merging. Quality is maintained through a layered testing strategy — unit tests, integration tests, end-to-end smoke tests, and security scanning in CI — with manual QA reserved for feature acceptance. Blockers are escalated through a clear three-level path: team standup → PM/Product Lead → Sponsor.

OctoAcme operates with **three core delivery personas**: the *Project Manager*, who owns schedules, risks, and cross-team coordination; the *Product Manager*, who defines outcomes, prioritizes the backlog, and measures business value; and *Developers*, who implement features, maintain test coverage, and surface technical risks. Communication follows a predictable cadence — weekly PM/PdM syncs, twice-weekly standups, and monthly stakeholder updates — supplemented by a standardized weekly status template covering progress, next steps, risks, and decisions needed. Risk management is continuous, with a maintained risk register reviewed at every weekly sync and a formal escalation path to the security on-call team for security incidents.

After every sprint, release, or significant milestone, OctoAcme runs a **timeboxed retrospective** (45–75 minutes) structured around what went well, what could improve, and concrete action items with named owners and due dates. Those action items feed directly back into the project backlog, closing the loop between learning and delivery. This continuous improvement culture — combined with versioned process documentation, standardized templates for risk, release notes, and status updates, and centralized artifacts stored in `docs/` — ensures that institutional knowledge is accessible to all team members, reducing single-person dependency and enabling consistent, repeatable project execution across teams.

---

## Process Documents

| Document | Description |
|---|---|
| [Project Management Overview](octoacme-project-management-overview.md) | Introduction to OctoAcme's approach, core roles, key artifacts, and lifecycle phases. |
| [Project Initiation Guide](octoacme-project-initiation.md) | Steps to validate and authorize work, align stakeholders, and create a lightweight plan. |
| [Project Planning](octoacme-project-planning.md) | Turn an approved initiative into an actionable backlog, milestone map, and risk register. |
| [Execution & Tracking](octoacme-execution-and-tracking.md) | Day-to-day execution guidance including team rhythm, PR workflow, QA, and blocker escalation. |
| [Risk Management & Communication](octoacme-risks-and-communication.md) | How to identify, manage, and communicate risks, dependencies, and stakeholder updates. |
| [Release & Deployment Guide](octoacme-release-and-deployment.md) | Standardized release process covering pre-release requirements, deployment, and rollback. |
| [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) | Capture learnings and convert them into actionable improvements after each sprint or release. |
| [Roles & Personas](octoacme-roles-and-personas.md) | Definitions and responsibilities for Developers, Product Managers, and Project Managers. |
