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

### Interaction with Other Roles
- Work with **QA/Testing Lead** to define testable acceptance criteria and participate in quality reviews
- Collaborate with **Technical Lead/Architect** on design decisions and code standards
- Receive prioritized work from **Product Managers** and track progress with **Project Managers**
- Coordinate deployments with **Operations/Deployment Engineer** for production readiness

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

### Interaction with Other Roles
- Partner with **Stakeholders/Sponsors** to align on business priorities and strategic value
- Define acceptance criteria and quality expectations with **QA/Testing Lead**
- Collaborate with **Technical Lead/Architect** on feasibility and technical approach
- Coordinate with **Project Managers** on delivery timelines and risk management

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

### Interaction with Other Roles
- Escalate risks and blockers to **Stakeholders/Sponsors** for decision-making
- Track quality metrics and dependencies with **QA/Testing Lead**
- Coordinate deployment schedules with **Operations/Deployment Engineer**
- Facilitate communication between **Product Managers**, **Developers**, and **Technical Lead/Architect**

---

## QA/Testing Lead

### Role Summary
QA/Testing Leads own quality assurance, test planning, and acceptance validation. They collaborate with developers and product managers to define testability requirements and ensure features meet acceptance criteria before release.

### Responsibilities
- Design and maintain test strategy and QA approach for the project
- Create and maintain automated test suites (unit, integration, end-to-end)
- Perform manual QA and acceptance testing
- Identify quality gaps and regressions
- Participate in Definition of Done (DoD) definition to ensure testability
- Establish quality metrics and track coverage

### Goals
- Ensure high quality standards and zero critical defects in production
- Reduce cycle time through efficient, automated testing
- Catch issues early in the development process
- Enable fast feedback loops for developers

### Typical Communication
- Sprint planning and backlog refinement
- Quality status in weekly syncs
- Test plan documentation and bug reports
- Post-release quality assessments

### Interaction with Other Roles
- Work with **Developers** to define testable acceptance criteria and review test results
- Collaborate with **Product Managers** to validate acceptance criteria and define quality expectations
- Partner with **Technical Lead/Architect** on test strategy and automation approach
- Coordinate with **Operations/Deployment Engineer** on smoke test execution and production validation
- Report quality metrics to **Project Managers** for risk tracking

---

## Stakeholder/Sponsor

### Role Summary
Stakeholders and Sponsors provide business context, prioritization guidance, and escalation authority. They ensure the project aligns with business strategy and have decision-making power for scope, timeline, and resource trade-offs.

### Responsibilities
- Articulate business case and strategic alignment
- Provide prioritization and trade-off decisions
- Escalate blockers and risks to leadership
- Approve scope changes and milestone decisions
- Communicate outcomes to broader organization
- Define success criteria and business metrics

### Goals
- Ensure project delivers business value
- Maintain alignment with organizational strategy
- Enable rapid decision-making and escalation
- Support project teams with authority and resources

### Typical Communication
- Monthly stakeholder updates
- Go/no-go decision gates
- Executive briefings and announcements
- Risk escalation and trade-off reviews

### Interaction with Other Roles
- Receive project status and risk escalations from **Project Managers**
- Align on business priorities and success metrics with **Product Managers**
- Approve timeline and resource decisions affecting **Developers**, **QA/Testing Lead**, and **Operations/Deployment Engineer**
- Make final decisions on scope changes and blocking risks

---

## Technical Lead/Architect

### Role Summary
Technical Leads and Architects guide technical strategy, design decisions, and system architecture. They ensure solutions are scalable, maintainable, and aligned with technical standards and organizational practices.

### Responsibilities
- Define technical approach and architecture for features
- Review design and code for technical quality
- Identify technical risks and propose mitigations
- Mentor developers on best practices and standards
- Ensure alignment with organizational technical standards
- Lead design reviews and architectural discussions
- Support performance, security, and reliability goals

### Goals
- Deliver maintainable, scalable, and secure solutions
- Reduce technical debt and future rework
- Share knowledge and build team capability
- Ensure long-term system health and evolution

### Typical Communication
- Design review meetings
- Architecture decisions and Request for Comments (RFCs)
- Code review feedback
- Technical risk assessments
- Mentoring and knowledge-sharing sessions

### Interaction with Other Roles
- Collaborate with **Developers** on design decisions and provide architectural guidance
- Work with **QA/Testing Lead** on test strategy and quality approaches
- Partner with **Product Managers** on feasibility assessment and trade-offs
- Advise **Project Managers** on technical risks and mitigation plans
- Coordinate with **Operations/Deployment Engineer** on infrastructure and deployment requirements

---

## Operations/Deployment Engineer

### Role Summary
Operations/Deployment Engineers manage production deployments, infrastructure, monitoring, and incident response. They ensure reliable, secure releases and maintain system health in production.

### Responsibilities
- Design and maintain deployment pipelines and processes
- Manage production infrastructure and environment configurations
- Implement monitoring, logging, and alerting
- Lead incident response and post-incident reviews
- Ensure security and compliance in deployments
- Support rollback and disaster recovery procedures
- Optimize system performance and reliability

### Goals
- Enable fast, reliable, and safe deployments to production
- Maintain high system availability and performance
- Reduce mean time to recovery (MTTR) from incidents
- Ensure security, compliance, and auditability

### Typical Communication
- Release planning and deployment coordination
- Incident response and postmortems
- Infrastructure and operations updates
- Security and compliance reviews
- On-call escalations and status updates

### Interaction with Other Roles
- Coordinate with **Developers** on deployment requirements and production readiness
- Execute smoke tests designed by **QA/Testing Lead** before and after deployments
- Work with **Project Managers** on release schedules and deployment windows
- Support **Technical Lead/Architect** on infrastructure decisions and reliability improvements
- Report deployment status and incidents to **Stakeholders/Sponsors** when needed

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Reference the interaction patterns to understand cross-functional collaboration and dependencies.
