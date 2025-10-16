# OctoAcme — Risk Management & Communication

## Purpose
Explain how to identify, manage, and communicate risks and dependencies.

## Risk Register
Maintain a simple table with:
- ID
- Description
- Impact (High/Med/Low)
- Likelihood (High/Med/Low)
- Owner
- Mitigation plan
- Status

## Risk Lifecycle
- Identify: during planning and ongoing execution
  - **Project Manager** maintains Risk Register
  - **Scrum Master** surfaces team-level risks during standups
  - **Business Analyst** identifies requirement-related risks
  - **Developers** flag technical risks
- Assess: estimate impact and likelihood
  - **Project Manager** facilitates risk assessment with relevant stakeholders
- Mitigate: reduced via actions, contingency plans
  - **Project Manager** assigns mitigation owners and tracks progress
  - **Scrum Master** helps remove impediments that create risk
- Monitor: review at weekly syncs and update status
  - **Project Manager** reports on risk status to stakeholders

## Stakeholder Communication
- Identify stakeholder groups and communication needs (e.g., engineering, sales, support)
- Provide regular updates (weekly or milestone-based)
- Use a single source of truth (project README or release doc) for status

### Communication Roles & Responsibilities
- **Project Manager**: Provides weekly status updates and manages stakeholder expectations
- **Product Manager**: Shares roadmap updates and priority changes with stakeholders
- **Release Manager**: Sends release announcements and coordinates deployment communications
- **Support Lead**: Communicates customer feedback and prepares support teams for releases
- **Business Analyst**: Documents and clarifies requirement changes with stakeholders
- **Scrum Master**: Shares team velocity and improvement initiatives

## Communication Templates
Weekly Status Template:
- Progress this week:
- Next steps:
- Risks & blockers:
- Ask / decisions needed:

Incident Communication
- Triage summary
- Actions being taken
- Expected timeline
- Post-incident blameless retrospective scheduled

## Escalation Paths
- Team-level -> PM -> Product Lead -> Sponsor
- For security incidents, follow the security incident runbook and notify Security on-call
- **Escalation Chain**:
  - **Level 1 (Team)**: Scrum Master facilitates resolution within the team
  - **Level 2 (Cross-team)**: Project Manager escalates to dependent teams and Product Lead
  - **Level 3 (Sponsor)**: Project Manager + Product Manager escalate to executive sponsor
  - **Support Escalations**: Support Lead escalates critical customer issues to engineering
