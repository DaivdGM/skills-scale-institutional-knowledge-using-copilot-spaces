# OctoAcme Project Management Docs

Welcome to the OctoAcme project management documentation hub. This collection of guides standardizes how we run projects, manage stakeholders, and deliver value iteratively.

## Quick Start

If you're new to OctoAcme projects, start with [OctoAcme Project Management Overview](octoacme-project-management-overview.md) to understand our core principles, roles, and lifecycle.

## Core Principles

OctoAcme projects are built on five principles:
- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Each project has a named Project Manager and Product Lead
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning

## Project Management Lifecycle

OctoAcme projects follow a structured lifecycle with clear phases and decision gates:

1. **Initiation** – Validate business need, align stakeholders, define success criteria
2. **Planning** – Break work into shippable increments, define dependencies and milestones
3. **Execution** – Build, test, review, and iterate with daily standups and weekly syncs
4. **Release** – Deploy to production with safety checks and rollback plans
5. **Close & Retrospective** – Capture learnings and continuous improvements

## Process Overview

OctoAcme follows a structured, lifecycle-based approach to project management that emphasizes customer value, iterative delivery, and clear ownership. The process begins with **Initiation**, where teams validate business need and align stakeholders around a lightweight Project One-pager that defines the problem, objectives, success metrics, and initial risks. Once stakeholders approve the initiative, the **Planning** phase breaks work into shippable increments with prioritized backlogs, acceptance criteria, and defined dependencies.

During **Execution**, teams operate with a disciplined rhythm through twice-weekly standups, weekly PM/Product Lead syncs, and monthly stakeholder updates. Work flows through a GitHub Projects board with clear columns (Backlog → Ready → In Progress → In Review → QA → Done). Pull requests are kept small (≤400 lines when possible), require at least one approval, and must pass automated tests and linting. Three core personas coordinate delivery: **Project Managers** (who manage schedules, risks, and communications), **Product Managers** (who define outcomes and prioritize work), and **Developers** (who implement features and collaborate on quality). Blockers escalate through three levels: team-level (daily standup) → product-level (PM escalates) → sponsor-level (for business-impacting issues).

**Release** decisions require passing CI and security scans, drafted release notes, and a documented rollback plan. Teams run post-deployment verifications and announce releases to stakeholders and support. Quality and risk management are embedded throughout: unit tests for new logic, integration and end-to-end smoke tests for critical flows, security scanning in CI, and a Risk Register that tracks threats by impact, likelihood, and mitigation. Finally, OctoAcme closes projects with blameless **Retrospectives** that capture learnings and convert them into actionable improvements tracked in the backlog with owners and due dates.

## Documentation Index

### Getting Started
- [Project Management Overview](octoacme-project-management-overview.md) – Foundational guide to OctoAcme approach, roles, and key artifacts
- [Roles and Personas](octoacme-roles-and-personas.md) – Definitions of typical roles and responsibilities

### By Project Phase
- [Project Initiation Guide](octoacme-project-initiation.md) – Steps to validate and authorize work
- [Project Planning](octoacme-project-planning.md) – Turn initiatives into actionable backlogs and delivery plans
- [Execution & Tracking](octoacme-execution-and-tracking.md) – Day-to-day execution, team rhythm, and progress tracking
- [Release & Deployment Guide](octoacme-release-and-deployment.md) – Standardized release processes and safety checks
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) – Capture learnings and drive improvements

### Cross-Cutting
- [Risk Management & Communication](octoacme-risks-and-communication.md) – Risk registers, stakeholder communication, and escalation paths

## How to Use These Docs

- **For new team members**: Start with the Overview, then jump to the phase relevant to your current project
- **For project kickoffs**: Use Initiation and Planning guides as a checklist
- **For team leads**: Reference Execution & Tracking and Risk Management for governance
- **For process improvements**: Check Retrospective & Continuous Improvement for structured approaches

## Contributing

To suggest updates or additions to these process documents, please create an issue using the [Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) template.
