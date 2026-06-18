# OctoAcme Project Management Docs

This README consolidates OctoAcme's project management process documents into a single reference point. It provides a brief overview of how OctoAcme runs projects and links to each process document in this folder.

---

## Project Management Processes — Overview

OctoAcme follows an iterative, customer-first project management approach structured around five lifecycle stages: **Initiation, Planning, Execution, Release, and Retrospective**. Every project begins with a lightweight one-pager that captures the problem statement, SMART goals, success metrics, stakeholder list, and initial risks. A formal decision gate ensures work only advances to planning once success metrics are clear, stakeholders are aligned, and team availability is confirmed. This structured entry point reduces wasted effort and sets a shared foundation before any development begins.

Three core personas drive delivery: the **Project Manager (PM)**, who coordinates schedules, risks, and cross-team communication; the **Product Manager (PdM)**, who owns the product vision, prioritizes the backlog, and measures outcomes; and **Developers**, who implement features, write tests, and contribute to design and estimation. Supporting roles include QA/Testing for acceptance validation and Stakeholders for approvals and input. Communication is kept lean and regular — daily standups (15 min), weekly delivery syncs, weekly PM–PdM alignment, monthly stakeholder updates, and sprint-end demos ensure transparency without overloading the team. Risks and blockers follow a clear escalation path: team-level triage → PM → Product Lead → Sponsor.

During execution, the team works from a prioritized backlog on a project board (Backlog → Ready → In Progress → In Review → QA → Done). Pull requests are kept small (≤ 400 lines where possible), must link to an issue with acceptance criteria, and require at least one approval after passing automated CI checks (tests, linting, security scanning). Quality is enforced through unit tests, integration tests, end-to-end smoke tests for critical flows, and manual QA for feature acceptance. A Risk Register is maintained throughout, with impact, likelihood, owner, and mitigation tracked and reviewed at each weekly sync.

Releases are categorized as patch, minor, or major, and all require passing CI, completed acceptance criteria, drafted release notes, and a documented rollback plan before deployment. Post-release, the team runs structured retrospectives — after every sprint, release, or significant incident — using a *what went well / what could be improved / action items* format. Action items are fed back into the project backlog with clear owners and due dates, and their impact is measured over time. This retrospective loop, combined with the team's emphasis on psychological safety and data-informed decisions, forms the backbone of OctoAcme's continuous improvement culture.

---

## Process Documents

| Document | Description |
|---|---|
| [Project Management Overview](octoacme-project-management-overview.md) | Introduction to OctoAcme's approach, core roles, key artifacts, and project lifecycle. |
| [Project Initiation Guide](octoacme-project-initiation.md) | Steps to validate and authorize work, align stakeholders, and create a lightweight plan. |
| [Project Planning](octoacme-project-planning.md) | How to turn an approved initiative into an actionable plan and backlog for delivery. |
| [Execution & Tracking](octoacme-execution-and-tracking.md) | Day-to-day execution guidance including team rhythm, PR workflows, quality, and escalation. |
| [Risks & Communication](octoacme-risks-and-communication.md) | How to identify, manage, and communicate risks, dependencies, and stakeholder updates. |
| [Release & Deployment](octoacme-release-and-deployment.md) | Standardized release process covering deployment checklists, rollback, and release notes. |
| [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) | How to run retrospectives and convert learnings into actionable improvements. |
| [Roles & Personas](octoacme-roles-and-personas.md) | Definitions of typical roles — Developers, Product Managers, Project Managers — and their responsibilities. |
