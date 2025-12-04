# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises. It provides clarity on accountability, collaboration patterns, and interaction details to support effective project delivery.

---

## Project Sponsor

### Role Summary
The Project Sponsor provides strategic direction, secures funding and resources, and acts as the executive champion for the project. They ensure alignment with organizational goals and resolve high-level conflicts.

### Responsibilities
- Approve project scope, budget, and major resource allocations
- Provide strategic direction and business context
- Remove organizational barriers and resolve escalated conflicts
- Champion the project with senior leadership and stakeholders
- Authorize key decisions and phase gate approvals

### Goals
- Ensure project aligns with business strategy and delivers expected value
- Secure and protect necessary resources and funding
- Maintain executive visibility and support for the project

### Typical Communication
- Monthly executive status briefings with Project Manager
- Ad-hoc escalation meetings for critical decisions
- Quarterly business reviews with stakeholders

### Interactions with Other Roles
- **Project Manager**: Receives regular status updates, provides guidance on strategic decisions, and resolves escalated issues
- **Product Owner/Manager**: Collaborates on business priorities and trade-offs between scope and resources
- **Technical Leads**: Consulted on major technical decisions with significant budget or timeline impact

### Example Scenario
> During a project review, the team identifies that delivering Feature X by the deadline requires additional engineering resources. The Project Manager escalates this to the Project Sponsor, who evaluates the business case, approves temporary contractor support, and communicates the decision to senior leadership.

---

## Business Analyst

### Role Summary
Business Analysts bridge the gap between business stakeholders and the delivery team. They gather and document requirements, conduct stakeholder interviews, and ensure the solution meets business needs.

### Responsibilities
- Elicit, analyze, and document business requirements
- Conduct stakeholder interviews and workshops
- Translate business needs into user stories and acceptance criteria
- Validate that delivered solutions meet documented requirements
- Identify process improvements and gaps

### Goals
- Ensure clear understanding of business requirements across the team
- Reduce ambiguity and rework through thorough requirement documentation
- Support successful acceptance testing and stakeholder sign-off

### Typical Communication
- Regular sessions with stakeholders to gather and validate requirements
- Collaboration with Product Owner on backlog refinement
- Requirements walkthroughs with development team

### Interactions with Other Roles
- **Project Manager**: Coordinates on scope changes and timeline impacts from requirement updates
- **Product Owner/Manager**: Partners on prioritization and ensures requirements align with product vision
- **Developers**: Clarifies requirements during implementation and reviews acceptance criteria
- **Quality Assurance Lead**: Collaborates on test case development based on requirements

### Example Scenario
> Before sprint planning, the Business Analyst conducts interviews with the sales team to understand pain points with the current reporting dashboard. They document detailed user stories and acceptance criteria, then present findings to the Product Owner and developers during backlog refinement.

---

## Communications Lead

### Role Summary
The Communications Lead develops and executes communication plans to ensure consistent, timely messaging to all project stakeholders. They coordinate updates, manage stakeholder expectations, and support change adoption.

### Responsibilities
- Develop and maintain the project communication plan
- Craft and distribute project updates, announcements, and documentation
- Ensure consistent messaging across all stakeholder groups
- Coordinate communication timing with project milestones
- Manage stakeholder feedback channels

### Goals
- Keep all stakeholders informed and aligned on project progress
- Minimize confusion through clear, consistent messaging
- Support smooth adoption of changes through proactive communication

### Typical Communication
- Regular stakeholder newsletters and status updates
- Milestone announcements and release communications
- Coordination meetings with Project Manager and Change Manager

### Interactions with Other Roles
- **Project Manager**: Aligns on communication timing, content, and escalation messaging
- **Change Manager**: Coordinates messaging for change initiatives and training announcements
- **Product Owner/Manager**: Collaborates on feature announcements and customer-facing communications
- **Technical Leads**: Reviews technical content for accuracy before stakeholder distribution

### Example Scenario
> As the team approaches a major release, the Communications Lead drafts a stakeholder announcement email, coordinates timing with the Project Manager, reviews technical details with the development lead, and aligns with the Change Manager on training resource availability messaging.

---

## Change Manager

### Role Summary
The Change Manager leads organizational change efforts, ensuring smooth transitions when new processes, tools, or systems are introduced. They focus on stakeholder readiness, training, and minimizing disruption.

### Responsibilities
- Develop change management plans and transition strategies
- Assess stakeholder impacts and readiness
- Coordinate training programs and support resources
- Monitor adoption and address resistance
- Document lessons learned from change initiatives

### Goals
- Achieve high adoption rates for new processes and tools
- Minimize disruption and productivity loss during transitions
- Build organizational change capability and resilience

### Typical Communication
- Change readiness assessments with impacted teams
- Training schedule and resource communications
- Progress updates to Project Manager and Communications Lead

