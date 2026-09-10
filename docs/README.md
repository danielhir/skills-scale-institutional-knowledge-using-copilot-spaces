# OctoAcme Project Management Documentation

Welcome to the OctoAcme project management process library. This README serves as a guide to our standardized approach for running projects, from initiation through retrospective and continuous improvement.

## About OctoAcme Project Management

OctoAcme uses a structured, customer-first approach to project delivery with clear ownership, iterative delivery cycles, and data-informed decision-making. Our process emphasizes psychological safety, collaboration across functions, and continuous learning.

OctoAcme follows a structured, lifecycle-based approach to project management grounded in customer-first principles and iterative delivery. The organization operates across five distinct phases: **Initiation**, **Planning**, **Execution**, **Release**, and **Close & Retrospective**. During Initiation, teams validate business need and align stakeholders using a lightweight Project One-pager that captures the problem statement, success metrics, and initial resource requirements. Once approved, the Planning phase breaks work into shippable increments with prioritized backlogs, acceptance criteria, and a defined Definition of Done. This ensures that execution teams begin with clarity on scope, dependencies, and release milestones before any code is written.

The organization clarifies roles and responsibilities across three core personas: **Product Managers** (who define what to build and prioritize outcomes), **Project Managers** (who coordinate delivery, manage risks, and maintain transparency), and **Developers** (who implement features, maintain quality, and collaborate on design). This clear ownership structure is reinforced through a consistent communication cadence: weekly syncs between PM and Product Lead, twice-weekly standups for delivery teams, and monthly stakeholder updates. Risk management is continuous—teams maintain a Risk Register throughout the project lifecycle, escalating blockers through three levels: team-level triage in standups, PM escalation to Product Leadership, and sponsor-level escalation for business-impacting issues.

Quality and observability are embedded throughout execution and release. Teams follow a pull request workflow with small, reviewable PRs (≤400 lines when possible), automated CI testing and linting, and a requirement for at least one approval before merge. Pre-release validation includes unit tests, integration tests, end-to-end smoke tests, and security scanning. Releases are managed through standardized deployment checklists with pre-release requirements, staging validation, and rollback playbooks to mitigate production risk. Finally, OctoAcme closes the loop through retrospectives after each sprint or milestone, capturing learnings and tracking action items to continuously improve processes and team performance.

### Core Principles
- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Ship small, testable increments
- **Clear ownership**: Every project has named roles and responsibilities
- **Data-informed**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning

## Quick Navigation

### By Project Lifecycle Phase

**1. Initiation**
- [Project Initiation Guide](octoacme-project-initiation.md) — Validate need, identify stakeholders, make go/no-go decision

**2. Planning**
- [Project Planning](octoacme-project-planning.md) — Break work into shippable increments, define dependencies and timeline

**3. Execution & Tracking**
- [Execution & Tracking](octoacme-execution-and-tracking.md) — Day-to-day workflows, quality standards, reporting metrics

**4. Release & Deployment**
- [Release & Deployment Guide](octoacme-release-and-deployment.md) — Pre-release requirements, deployment checklist, rollback procedures

**5. Close & Improve**
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) — Capture learnings and drive improvements

### By Role
- [Project Management Overview](octoacme-project-management-overview.md) — Core roles, artifacts, and communication cadence
- [Roles and Personas](octoacme-roles-and-personas.md) — Detailed descriptions of developers, product managers, and project managers

### By Topic
- [Risk Management & Communication](octoacme-risks-and-communication.md) — Risk register, escalation paths, stakeholder communication templates

## Key Artifacts at Each Stage
- **Initiation**: Project One-pager, Stakeholder list, Risk list
- **Planning**: Prioritized backlog, Release plan, Definition of Done
- **Execution**: Sprint backlog, PR reviews, Status reports
- **Release**: Release notes, Deployment checklist, Smoke tests
- **Retrospective**: Learnings document, Action items

## Getting Started

1. **New to OctoAcme?** Start with the [Project Management Overview](octoacme-project-management-overview.md)
2. **Initiating a new project?** Read the [Project Initiation Guide](octoacme-project-initiation.md)
3. **Looking for a specific process?** Use the navigation above or search this directory

## How to Use These Docs
- Keep process artifacts (checklists, templates) in the repo root or project board
- Add context-specific guidance to `.copilot/` if using Copilot Spaces
- Update docs as processes evolve and capture learnings from retrospectives

---

*For issues, questions, or suggestions about these processes, use the [Process Doc Update issue template](.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) to propose improvements.*
