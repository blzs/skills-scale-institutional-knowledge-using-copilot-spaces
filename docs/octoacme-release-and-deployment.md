# OctoAcme — Release & Deployment Guide

## Purpose
Standardize how OctoAcme releases features to production to reduce risk and improve observability.

## Release Types
- Patch: hotfixes addressing critical production issues
- Minor: incremental features and improvements
- Major: significant functionality or breaking changes

## Pre-release requirements
- All acceptance criteria met and PRs merged
- Passing CI and security scans — **Security Champion** confirms no outstanding critical vulnerabilities
- Usability sign-off for user-facing changes — **UX Designer** confirms usability testing is complete
- Release notes drafted
- Rollback / mitigation plan documented — **DevOps Engineer** owns the rollback procedure
- Smoke tests prepared

## Deployment Checklist
- [ ] Deployment window scheduled (**DevOps Engineer** coordinates with PM)
- [ ] Backup or snapshot in place (**DevOps Engineer**)
- [ ] Security Champion confirms security scan results are acceptable
- [ ] Deploy to staging and run smoke tests (**DevOps Engineer**)
- [ ] Deploy to production (automated pipeline preferred — **DevOps Engineer**)
- [ ] Run post-deploy verifications
- [ ] Announce release to stakeholders and support

## Rollback & Incident Playbook
- If a deployment fails or causes a critical issue:
  - **DevOps Engineer** triggers incident response and notifies on-call
  - Rollback to last known-good release if necessary (**DevOps Engineer** executes)
  - **Security Champion** assesses whether the incident has a security dimension
  - Triage root cause and capture action items

## Release Notes Template
- Release name / number:
- Date:
- Summary:
- Notable changes:
- Migration steps (if any):
- Known issues:
