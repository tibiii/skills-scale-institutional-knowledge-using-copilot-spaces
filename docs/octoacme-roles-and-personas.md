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

---

## Scrum Masters

### Role Summary
Scrum Masters facilitate agile ceremonies, remove impediments, and coach teams on Scrum/agile practices. They ensure the team adheres to agreed processes and continuously improves.

### Responsibilities
- Facilitate sprint planning, daily standups, reviews, and retrospectives
- Remove blockers and impediments that slow team velocity
- Coach team members on agile practices and self-organization
- Shield the team from external distractions and unnecessary meetings
- Track team metrics (velocity, burndown) and identify improvement opportunities

### Goals
- Maximize team productivity and flow
- Foster a culture of continuous improvement and psychological safety
- Ensure process adherence without bureaucracy

### Typical Communication
- Daily facilitation of standups and team coordination
- Weekly sync with Project Manager on impediments and team health
- Retrospective facilitation and follow-up on action items

---

## UX/UI Designers

### Role Summary
UX/UI Designers create user-centered designs that balance usability, accessibility, and visual appeal. They collaborate with Product Managers and Developers to ensure features meet user needs.

### Responsibilities
- Conduct user research and usability testing
- Create wireframes, mockups, and prototypes
- Define user flows and interaction patterns
- Maintain design systems and style guides
- Collaborate with developers on implementation feasibility

### Goals
- Deliver intuitive, accessible user experiences
- Ensure design consistency across the product
- Validate designs with real user feedback

### Typical Communication
- Design reviews with Product Managers and stakeholders
- Handoff sessions with developers (design specs, assets)
- User research findings and usability test results

---

## Business Analysts

### Role Summary
Business Analysts bridge the gap between business stakeholders and technical teams. They gather requirements, analyze business processes, and ensure solutions align with business objectives.

### Responsibilities
- Elicit and document business requirements
- Analyze current-state processes and identify improvement opportunities
- Create process flows, data models, and requirement specifications
- Validate that delivered solutions meet business needs
- Support change management and user adoption

### Goals
- Ensure clear, actionable requirements
- Minimize rework by catching gaps early
- Align technical solutions with business value

### Typical Communication
- Requirements workshops with stakeholders
- Clarification sessions with developers and Product Managers
- Acceptance testing and validation of delivered features

---

## Release Managers

### Role Summary
Release Managers coordinate the end-to-end release process, ensuring that features are deployed smoothly, safely, and on schedule. They manage release planning, coordination, and communication.

### Responsibilities
- Create and maintain release schedules and plans
- Coordinate release readiness reviews and go/no-go decisions
- Manage deployment windows and change freezes
- Track release metrics and post-deployment health
- Coordinate rollback procedures if issues arise

### Goals
- Deliver reliable, on-time releases
- Minimize deployment-related incidents
- Maintain clear release documentation and communication

### Typical Communication
- Release planning meetings with engineering and product teams
- Deployment coordination with infrastructure and operations teams
- Release announcements to stakeholders, support, and customers

---

## Support Leads

### Role Summary
Support Leads represent the voice of customers and support teams during product development. They ensure features are supportable and that support teams are prepared for new releases.

### Responsibilities
- Provide feedback on customer pain points and common issues
- Review upcoming features for supportability and documentation needs
- Prepare support teams for new releases (training, runbooks)
- Escalate critical customer issues to engineering
- Track support metrics and trends

### Goals
- Reduce customer friction and support ticket volume
- Ensure support teams can effectively handle customer inquiries
- Bridge customer feedback into product improvements

### Typical Communication
- Weekly syncs with Product Managers on customer trends
- Pre-release reviews with Release Managers
- Support readiness briefings and documentation reviews

---

## Collaboration Patterns & Handoffs

### Initiation Phase
- **Business Analyst** works with stakeholders to gather initial requirements and create the Project One-pager
- **Product Manager** validates business value and success metrics
- **Project Manager** coordinates stakeholder alignment and creates initial timeline
- **Handoff**: One-pager approved → move to Planning

### Planning Phase
- **Business Analyst** documents detailed requirements and acceptance criteria
- **UX/UI Designer** creates wireframes and user flows based on requirements
- **Scrum Master** facilitates sprint planning and estimation sessions
- **Developers** estimate scope and identify technical dependencies
- **Release Manager** incorporates features into release schedule
- **Handoff**: Design specs and backlog ready → move to Execution

### Execution Phase
- **Developers** implement features following design specs and acceptance criteria
- **UX/UI Designer** reviews implementation and provides feedback during design QA
- **Scrum Master** facilitates daily standups and removes blockers
- **Project Manager** tracks progress, manages risks, and communicates status
- **Business Analyst** validates that implementation meets business requirements
- **Handoff**: Code merged and tested → move to Release

### Release Phase
- **Release Manager** coordinates release readiness review and deployment
- **Support Lead** ensures support documentation and training are complete
- **Developers** monitor post-deployment metrics and address issues
- **Project Manager** announces release and updates stakeholders
- **Handoff**: Release deployed and verified → move to Retrospective

### Retrospective Phase
- **Scrum Master** facilitates retrospective and captures action items
- **Project Manager** tracks action items and incorporates into next project
- All roles participate in learnings and continuous improvement

### Cross-Team Dependencies
- **Project Manager** owns dependency tracking and escalation
- **Business Analyst** documents integration points and data flows
- **Release Manager** coordinates timing with dependent teams
- **Scrum Master** flags impediments caused by external dependencies

### Stakeholder Communication
- **Project Manager** provides weekly status updates to stakeholders
- **Product Manager** shares roadmap and priority changes
- **Release Manager** sends release announcements and change notices
- **Support Lead** communicates customer feedback and support trends

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

