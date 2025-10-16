# OctoAcme — Release & Deployment Guide

## Purpose
Standardize how OctoAcme releases features to production to reduce risk and improve observability.

## Release Types
- Patch: hotfixes addressing critical production issues
- Minor: incremental features and improvements
- Major: significant functionality or breaking changes

## Pre-release requirements
- All acceptance criteria met and PRs merged
  - **Validated by:** QA and Product Manager
- Passing CI and security scans
  - **Verified by:** Tech Lead and Release Manager
- Release notes drafted
  - **Prepared by:** Release Manager (with input from Product Manager)
- Rollback / mitigation plan documented
  - **Prepared by:** Release Manager and Tech Lead
- Smoke tests prepared
  - **Prepared by:** QA
- Support team briefed on changes
  - **Led by:** Support Lead (coordinated by Release Manager)

## Deployment Checklist
- [ ] Deployment window scheduled (if needed)
  - **Owner:** Release Manager
- [ ] Backup or snapshot (if applicable)
  - **Owner:** Release Manager / DevOps
- [ ] Deploy to staging and run smoke tests
  - **Owner:** Release Manager and QA
- [ ] Deploy to production (automated pipeline preferred)
  - **Owner:** Release Manager
- [ ] Run post-deploy verifications
  - **Owner:** QA and Developers
- [ ] Announce release to stakeholders and support
  - **Owner:** Release Manager and Support Lead
- [ ] Monitor dashboards for errors and performance
  - **Owner:** Tech Lead and Developers

## Rollback & Incident Playbook
- If a deployment fails or causes a critical issue:
  - Trigger incident response and notify on-call
  - Rollback to last known-good release if necessary
  - Triage root cause and capture action items

## Release Notes Template
- Release name / number:
- Date:
- Summary:
- Notable changes:
- Migration steps (if any):
- Known issues:
