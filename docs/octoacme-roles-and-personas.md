# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises. Each persona includes a role summary, responsibilities, goals, typical communication patterns, and notes on how the role interacts with other personas.

See also:
- [RACI Template](octoacme-raci-template.md) — assign Responsible, Accountable, Consulted, and Informed owners across activities
- [Stakeholder Mapping Template](octoacme-stakeholder-mapping.md) — identify and manage stakeholder engagement
- [Decision Log Template](octoacme-decision-log.md) — track key decisions and their rationale
- [Escalation Path Quick Reference](octoacme-escalation-path.md) — understand how to escalate blockers and risks
- [Role Onboarding Checklist](octoacme-role-onboarding-checklist.md) — guide new team members through their first weeks

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
- **Product Owner / Product Manager**: Clarify requirements, acceptance criteria, and scope trade-offs.
- **Project Manager**: Report progress, flag blockers, and provide estimates.
- **Quality Lead**: Collaborate on test coverage, bug triage, and release readiness.
- **Agile Coach / Scrum Master**: Participate in agile ceremonies; raise process impediments.

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
- **Project Sponsor**: Align roadmap priorities and escalate funding or scope decisions.
- **Product Owner**: In teams where both roles exist, the Product Manager sets strategic vision while the Product Owner manages day-to-day backlog.
- **Project Manager**: Share roadmap context; coordinate dependencies and delivery timelines.
- **Stakeholders**: Gather feedback, validate priorities, and communicate product direction.

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
- **Project Sponsor**: Escalate critical risks, scope changes, and resource needs; obtain approvals.
- **Product Manager / Product Owner**: Align on priorities, scope changes, and release dates.
- **Agile Coach / Scrum Master**: Collaborate on process health; share impediment status.
- **Quality Lead**: Coordinate release readiness criteria and sign-off gates.
- **Stakeholders**: Provide regular status updates and manage expectations.

---

## Project Sponsor

### Role Summary
The Project Sponsor is an executive or senior leader who champions the project, secures funding, removes organizational obstacles, and provides strategic direction. The sponsor is the ultimate decision-maker for significant scope, budget, or timeline changes.

### Responsibilities
- Approve project charter, budget, and high-level scope
- Remove organizational blockers that the Project Manager cannot resolve
- Champion the project within the organization and secure executive support
- Review and approve major milestone completions
- Make final calls on escalated scope, budget, or priority trade-offs

### Goals
- Ensure the project delivers expected business value
- Protect the team from organizational interference
- Maintain executive alignment and support

### Typical Communication
- Monthly or milestone-based executive briefings from the Project Manager
- Escalation reviews when critical risks or blockers arise
- Sign-off on project charters, major scope changes, and releases

### Interactions with Other Roles
- **Project Manager**: Primary point of contact; receives status reports, escalations, and requests for decisions.
- **Product Manager / Product Owner**: Aligns on strategic product direction and priority trade-offs.
- **Stakeholders**: Represents the project at the executive level; aligns senior stakeholder expectations.
- **Agile Coach / Scrum Master**: May be briefed on process health at a high level.

### Decision Rights
- **Decides**: Budget changes, major scope adjustments, resource additions, project continuation/cancellation.
- **Consults**: Roadmap prioritization, release timing, team structure.
- **Informed**: Sprint outcomes, detailed risk registers, day-to-day delivery status.

---

## Product Owner

### Role Summary
The Product Owner (PO) acts as the voice of the customer within the delivery team. They own and prioritize the product backlog, define acceptance criteria, and make day-to-day decisions on scope trade-offs to maximize delivered value.

### Responsibilities
- Own and prioritize the product backlog based on business value
- Write and refine user stories with clear acceptance criteria
- Collaborate with developers during sprint planning and grooming
- Accept or reject completed work against acceptance criteria
- Communicate backlog priorities to stakeholders and the Project Manager
- Make scope trade-off decisions within the sprint boundary

### Goals
- Ensure the team always works on the highest-value items
- Minimize waste through clear, well-refined backlog items
- Maintain a shared understanding of priorities across the team

