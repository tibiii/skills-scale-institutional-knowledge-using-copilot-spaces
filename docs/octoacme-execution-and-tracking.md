# OctoAcme — Execution & Tracking

## Purpose
Guidance for managing day-to-day execution and tracking progress toward project milestones.

## Team Rhythm
- Daily standups (15 min) — focus on progress, blockers, dependencies
  - **Facilitated by:** Scrum Master or Project Manager
  - **Attendees:** Developers, QA, UX/UI Designer (as needed)
- Weekly delivery sync — show progress, updates, and flagged risks
  - **Led by:** Project Manager
  - **Attendees:** Product Manager, Tech Lead, stakeholders
- Demo/Review at the end of each sprint or milestone
  - **Facilitated by:** Scrum Master or Product Manager
  - **Attendees:** Full team and stakeholders

## Role Handoffs During Execution
Understanding when and how work passes between roles:

1. **Requirements → Design**: Product Manager/Business Analyst hands off requirements to UX/UI Designer
   - Deliverables: User stories, acceptance criteria, user research insights
   
2. **Design → Development**: UX/UI Designer hands off designs to Developers
   - Deliverables: Mockups, prototypes, design specs, asset files
   - Review: Design feasibility discussion before implementation begins
   
3. **Development → QA**: Developers hand off completed features to QA/Testing
   - Deliverables: Pull requests with test coverage, feature deployed to test environment
   - Criteria: Code reviewed and merged, unit tests passing
   
4. **QA → Release**: QA hands off validated features to Release Manager
   - Deliverables: Test results, sign-off on acceptance criteria
   - Criteria: All tests passing, no critical bugs
   
5. **Release → Support**: Release Manager hands off deployed changes to Support Lead
   - Deliverables: Release notes, known issues, FAQs, training materials
   - Timing: At least 24-48 hours before production deployment

## Workflows
- Use the project board (e.g., GitHub Projects) with columns: Backlog, Ready, In Progress, In Review, QA, Done
- Pull Request workflow:
  - Small PRs (<= 400 lines when possible)
  - Include issue link and acceptance criteria in PR description
  - Run automated tests and linting in CI before requesting review
  - Require at least one approval before merging (or team-defined policy)

## Quality & Testing
- Unit tests for new logic
- Integration tests where applicable
- End-to-end smoke tests for critical flows before release
- Security scanning in CI
- Manual QA for feature acceptance when needed

## Reporting & Metrics
- Track velocity and burndown
- Monitor success metrics identified in the Project One-pager
- Use dashboards for key signals (errors, latency, usage)

## Blocker Escalation
- Level 1: Team-level triage in daily standup
- Level 2: PM escalates to Product Lead and dependent teams
- Level 3: Sponsor-level escalation for business-impacting issues

## Execution Checklist
- [ ] Branching and PR conventions documented in repo
- [ ] CI configured for tests and lint
- [ ] Regular demos scheduled
- [ ] Risk register updated weekly
