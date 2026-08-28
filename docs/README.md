# OctoAcme Project Management Documentation

Welcome to the OctoAcme Project Management process documentation. This folder contains comprehensive guides for running projects at OctoAcme, from initial concept through delivery and retrospective learning.

## Quick Overview

OctoAcme follows a structured project lifecycle designed to maximize customer value, ensure clear ownership, and foster continuous improvement:

1. **Initiation** - Validate the business need and align stakeholders
2. **Planning** - Break work into shippable increments and define success metrics
3. **Execution** - Build, test, and iterate with daily standups and regular reviews
4. **Release** - Deploy with confidence using proven pre-release and deployment checklists
5. **Close & Retrospective** - Capture learnings and convert them into actionable improvements

## Core Principles

- **Customer-first** - Prioritize customer value and usability
- **Iterative delivery** - Deliver small, testable increments
- **Clear ownership** - Each project has a named Project Manager (PM) and Product Lead
- **Data-informed decisions** - Measure impact and iterate based on evidence
- **Psychological safety** - Encourage feedback and learning

## OctoAcme Project Management Process Summary

OctoAcme follows a structured, lifecycle-based approach to project management that emphasizes customer value, iterative delivery, and clear ownership. The process is organized into five key phases: **Initiation**, **Planning**, **Execution**, **Release**, and **Close & Retrospective**. During Initiation, teams validate business need and create a lightweight Project One-pager with success metrics, stakeholder alignment, and resource estimates. This decision gate ensures that only prioritized work moves forward. Once approved, the Planning phase breaks work into shippable increments, establishes acceptance criteria, identifies dependencies and risks, and defines the team's Definition of Done. This structured approach ensures alignment before execution begins.

Execution and daily delivery are governed by clear team rhythms and quality standards. OctoAcme teams conduct daily standups (15 minutes) focused on progress and blockers, weekly delivery syncs to track metrics and flag risks, and regular demos at sprint or milestone endpoints. Developers follow a Pull Request workflow with small, reviewable changes (≤400 lines), automated CI testing and linting, and at least one approval before merge. Quality is maintained through unit and integration tests, end-to-end smoke tests for critical flows, security scanning in CI, and manual QA for feature acceptance. Progress is tracked using GitHub Projects with columns for Backlog, Ready, In Progress, In Review, QA, and Done, and velocity and burndown metrics inform continuous improvement.

OctoAcme defines clear roles and responsibilities to eliminate ambiguity. **Developers** implement features and collaborate on design and testing; **Product Managers (PdM)** define outcomes, prioritize the backlog, and measure success; **Project Managers (PM)** coordinate delivery, manage risks and schedules, and facilitate communication; and **QA/Testing** validate acceptance criteria and quality. A weekly PM–PdM sync and twice-weekly team standups ensure coordination and rapid escalation of blockers. Risk management is central to the process: teams maintain a Risk Register throughout execution, identify dependencies during planning, escalate blockers through three levels (team → PM → Product Lead → Sponsor), and communicate status via standardized weekly templates.

Release and continuous improvement close the lifecycle. Before deployment, teams verify all acceptance criteria are met, CI passes, security scans are complete, rollback plans are documented, and release notes are drafted. Post-deployment, automated smoke tests and post-release verification confirm success. After each sprint, release, or milestone, teams conduct retrospectives to capture learnings and prioritize 2–3 action items for improvement. This emphasis on measurement, feedback loops, and blameless learning ensures that OctoAcme projects deliver value while building organizational capability over time.

## Process Documents

### Foundational

- [Project Management Overview](./octoacme-project-management-overview.md) - Start here for a high-level introduction to roles, artifacts, and lifecycle
- [Roles and Personas](./octoacme-roles-and-personas.md) - Understand the responsibilities and communication patterns for Developers, Product Managers, and Project Managers

### By Project Phase

- [Project Initiation Guide](./octoacme-project-initiation.md) - Steps to validate ideas and authorize work
- [Project Planning](./octoacme-project-planning.md) - Turn approved initiatives into actionable plans and backlogs
- [Execution & Tracking](./octoacme-execution-and-tracking.md) - Manage day-to-day delivery and progress tracking
- [Release & Deployment Guide](./octoacme-release-and-deployment.md) - Standardize releases and reduce deployment risk
- [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) - Capture learnings and drive improvements

### Cross-Cutting Concerns

- [Risk Management & Communication](./octoacme-risks-and-communication.md) - Identify, manage, and communicate risks and dependencies

## Getting Started

**New to OctoAcme projects?** Read the [Project Management Overview](./octoacme-project-management-overview.md).

**Starting a new project?** Follow the [Project Initiation Guide](./octoacme-project-initiation.md).

**Already in execution?** Refer to [Execution & Tracking](./octoacme-execution-and-tracking.md) for daily workflows.

**Preparing for release?** Review the [Release & Deployment Guide](./octoacme-release-and-deployment.md).

**Running a retrospective?** See [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md).

**Handling risks and dependencies?** Consult [Risk Management & Communication](./octoacme-risks-and-communication.md).