### Typical Communication
- Sprint planning, backlog grooming, and sprint review sessions
- Written acceptance criteria in stories and tasks
- Regular check-ins with Stakeholders and Product Manager on priorities

### Interactions with Other Roles
- **Developers**: Primary day-to-day collaboration partner; refine stories, answer questions, accept work.
- **Product Manager**: Align on strategic priorities and translate them into backlog items.
- **Project Manager**: Share sprint scope, flag risks to timeline, and coordinate cross-team dependencies.
- **Quality Lead**: Review test coverage expectations and participate in acceptance testing.
- **Agile Coach / Scrum Master**: Partner on backlog health and agile ceremony effectiveness.
- **Stakeholders**: Gather requirements, share backlog priorities, and manage expectations.

### Decision Rights
- **Decides**: Story priority, acceptance of completed work, backlog ordering.
- **Consults**: Release scope, cross-team dependencies.
- **Informed**: Technical approach decisions, infrastructure changes.

---

## Agile Coach / Scrum Master

### Role Summary
The Agile Coach or Scrum Master serves the team by facilitating agile ceremonies, removing impediments, and fostering continuous improvement. They coach team members and the organization on agile principles and practices.

### Responsibilities
- Facilitate sprint planning, standups, retrospectives, and sprint reviews
- Identify and remove impediments that block the delivery team
- Coach the team on agile values, principles, and practices
- Shield the team from external distractions and scope creep during a sprint
- Track team velocity, cycle time, and other delivery metrics
- Guide the organization in adopting and scaling agile practices
- Support the Product Owner in backlog management and refinement techniques

### Goals
- Enable a high-performing, self-organizing team
- Continuously improve team processes and delivery flow
- Build organizational agile maturity

### Typical Communication
- Daily standups and retrospective facilitation
- Impediment logs and team health dashboards
- Coaching conversations and training sessions

### Interactions with Other Roles
- **Developers**: Remove blockers; facilitate agile ceremonies; coach on engineering practices.
- **Product Owner**: Support backlog refinement; ensure stories are sprint-ready.
- **Project Manager**: Share impediment status and team capacity; collaborate on delivery risk.
- **Project Sponsor**: Escalate systemic organizational blockers requiring executive intervention.
- **Quality Lead**: Coordinate quality practices within the agile process (e.g., definition of done).

### Decision Rights
- **Decides**: Facilitation approach, agile ceremony format, process improvement experiments.
- **Consults**: Team composition, tooling choices, delivery metrics.
- **Informed**: Business priorities, budget constraints.

---

## Quality Lead

### Role Summary
The Quality Lead owns the test strategy and quality assurance process for a project. They ensure that deliverables meet defined quality standards and coordinate release readiness and sign-off.

### Responsibilities
- Define and maintain the overall test strategy (unit, integration, regression, UAT)
- Review acceptance criteria for testability
- Coordinate and execute test cycles; track defects and resolution
- Manage the definition of done as it relates to quality gates
- Sign off on release readiness from a quality perspective
- Identify and communicate quality risks to the Project Manager
- Champion quality practices across the team (e.g., shift-left testing)

### Goals
- Prevent defects from reaching production
- Build confidence in each release through rigorous testing
- Reduce rework and cost of quality over time

### Typical Communication
- Test plan and test results reports shared with Project Manager and Product Owner
- Defect reports and bug triage sessions with Developers
- Release readiness sign-off communicated to the Project Manager and Project Sponsor

### Interactions with Other Roles
- **Developers**: Collaborate on test automation, defect triage, and code quality practices.
- **Product Owner**: Validate acceptance criteria are testable; participate in acceptance testing.
- **Project Manager**: Report quality status, flag quality risks, and confirm release readiness.
- **Agile Coach / Scrum Master**: Integrate quality practices into the agile process and definition of done.
- **Stakeholders**: Facilitate UAT sessions; collect and action stakeholder feedback on quality.

### Decision Rights
- **Decides**: Test strategy, quality gate criteria, release readiness (quality dimension).
- **Consults**: Acceptance criteria, risk mitigation for quality issues.
- **Informed**: Business priorities, sprint scope changes.

