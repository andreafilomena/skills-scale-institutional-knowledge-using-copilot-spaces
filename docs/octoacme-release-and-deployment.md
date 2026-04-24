# OctoAcme — Release & Deployment Guide

## Purpose
Standardize how OctoAcme releases features to production to reduce risk and improve observability.

## Release Types
- Patch: hotfixes addressing critical production issues
- Minor: incremental features and improvements
- Major: significant functionality or breaking changes

## Pre-release requirements
- All acceptance criteria met and PRs merged
- Passing CI and security scans (reviewed and signed off by **Security Lead**)
- Release notes drafted by **Technical Writer**, reviewed by **Product Manager** and **Customer Success**
- Rollback / mitigation plan documented
- Smoke tests prepared
- **UX Designer** has reviewed implemented UI against design specs
- **Data Analyst** has validated analytics instrumentation in staging
- **Customer Success** has prepared support materials and FAQs

> For a full pre-release owner checklist, see the [Cross-Functional Engagement Checklist — Execution → Release](./octoacme-cross-functional-engagement-checklist.md#execution--release).

## Deployment Checklist
- [ ] Deployment window scheduled (if needed)
- [ ] Backup or snapshot (if applicable)
- [ ] Deploy to staging and run smoke tests
- [ ] Deploy to production (automated pipeline preferred)
- [ ] Run post-deploy verifications
- [ ] Announce release to stakeholders and support

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
