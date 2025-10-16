# OctoAcme — Execution & Tracking

## Purpose
Guidance for managing day-to-day execution and tracking progress toward project milestones.

## Team Rhythm
- Daily standups (15 min) — focus on progress, blockers, dependencies
  - **Scrum Master** facilitates and tracks action items
  - **Developers** share progress and blockers
  - **Business Analyst** clarifies requirements as needed
- Weekly delivery sync — show progress, updates, and flagged risks
  - **Project Manager** tracks overall progress and risks
  - **Product Manager** adjusts priorities based on learnings
- Demo/Review at the end of each sprint or milestone
  - **Scrum Master** organizes demo
  - **UX/UI Designer** validates implementation against design specs
  - **Business Analyst** confirms acceptance criteria are met

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
- Level 1: Team-level triage in daily standup (Scrum Master facilitates)
- Level 2: PM escalates to Product Lead and dependent teams (Project Manager coordinates)
- Level 3: Sponsor-level escalation for business-impacting issues (Project Manager + Product Manager)
- **Scrum Master** tracks and removes impediments
- **Project Manager** escalates cross-team dependencies
- **Business Analyst** helps resolve requirement ambiguities

## Execution Checklist
- [ ] Branching and PR conventions documented in repo
- [ ] CI configured for tests and lint
- [ ] Regular demos scheduled (Scrum Master coordinates)
- [ ] Risk register updated weekly (Project Manager)
- [ ] Design QA completed for UI changes (UX/UI Designer)
- [ ] Business acceptance validation scheduled (Business Analyst)
- [ ] Support documentation drafted (Support Lead reviews)

## Handoff to Release
- **From**: Development team completes all acceptance criteria
- **To**: Release Manager for deployment coordination
- **Artifacts**: Merged PRs, passing tests, release notes draft, rollback plan
- **Checklist**:
  - [ ] All acceptance criteria met and validated (Business Analyst)
  - [ ] Design implementation approved (UX/UI Designer)
  - [ ] Security scans passed
  - [ ] Support documentation complete (Support Lead)
  - [ ] Release Manager informed and deployment scheduled