---

## Stakeholder

### Role Summary
Stakeholders are individuals or groups with a vested interest in the project's outcomes. They represent business, technical, or customer interests and provide input on requirements, deliverables, and changes. Stakeholders may be internal (e.g., business units) or external (e.g., customers, partners).

### Responsibilities
- Provide input on requirements and priorities during discovery and planning
- Review and approve deliverables, demos, and release content as requested
- Attend sprint reviews and provide actionable feedback
- Raise concerns, risks, or change requests through defined channels
- Stay informed on project status and act on escalations as needed

### Goals
- Ensure the project delivers outcomes aligned to their needs
- Maintain visibility into progress and risks
- Provide timely input to avoid delivery delays

### Typical Communication
- Sprint reviews and demo sessions
- Monthly or milestone-based status updates from the Project Manager
- Ad-hoc reviews when deliverables require stakeholder input or sign-off

### Interactions with Other Roles
- **Project Manager**: Primary channel for status updates, escalations, and change requests.
- **Product Owner / Product Manager**: Provide requirements and validate that backlog priorities reflect business needs.
- **Quality Lead**: Participate in user acceptance testing (UAT) and provide feedback.
- **Project Sponsor**: Escalate concerns that require executive-level attention or decisions.

### Decision Rights
- **Decides**: Acceptance of deliverables within their domain; change request priorities from their business area.
- **Consults**: Roadmap priorities, risk tolerance for their area.
- **Informed**: Sprint progress, release content, risk status.

---

## Role Interaction Matrix

The table below summarizes how each role typically interacts with the others. Cells describe the nature of the interaction.

| | Project Sponsor | Product Manager | Product Owner | Project Manager | Agile Coach / Scrum Master | Quality Lead | Developer | Stakeholder |
|---|---|---|---|---|---|---|---|---|
| **Project Sponsor** | — | Strategic alignment | Strategic alignment | Receives escalations & status | Briefed on process health | Informed of release sign-off | — | Executive alignment |
| **Product Manager** | Escalates priorities & funding | — | Sets strategic vision; delegates backlog | Shares roadmap & dependencies | — | — | Defines feature specs | Gathers & validates requirements |
| **Product Owner** | — | Executes on strategy | — | Shares sprint scope & flags risks | Partners on backlog health | Reviews acceptance criteria | Primary collaboration partner | Gathers requirements; shares priorities |
| **Project Manager** | Escalates blockers & scope | Aligns on priorities | Aligns on sprint scope | — | Shares impediment status | Coordinates release readiness | Monitors progress | Provides status updates |
| **Agile Coach / Scrum Master** | Escalates systemic blockers | — | Supports backlog refinement | Collaborates on delivery risk | — | Integrates quality in DoD | Removes blockers; facilitates ceremonies | — |
| **Quality Lead** | Informs of release readiness | — | Reviews acceptance criteria | Reports quality status | Integrates quality in agile | — | Triage defects; test automation | Facilitates UAT |
| **Developer** | — | — | Clarifies requirements; demos work | Reports progress & flags blockers | Raises impediments | Collaborates on test coverage | — | — |
| **Stakeholder** | Escalates to sponsor | Validates priorities | Provides requirements | Raises change requests | — | Participates in UAT | — | — |

---

## Escalation Path

When issues cannot be resolved at one level, use the following escalation path:

1. **Developer / Quality Lead** → raise impediment to Agile Coach / Scrum Master
2. **Agile Coach / Scrum Master** → escalate unresolved blockers to Project Manager
3. **Project Manager** → escalate risks, scope changes, or resource issues to Project Sponsor
4. **Project Sponsor** → resolve organizational blockers or escalate to executive leadership as needed

For detailed escalation guidance, see [Escalation Path Quick Reference](octoacme-escalation-path.md).

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Reference the [RACI Template](octoacme-raci-template.md) to assign owners for specific project activities.
- Use the [Role Onboarding Checklist](octoacme-role-onboarding-checklist.md) when a new team member joins in any of these roles.

