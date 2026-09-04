# OctoAcme Project Management Process Docs

Welcome to the OctoAcme Project Management guide. This repository contains comprehensive documentation for running successful projects at OctoAcme.

## Overview

OctoAcme follows a structured yet flexible project management approach grounded in five core principles: **customer-first delivery**, **iterative development**, **clear ownership**, **data-informed decisions**, and **psychological safety**. This methodology applies across all cross-functional projects that deliver product features, services, or integrations.

Our process emphasizes lightweight documentation—starting with a Project One-pager that validates business need and success metrics before moving forward—and keeping key artifacts (charters, backlogs, risk registers) accessible and regularly updated within project repositories. Each project is stewarded by a Project Manager (PM) who coordinates delivery and communications, paired with a Product Manager (PdM) who defines outcomes and measures success. This dual-leadership model, supported by developers, QA/testing teams, and stakeholders, creates clear accountability while maintaining collaborative decision-making.

Execution and delivery are guided by a disciplined workflow centered on small, testable increments. Teams operate on a cadence of daily standups (15 minutes), weekly delivery syncs, and sprint-based planning, using project boards to visualize work through defined stages. Pull requests are kept small (≤400 lines when possible), include issue links and acceptance criteria, and require automated CI checks and approval before merging. Quality assurance is embedded throughout via unit tests, integration tests, end-to-end smoke tests, and security scanning. Risk and stakeholder communication are continuous responsibilities, with regular updates, structured retrospectives, and an emphasis on learning and continuous improvement.

## Project Lifecycle

OctoAcme projects follow a five-phase lifecycle:

1. **Initiation** - Validate business need, align stakeholders, define success metrics
2. **Planning** - Break work into shippable increments, identify dependencies and risks
3. **Execution** - Build, test, review, and iterate with disciplined workflows
4. **Release** - Deploy to production with confidence and clear communication
5. **Retrospective** - Capture learnings and drive continuous improvement

## Documentation Index

### Core Reference
- **[Project Management Overview](octoacme-project-management-overview.md)** - Start here for principles, roles, and high-level lifecycle overview

### Phase-Specific Guides
- **[Project Initiation Guide](octoacme-project-initiation.md)** - Steps to validate and authorize new work, align stakeholders, create lightweight plans
- **[Project Planning](octoacme-project-planning.md)** - Creating actionable plans, prioritized backlogs, and release timelines
- **[Execution & Tracking](octoacme-execution-and-tracking.md)** - Day-to-day management, workflows, quality assurance, and blocker escalation
- **[Release & Deployment Guide](octoacme-release-and-deployment.md)** - Standardized release process, deployment checklist, and rollback procedures
- **[Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)** - Running retrospectives and converting learnings into actionable improvements

### Supporting Resources
- **[Risk Management & Communication](octoacme-risks-and-communication.md)** - Risk identification, mitigation tracking, and stakeholder communication templates
- **[OctoAcme Personas](octoacme-roles-and-personas.md)** - Detailed role definitions, responsibilities, and typical communication patterns

## Quick Reference by Role

### Project Managers
**Primary documents:** Execution & Tracking, Risk Management & Communication
- Day-to-day coordination and progress tracking
- Risk identification, escalation, and mitigation
- Stakeholder communication and status reporting
- Facilitate planning, retrospectives, and key meetings

### Product Managers
**Primary documents:** Project Initiation, Project Planning
- Define problem statements and success metrics
- Prioritize roadmap and backlog
- Validate solutions and measure outcomes
- Collaborate with stakeholders on trade-offs

### Developers
**Primary documents:** Project Planning (Definition of Done), Execution & Tracking
- Implement features meeting acceptance criteria
- Write and maintain tests and documentation
- Participate in code reviews and design discussions
- Help identify technical risks and propose mitigations

### QA / Testing
**Primary documents:** Project Planning (quality section), Execution & Tracking, Release & Deployment
- Validate quality and acceptance criteria
- Plan and execute test strategies
- Identify and triage defects
- Coordinate smoke tests and post-deployment verification

## How to Use This Documentation

1. **New Project?** → Start with [Project Initiation Guide](octoacme-project-initiation.md)
2. **Planning Phase** → Reference [Project Planning](octoacme-project-planning.md)
3. **Active Execution** → Use [Execution & Tracking](octoacme-execution-and-tracking.md) and [Risk Management & Communication](octoacme-risks-and-communication.md)
4. **Ready to Release** → Follow [Release & Deployment Guide](octoacme-release-and-deployment.md)
5. **Sprint/Release Complete** → Run [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
6. **Need Role Clarity** → Check [OctoAcme Personas](octoacme-roles-and-personas.md)

## Key Artifacts by Phase

| Phase | Key Artifacts |
|-------|---------------|
| **Initiation** | Project One-pager, Stakeholder List, Risk List, Resource Plan |
| **Planning** | Prioritized Backlog, Release Plan, Risk Register, Definition of Done |
| **Execution** | Sprint Backlog, PRs with Acceptance Criteria, Risk Register (updated), Status Reports |
| **Release** | Release Notes, Deployment Checklist, Rollback Plan, Post-Deploy Verification |
| **Retrospective** | Retrospective Notes, Action Items, Velocity/Burndown Data, Lessons Learned |

## Communication Cadence

- **Daily:** Team standups (15 minutes) — progress, blockers, dependencies
- **Weekly:** PM + PdM sync and delivery team sync — progress, risks, decisions
- **Bi-weekly/Sprint Basis:** Sprint planning and reviews
- **Monthly:** Stakeholder updates
- **As-needed:** Escalations and incident communications

---

For questions or to propose updates to these process docs, please use the [Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) issue template.
