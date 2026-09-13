# OctoAcme Project Management Documentation

Welcome to the OctoAcme Project Management Docs. This guide provides a centralized reference for how we run projects at OctoAcme.

## Quick Overview

OctoAcme follows a structured yet iterative approach to project management built on these core principles:
- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Each project has a named Project Manager and Product Lead
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning

## Project Management Lifecycle

Our projects progress through five key phases:

1. **Initiation** – Validate business need, align stakeholders, and establish success criteria
2. **Planning** – Define scope, estimate work, identify dependencies and risks
3. **Execution & Tracking** – Build, test, review, and manage day-to-day delivery
4. **Release & Deployment** – Standardize release processes and production deployment
5. **Retrospective & Continuous Improvement** – Capture learnings and drive improvements

Throughout all phases, we maintain strong **Risk Management & Communication** practices.

## OctoAcme Project Management Overview

OctoAcme operates with a structured five-phase project lifecycle designed to deliver customer value through iterative, data-informed delivery. The lifecycle begins with **Initiation**, where new ideas are validated through a lightweight Project One-pager that confirms business need, identifies stakeholders, and establishes success metrics. This is followed by **Planning**, where approved initiatives are broken into shippable increments with prioritized backlogs, acceptance criteria, and a documented Definition of Done. The **Execution** phase emphasizes daily standups, weekly delivery syncs, and a pull request workflow with automated testing and code review. **Release** focuses on pre-deployment verification, smoke testing, and rollback planning, while **Closure & Retrospectives** capture learnings and convert them into actionable improvements for continuous iteration.

OctoAcme operates with clear role definitions that ensure accountability and collaboration. The core roles include **Project Managers** who coordinate delivery, manage schedules, risks, and stakeholder communication; **Product Managers** who define what should be built, prioritize the backlog, and measure outcomes; **Developers** who implement features with high quality and maintainability; and **QA/Testing professionals** who validate acceptance criteria and quality. This structure is supported by a regular communication cadence: daily standups focused on progress and blockers, weekly PM-to-PdM syncs, twice-weekly team standups, and monthly stakeholder updates. Escalation follows a clear path from team-level triage through the PM to the Product Lead and ultimately to the Sponsor for business-impacting issues.

Quality and risk management are embedded throughout execution. The organization maintains a Risk Register tracking impact, likelihood, ownership, and mitigation strategies, with risks reviewed weekly during syncs. Quality assurance practices include unit tests, integration tests, end-to-end smoke tests for critical flows, security scanning in CI, and manual QA when needed. Pull requests follow strict conventions—small PRs (≤400 lines when possible) with linked issues and acceptance criteria, automated testing and linting in CI, and at least one approval before merge. Deployment follows a comprehensive checklist including staging verification, post-deploy tests, and incident playbooks with rollback procedures. This combination of structured roles, regular communication, disciplined risk management, and rigorous quality practices enables OctoAcme to deliver reliably while maintaining transparency and psychological safety across the organization.

## Documentation Index

### Core Reference
- **[Project Management Overview](./octoacme-project-management-overview.md)** – Start here for a high-level understanding of OctoAcme's approach, core roles, and key artifacts.

### Phase-Specific Guides
- **[Project Initiation Guide](./octoacme-project-initiation.md)** – Steps to validate ideas, align stakeholders, and decide go/no-go for planning
- **[Project Planning Guide](./octoacme-project-planning.md)** – Breaking work into shippable increments and creating actionable backlogs
- **[Execution & Tracking Guide](./octoacme-execution-and-tracking.md)** – Managing day-to-day delivery, quality, and progress reporting
- **[Release & Deployment Guide](./octoacme-release-and-deployment.md)** – Standardizing how we ship to production
- **[Retrospective & Continuous Improvement Guide](./octoacme-retrospective-and-continuous-improvement.md)** – Capturing learnings and driving improvements

### Cross-Cutting Topics
- **[Risk Management & Communication](./octoacme-risks-and-communication.md)** – Managing risks, dependencies, and stakeholder communication throughout the project
- **[Roles & Personas](./octoacme-roles-and-personas.md)** – Definitions of key roles (Developers, Product Managers, Project Managers) and their responsibilities

## How to Use These Docs

- **Getting Started?** Read the Project Management Overview, then follow the guides corresponding to your current project phase.
- **Looking for a specific process?** Use the index above to jump to the relevant guide.
- **Contributing?** Updates to process documentation should follow the ["Add Content to Project Management Process Docs"](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) issue template.
