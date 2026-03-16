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
- QA Lead has completed the QA Release Checklist (`docs/octoacme-qa-release-checklist.md`) and provided sign-off
- Release notes drafted and reviewed by Product Manager and Release Coordinator
- Rollback / mitigation plan documented
- Smoke tests prepared
- Release Coordinator has confirmed all stakeholder communications are ready

## Deployment Checklist
- [ ] QA Lead sign-off received (see `docs/octoacme-qa-release-checklist.md`)
- [ ] Deployment window scheduled and communicated by Release Coordinator
- [ ] Backup or snapshot (if applicable)
- [ ] Deploy to staging and run smoke tests
- [ ] Deploy to production (automated pipeline preferred)
- [ ] Run post-deploy verifications
- [ ] Release Coordinator announces release to stakeholders and support
- [ ] Stakeholder Champion notified to distribute release announcement to business units

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
