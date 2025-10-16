# OctoAcme Project Management Process Guide

Welcome to OctoAcme! This README provides a brief overview of how we manage projects, enabling new team members to quickly understand our workflows, roles, communication practices, and quality standards. For detailed information on specific topics, please refer to the linked process documents throughout this guide.

## How We Run Projects

Project management at OctoAcme follows a structured lifecycle designed to deliver customer value iteratively while maintaining transparency and accountability. Every project begins with a clear **initiation process** ([see Project Initiation Guide](octoacme-project-initiation.md)) where Business Analysts gather requirements, Product Managers validate business needs, and Project Managers align stakeholders. This process creates foundational artifacts like the Project One-pager, which captures the problem statement, objectives, success metrics, stakeholders, timeline, and initial risks—ensuring everyone shares a common understanding before work begins. Once an initiative is approved, we move into **planning** ([see Project Planning](octoacme-project-planning.md)), where Scrum Masters facilitate sprint planning, UX/UI Designers create design specifications, Business Analysts document detailed acceptance criteria, and developers estimate scope using story points or T-shirt sizing. Release Managers align project milestones with the release calendar, and Support Leads review features for supportability. Planning also defines the Definition of Done and identifies cross-team dependencies tracked by the Project Manager to minimize surprises during execution.

## Roles, Responsibilities, and Communication

OctoAcme projects are delivered by cross-functional teams with clearly defined roles ([see Roles and Personas](octoacme-roles-and-personas.md)). **Project Managers (PMs)** coordinate delivery, manage schedules, track risks, and facilitate communication across stakeholders. **Product Managers (PdMs)** own the product vision, prioritize the backlog based on customer value, and measure success through data-driven metrics. **Scrum Masters** facilitate agile ceremonies (daily standups, sprint planning, retrospectives), remove impediments, and coach teams on continuous improvement. **Business Analysts** gather and document requirements, create acceptance criteria, and validate that solutions meet business needs. **UX/UI Designers** create user-centered designs, wireframes, and prototypes while ensuring accessibility and design consistency. **Developers** implement features, write tests, participate in code reviews, and help identify technical risks. **Release Managers** coordinate end-to-end release processes, manage deployment windows, and track release health. **Support Leads** represent customer voice, prepare support teams for releases, and escalate critical issues to engineering. **QA/Testing** validates that acceptance criteria are met and ensures quality standards are upheld. 

Communication is intentional and structured to maintain alignment and psychological safety ([see Risk Management & Communication](octoacme-risks-and-communication.md)). Teams hold daily standups facilitated by the Scrum Master to surface blockers and progress, weekly syncs between PMs, PdMs, and Scrum Masters to align on priorities and risks, and monthly stakeholder updates led by the Project Manager to maintain transparency. Release Managers conduct pre-release briefings with Support Leads to ensure support readiness. Blocker escalation paths are clearly defined—from team-level triage facilitated by the Scrum Master, to PM escalation for cross-team dependencies, to sponsor-level decisions for business-impacting issues—ensuring problems are resolved quickly without bottlenecks.

## Quality Assurance and Release Practices

Quality is integrated at every phase of the project lifecycle, not treated as a final gate ([see Execution & Tracking](octoacme-execution-and-tracking.md) and [Release & Deployment Guide](octoacme-release-and-deployment.md)). During execution, Scrum Masters facilitate daily standups, UX/UI Designers review implementations during design QA, and Business Analysts validate that features meet business requirements. Developers write unit and integration tests for new logic, and all code must pass automated tests, linting, and security scans in CI pipelines before being merged. Pull requests are kept small (ideally ≤400 lines), require at least one approval, and include clear descriptions linking to issues and acceptance criteria. Manual QA validates feature acceptance when needed, and end-to-end smoke tests verify critical flows before release. 

Pre-release checklists coordinated by the Release Manager ensure that all acceptance criteria are met, support documentation is finalized by the Support Lead, release notes are drafted, rollback plans are documented, and deployments are tested in staging environments. Release Managers coordinate go/no-go decisions and manage deployment windows, while Support Leads prepare support teams through training and runbooks. Post-release monitoring via dashboards tracks errors, latency, and usage to catch issues early. If a deployment fails, Release Managers coordinate rollback decisions, Support Leads communicate with affected customers, and Scrum Masters facilitate blameless retrospectives to learn and improve.

## Continuous Improvement

OctoAcme embraces a culture of continuous improvement through regular retrospectives ([see Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)). After each sprint, release, or milestone—and following incidents—Scrum Masters facilitate retrospectives where teams gather to discuss what went well, what could be improved, and capture 2–3 actionable follow-ups with clear owners and due dates. All project roles participate, including Release Managers who share deployment metrics and Support Leads who provide customer feedback. These action items are tracked by the Scrum Master and reviewed by the Project Manager in weekly PM syncs to ensure accountability and progress. By measuring the impact of improvements and celebrating successes, we foster psychological safety and iterative learning, ensuring that each project builds on the lessons of the last.

## Key Artifacts and Where to Find Them

Throughout the project lifecycle, teams create and maintain several key artifacts to ensure alignment and transparency:

- **Project Charter / One-pager**: Problem statement, goals, success metrics, stakeholders, and timeline
- **Roadmap and Release Plan**: High-level milestones and delivery schedule
- **Sprint/Iteration Backlog**: Prioritized work items with acceptance criteria
- **Risk Register**: Identified risks, impact, likelihood, mitigation plans, and owners
- **Definition of Done**: Shared quality standards for work to be considered complete
- **Retrospective Notes**: Learnings and action items from each iteration or milestone

These artifacts are typically stored in the project repository (in `docs/` or `.copilot/` folders) to serve as a single source of truth and enable tools like Copilot Spaces to use them as context.

## Getting Started

If you're joining an OctoAcme project, start by reviewing the [Project Management Overview](octoacme-project-management-overview.md) for high-level principles and then dive into the specific process documents relevant to your role and current project phase. Our approach is designed to be lightweight, iterative, and customer-first—ensuring that every team member can contribute effectively while maintaining quality and transparency.
