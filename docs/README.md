# OctoAcme Project Management Docs

## Overview
OctoAcme manages work through a structured project lifecycle built around clear ownership, customer value, and iterative delivery. The framework starts with project initiation to validate the problem and stakeholders, moves into planning to turn ideas into scoped and prioritized work, and then shifts into execution, release, and retrospective phases. This approach keeps cross-functional teams aligned while making it easier to track progress, resolve dependencies, and improve delivery over time.

## Project Management Process Summary
OctoAcme emphasizes a customer-first, data-informed model of delivery. Every project is expected to define a clear problem statement, success metrics, roles, and milestones before significant work begins. Planning creates a structured backlog with acceptance criteria, estimates, owners, and a Definition of Done so the team can deliver shippable increments with confidence. Execution is managed with a visible board, daily standups, and regular reviews to address blockers, dependencies, and progress against milestones.

Quality and risk management are treated as first-class responsibilities. Teams use unit, integration, and smoke tests, run CI checks and security scans, and complete manual QA where needed before release. Risks and stakeholder communication are managed with a Risk Register, escalation paths, clear ownership, and a single source of truth for status updates. After each milestone or release, retrospectives capture what went well, what needs improvement, and which action items should be carried into the backlog.

## Core Principles
- Customer-first: prioritize user value and usability
- Iterative delivery: ship small, testable increments
- Clear ownership: define PM, product, engineering, and QA responsibilities
- Data-informed decisions: measure outcomes and adjust based on evidence
- Psychological safety: encourage feedback, learning, and candor

## Lifecycle
1. Initiation: validate the business need, stakeholders, and success metrics
2. Planning: create a roadmap, backlog, and release plan
3. Execution: build, test, track, and adapt with team rhythm
4. Release: verify with smoke tests, deploy, and communicate outcomes
5. Close & Retrospective: capture lessons learned and improve future work

## Key Roles
- Project Manager (PM): coordinates schedules, dependencies, risks, and communications
- Product Manager / Product Lead: defines value, prioritizes the backlog, and measures success
- Developers: implement features, fix issues, and maintain quality
- QA / Testing: validate quality and acceptance criteria
- Stakeholders: provide requirements, approvals, and business context

## Communication Cadence
- Weekly sync between PM and Product Lead
- Twice-weekly or agreed delivery team standups
- Monthly stakeholder updates
- Ad-hoc escalations for major blockers or incidents

## Key Artifacts
- Project charter / one-pager
- Roadmap and release plan
- Sprint or iteration backlog
- Acceptance criteria and Definition of Done
- Risk Register
- Retrospective notes and action items

## Quality Assurance and Release Practices
OctoAcme expects engineering teams to validate work with automated tests, linting, CI checks, and security scanning. For higher-risk functions, smoke tests and manual QA are used to confirm that critical workflows still behave as expected before deployment. Releases are governed by checklists, staging validation, rollback planning, and post-deploy verification to reduce operational risk.

## Documentation Index
### Getting Started
- [Project Management Overview](./octoacme-project-management-overview.md) — high-level introduction to OctoAcme's approach, roles, and artifacts
- [Roles and Personas](./octoacme-roles-and-personas.md) — role definitions and responsibilities used across the project docs

### Process Guides
- [Project Initiation](./octoacme-project-initiation.md) — how to validate and authorize project work
- [Project Planning](./octoacme-project-planning.md) — backlog creation, estimates, milestones, and planning activities
- [Execution & Tracking](./octoacme-execution-and-tracking.md) — daily workflows, team rhythm, and progress tracking
- [Release & Deployment](./octoacme-release-and-deployment.md) — deployment, smoke testing, rollback, and release notes

### Cross-Cutting Areas
- [Risk Management & Communication](./octoacme-risks-and-communication.md) — risk management, escalation paths, and stakeholder communication
- [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) — team learning and ongoing process improvement

## Recommended Reading Order
For a new team member, the best path to onboarding is:
1. [Project Management Overview](./octoacme-project-management-overview.md)
2. [Roles and Personas](./octoacme-roles-and-personas.md)
3. [Project Initiation](./octoacme-project-initiation.md)
4. [Project Planning](./octoacme-project-planning.md)
5. [Execution & Tracking](./octoacme-execution-and-tracking.md)
6. [Risk Management & Communication](./octoacme-risks-and-communication.md)
7. [Release & Deployment](./octoacme-release-and-deployment.md)
8. [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)

This README is intended to serve as a central entry point for understanding how OctoAcme runs projects and where to find detailed guidance for each process.
