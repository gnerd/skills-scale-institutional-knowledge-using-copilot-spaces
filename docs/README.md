# OctoAcme Project Management Docs

Welcome to OctoAcme's centralized project management documentation. This README provides an overview of our processes and serves as a starting point for navigating our documentation.

---

## Summary

OctoAcme's project management methodology is built on these core principles:

- **Customer-first**: Prioritize customer value and usability in all decisions
- **Iterative delivery**: Ship small, testable increments to reduce risk and gather feedback
- **Clear ownership**: Every project has a named Project Manager (PM) and Product Lead
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback, learning, and continuous improvement

### Project Lifecycle

Our projects follow a structured lifecycle:

1. **Initiation**: Define the problem statement, identify stakeholders, and establish a high-level timeline
2. **Planning**: Break work into scope, resources, milestones, and dependencies
3. **Execution**: Build, test, review, and iterate on deliverables
4. **Release**: Deploy, verify, and announce to stakeholders
5. **Retrospective**: Capture learnings and identify next steps for improvement

### Core Roles

| Role | Key Responsibilities |
|------|---------------------|
| **Project Sponsor** | Provides strategic direction, approves budgets and resources, resolves high-level conflicts |
| **Project Manager (PM)** | Coordinates delivery, schedules, risk, and communications |
| **Product Manager (PdM)** | Defines outcomes, prioritizes backlog, and measures success |
| **Business Analyst** | Gathers requirements, conducts stakeholder interviews, ensures solution meets business needs |
| **Communications Lead** | Develops communication plans, ensures consistent messaging across stakeholders |
| **Change Manager** | Manages transition plans, stakeholder impacts, and training for new processes |
| **Quality Assurance Lead** | Oversees testing and validation, ensures process compliance, reports on quality metrics |
| **Developers** | Implement features, collaborate on design and testability |
| **Stakeholders** | Provide inputs and approvals |

For detailed role descriptions, responsibilities, and interaction patterns, see [Roles & Personas](octoacme-roles-and-personas.md).

### Communication Strategies

- **Weekly sync** between PM and Product Manager
- **Twice-weekly standups** for the delivery team (or as agreed)
- **Monthly stakeholder updates** for broader visibility
- **Ad-hoc escalations** as needed via defined escalation paths (Team → PM → Product Lead → Sponsor)

### Quality Assurance Practices

- Unit tests for new logic
- Integration tests where applicable
- End-to-end smoke tests for critical flows before release
- Security scanning in CI
- Manual QA for feature acceptance when needed
- Continuous improvement through retrospectives and action item tracking

---

## Document Index

### Process Documentation

| Document | Description |
|----------|-------------|
| [Project Management Overview](octoacme-project-management-overview.md) | Introduction to how OctoAcme runs projects, including principles, roles, and artifacts |
| [Project Initiation Guide](octoacme-project-initiation.md) | Steps to validate and authorize work, align stakeholders, and create a lightweight plan |
| [Project Planning](octoacme-project-planning.md) | Turning an approved initiative into an actionable plan and backlog |
| [Execution & Tracking](octoacme-execution-and-tracking.md) | Day-to-day execution guidance, team rhythm, and quality practices |
| [Risk Management & Communication](octoacme-risks-and-communication.md) | How to identify, manage, and communicate risks and dependencies |
| [Release & Deployment Guide](octoacme-release-and-deployment.md) | Standardized release processes to reduce risk and improve observability |
| [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) | Capturing learnings and converting them into actionable improvements |
| [Roles & Personas](octoacme-roles-and-personas.md) | Detailed definitions of roles and responsibilities used in OctoAcme projects |

### Checklists and Templates

| Document | Description |
|----------|-------------|
| [Role Assignment and Onboarding Checklist](role-assignment-onboarding-checklist.md) | Structured approach for assigning roles and onboarding new team members |
| [Communications Plan Template](communications-plan-template.md) | Template for developing project communication plans |
| [Change Management Checklist](change-management-checklist.md) | Checklist for managing organizational changes and process rollouts |
| [Quality Assurance Checklist](quality-assurance-checklist.md) | Quality standards and verification processes for deliverables and documentation |

---

## Guidance for New Team Members

### Discovering Documentation

This README serves as your central hub for all OctoAcme project management documentation. Start here and use the Document Index above to navigate to specific topics as needed.

**Recommended reading order for newcomers:**

1. Start with the [Project Management Overview](octoacme-project-management-overview.md) for a high-level understanding
2. Review [Roles & Personas](octoacme-roles-and-personas.md) to understand how different roles contribute
3. Follow the lifecycle documents in order:
   - [Project Initiation Guide](octoacme-project-initiation.md)
   - [Project Planning](octoacme-project-planning.md)
   - [Execution & Tracking](octoacme-execution-and-tracking.md)
   - [Release & Deployment Guide](octoacme-release-and-deployment.md)
   - [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
4. Reference [Risk Management & Communication](octoacme-risks-and-communication.md) as needed

### Onboarding Tips

- **Familiarize yourself with key artifacts**: Project Charter/One-pager, Roadmap, Sprint Backlog, Risk Register, and Retrospective notes
- **Understand the Definition of Done (DoD)**: Each project should have documented acceptance criteria
- **Know your escalation paths**: Team-level → PM → Product Lead → Sponsor
- **Participate in team rituals**: Daily standups, weekly syncs, sprint demos, and retrospectives

### Using These Docs

- Keep the Project Charter updated in your project repo
- Add process-specific docs into `.copilot/` if you want Copilot Spaces to use them as context
- Reference checklists in each document to ensure completeness at each phase
- Use templates provided (One-pager, Backlog Item, Release Notes, etc.) for consistency

---

## Key Artifacts

These are the standard artifacts used across OctoAcme projects:

- **Project Charter / One-pager**: Problem statement, goals, success metrics, stakeholders
- **Roadmap and Release Plan**: Timeline, milestones, and dependencies
- **Sprint/Iteration Backlog**: Prioritized work items with acceptance criteria
- **Acceptance Criteria & Definition of Done**: Quality gates for completed work
- **Risk Register**: Tracked risks with impact, likelihood, owner, and mitigation
- **Retrospective Notes and Action Items**: Learnings and improvement actions

---

## Contributing to These Docs

If you find gaps or have suggestions for improvement:

1. Open an issue describing the update needed
2. Propose content changes for review with stakeholders
3. Ensure updates align with existing process documentation
4. Submit a pull request for team review