### Interactions with Other Roles
- **Project Manager**: Coordinates change timelines with project milestones and resource planning
- **Communications Lead**: Partners on messaging and stakeholder communication for change initiatives
- **Product Owner/Manager**: Aligns on feature rollout impacts and user adoption strategies
- **Quality Assurance Lead**: Ensures training materials and documentation meet quality standards

### Example Scenario
> When rolling out a new project management tool, the Change Manager assesses team readiness, develops a training plan, coordinates with the Communications Lead on announcement timing, and works with the Project Manager to schedule training sessions without impacting sprint commitments.

---

## Quality Assurance Lead

### Role Summary
The Quality Assurance Lead oversees testing and validation activities, ensures process compliance, and drives quality standards across project deliverables. They report on quality metrics and coordinate with technical teams.

### Responsibilities
- Define and maintain quality standards and testing strategies
- Oversee test planning, execution, and defect management
- Ensure compliance with process and documentation standards
- Report on quality metrics and trends
- Coordinate quality gates and release readiness reviews

### Goals
- Deliver high-quality products that meet acceptance criteria
- Minimize defects escaping to production
- Establish consistent quality practices across projects

### Typical Communication
- Quality status reports to Project Manager
- Test plan reviews with development teams
- Defect triage meetings and release readiness checkpoints

### Interactions with Other Roles
- **Project Manager**: Reports on quality status and risks, coordinates on release readiness
- **Developers**: Partners on test strategy, defect resolution, and code quality practices
- **Business Analyst**: Collaborates on acceptance criteria and test case development
- **Product Owner/Manager**: Aligns on quality priorities and acceptable risk levels for releases

### Example Scenario
> Before a release, the Quality Assurance Lead reviews test coverage, identifies gaps in regression testing, coordinates with developers to address critical defects, and presents a release readiness report to the Project Manager with recommendations on go/no-go decision.

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

### Interactions with Other Roles
- **Project Manager**: Provides estimates, reports blockers, and participates in planning sessions
- **Product Owner/Manager**: Clarifies requirements, discusses trade-offs, and aligns on priorities
- **Business Analyst**: Collaborates on requirement clarification and acceptance criteria
- **Quality Assurance Lead**: Partners on testing strategy, defect resolution, and quality standards

### Example Scenario
> During implementation, a developer discovers that a requirement is ambiguous. They reach out to the Business Analyst for clarification, discuss implementation options with the Product Owner, and update the acceptance criteria before proceeding with the feature.

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

### Interactions with Other Roles
- **Project Manager**: Aligns on timeline, scope trade-offs, and resource allocation
- **Project Sponsor**: Collaborates on business priorities and escalates strategic decisions
- **Developers**: Clarifies requirements, discusses feasibility, and reviews implementations
- **Business Analyst**: Partners on requirement gathering and validation

### Example Scenario
> When customer feedback indicates a change in priorities, the Product Manager updates the roadmap, discusses timeline impacts with the Project Manager, communicates changes to the Business Analyst for requirement updates, and presents the adjusted plan to the Project Sponsor for approval.

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

### Interactions with Other Roles
- **Project Sponsor**: Escalates critical issues, provides status updates, and seeks approvals
- **Product Owner/Manager**: Collaborates on scope and timeline trade-offs
- **Communications Lead**: Coordinates stakeholder messaging and timing
- **Change Manager**: Aligns change timelines with project milestones
- **Quality Assurance Lead**: Reviews quality status and coordinates release readiness
- **Developers**: Facilitates planning, removes blockers, and tracks progress

### Example Scenario
> When a key dependency is delayed, the Project Manager assesses timeline impact, works with the Product Owner on scope adjustments, updates the risk register, coordinates with the Communications Lead on stakeholder messaging, and escalates to the Project Sponsor if executive action is needed.

---

## Role Interaction Matrix

The following matrix summarizes key interactions between roles:

| Role | Key Collaborators | Primary Touchpoints |
|------|------------------|---------------------|
| Project Sponsor | Project Manager, Product Owner | Monthly reviews, escalations, approvals |
| Business Analyst | Product Owner, Developers, QA Lead | Requirements, backlog refinement, testing |
| Communications Lead | Project Manager, Change Manager | Status updates, announcements, messaging |
| Change Manager | Communications Lead, Project Manager, QA Lead | Change plans, training, readiness |
| Quality Assurance Lead | Developers, Project Manager, Business Analyst | Testing, quality gates, defect triage |
| Developers | Product Owner, QA Lead, Business Analyst | Implementation, reviews, clarifications |
| Product Managers | Project Manager, Sponsor, Developers | Prioritization, roadmap, trade-offs |
| Project Managers | All roles | Coordination, planning, status, escalation |

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Reference the interaction details and example scenarios to understand collaboration patterns between roles.

