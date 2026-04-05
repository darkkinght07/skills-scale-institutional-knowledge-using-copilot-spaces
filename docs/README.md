# OctoAcme Project Management Docs

This folder contains the official process documentation for OctoAcme's project management practices. OctoAcme applies a structured, iterative approach to project management that spans the full lifecycle of a product initiative — from ideation through deployment and continuous improvement. The process begins with **Initiation**, where teams validate business needs, define measurable outcomes, identify stakeholders, and create a Project One-pager to ensure alignment before committing significant resources. In the **Planning phase**, approved initiatives are broken down into shippable increments with prioritized backlogs, clear acceptance criteria, scope estimates, dependency mapping, and a Definition of Done that provides a clear roadmap for execution.

**Execution & Tracking** follows agile rhythms with daily standups (15 min), weekly delivery syncs, and sprint-based iteration. Teams use GitHub Projects with standardized board columns (Backlog, Ready, In Progress, In Review, QA, Done), maintain small pull requests (≤ 400 lines), require automated testing and linting in CI, and enforce code review approvals before merging. A robust escalation process handles blockers at three levels: team-level triage, PM escalation to the Product Lead, and sponsor-level escalation for business-impacting issues. **Quality & Testing** is embedded throughout: unit tests for new logic, integration tests where applicable, end-to-end smoke tests for critical flows, security scanning in CI, and manual QA for feature acceptance.

The **Release & Deployment** phase includes standardized pre-release checklists, staged deployments (staging first, then production), post-deploy verification, and well-documented rollback procedures. **Retrospectives** are held after each sprint or milestone to capture learnings and drive continuous improvement through tracked action items. **Risk Management & Communication** is proactive, with regular risk register updates, clear escalation paths, and consistent stakeholder updates delivered through weekly syncs and release announcements.

Core **Roles & Personas** span Engineering (Individual Contributors, Tech Leads), Product (Product Manager, Product Owner), Design (UX Designer), QA (QA Engineer), and Leadership (Engineering Manager, Sponsor/Exec Stakeholder). Each role carries defined responsibilities across the project lifecycle, ensuring clear ownership of decisions, quality gates, and stakeholder communication at every stage.

---

## Table of Contents

| Document | Description |
|---|---|
| [Project Management Overview](octoacme-project-management-overview.md) | High-level overview of OctoAcme's end-to-end project management process |
| [Project Initiation](octoacme-project-initiation.md) | Business validation, stakeholder identification, and Project One-pager |
| [Project Planning](octoacme-project-planning.md) | Backlog creation, estimation, dependency mapping, and Definition of Done |
| [Execution & Tracking](octoacme-execution-and-tracking.md) | Agile ceremonies, GitHub Projects workflow, PR standards, and escalation |
| [Risks & Communication](octoacme-risks-and-communication.md) | Risk register, escalation paths, and stakeholder communication cadences |
| [Release & Deployment](octoacme-release-and-deployment.md) | Pre-release checklists, staged deployments, and rollback procedures |
| [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) | Sprint/milestone retrospectives and action item tracking |
| [Roles & Personas](octoacme-roles-and-personas.md) | Core roles, responsibilities, and ownership across the project lifecycle |
