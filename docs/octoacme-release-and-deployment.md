# OctoAcme — Release & Deployment Guide

## Purpose
Standardize how OctoAcme releases features to production to reduce risk and improve observability.

## Release Types
- Patch: hotfixes addressing critical production issues
- Minor: incremental features and improvements
- Major: significant functionality or breaking changes

## Pre-release requirements
- All acceptance criteria met and PRs merged
- Passing CI and security scans
- Release notes drafted
- Rollback / mitigation plan documented
- Smoke tests prepared
- **Release Manager** coordinates release readiness review
- **Support Lead** ensures support documentation and training are complete
- **Business Analyst** validates that all business requirements are met
- **UX/UI Designer** confirms UI changes match approved designs
- **Project Manager** confirms all stakeholders are informed

## Deployment Checklist
- [ ] Deployment window scheduled (if needed) — Release Manager
- [ ] Backup or snapshot (if applicable) — Infrastructure team
- [ ] Deploy to staging and run smoke tests — Developers + QA
- [ ] Support documentation finalized — Support Lead
- [ ] Support team briefed on changes — Support Lead
- [ ] Deploy to production (automated pipeline preferred) — Release Manager + Developers
- [ ] Run post-deploy verifications — Developers + Release Manager
- [ ] Announce release to stakeholders and support — Release Manager + Project Manager
- [ ] Monitor dashboards for errors or anomalies — Developers + Release Manager

## Release Coordination Roles
- **Release Manager**: Owns the release process, coordinates go/no-go decisions, manages deployment windows
- **Developers**: Deploy code, monitor post-deployment health, respond to incidents
- **Support Lead**: Prepares support team, creates runbooks, monitors customer impact
- **Project Manager**: Communicates release status to stakeholders
- **Product Manager**: Validates that released features meet business objectives

## Rollback & Incident Playbook
- If a deployment fails or causes a critical issue:
  - Trigger incident response and notify on-call
  - **Release Manager** coordinates rollback decision
  - Rollback to last known-good release if necessary
  - **Developers** execute rollback procedure
  - **Support Lead** communicates with affected customers
  - **Project Manager** updates stakeholders on status
  - Triage root cause and capture action items
  - **Scrum Master** facilitates post-incident retrospective

## Handoff to Retrospective
- **From**: Release Manager confirms deployment is stable
- **To**: Scrum Master for retrospective facilitation
- **Artifacts**: Release metrics, incident reports (if any), customer feedback
- **Participants**: All project roles for lessons learned

## Release Notes Template
- Release name / number:
- Date:
- Summary:
- Notable changes:
- Migration steps (if any):
- Known issues:
