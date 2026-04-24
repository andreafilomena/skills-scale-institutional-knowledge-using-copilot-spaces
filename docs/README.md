# OctoAcme Project Management Docs

## Overview

This README is the entry point to OctoAcme's project management process documentation. OctoAcme follows a lightweight, end-to-end project lifecycle that moves work from **initiation** through **planning**, **execution**, **release**, and finally **close and retrospective**. The approach is built on a set of shared principles: customer-first prioritization, iterative delivery of small and testable increments, clear ownership, data-informed decisions, and psychological safety. A consistent set of artifacts — Project One-pagers, prioritized backlogs with acceptance criteria, a Risk Register, and retrospective notes — provides the connective tissue across every phase and ensures that context is never lost as work progresses.

## Process Summary

**Initiation and planning** establish the foundation for successful delivery. Teams validate the business need, define measurable success metrics, identify stakeholders, and produce a Project One-pager before passing a decision gate that confirms go/no-go. Once approved, the initiative is broken into a prioritized backlog with clear acceptance criteria, estimates, and a Definition of Done. Dependencies and risks are logged in a Risk Register and reviewed at regular cadences, and a release plan maps milestones to a timeline agreed upon by the delivery team and stakeholders.

**Execution and tracking** are driven by a consistent team rhythm and transparent workflow management. Teams use a project board with clear status columns (Backlog → Ready → In Progress → In Review → QA → Done) and support day-to-day delivery through daily standups, weekly delivery syncs, and sprint or milestone demos. Defined roles keep responsibilities clear: Project Managers coordinate timelines, risks, and communications; Product Managers define outcomes and prioritize the backlog; Developers implement and test; and QA/Testing validates acceptance criteria. Stakeholders are engaged for inputs and approvals throughout the lifecycle, and a single source of truth for status — combined with structured weekly update templates and explicit escalation paths — keeps everyone aligned.

**Quality, release, and continuous improvement** are treated as first-class practices. OctoAcme expects unit tests for new logic, integration and end-to-end smoke tests for critical flows, CI-based linting and security scanning, and manual QA for feature acceptance when needed. Releases require that acceptance criteria are met, CI and scans pass, release notes and rollback plans are in place, and staging and production verification steps are completed. After sprints, releases, or incidents, the team runs structured retrospectives to capture what went well, what to improve, and a small set of owned and time-bound action items that feed back into the backlog — supporting continuous improvement and reducing repeat issues over time.

## Document Index

| Document | Description |
|---|---|
| [Project Management Overview](./octoacme-project-management-overview.md) | Principles, core roles, key artifacts, lifecycle summary, and communication cadence |
| [Project Initiation Guide](./octoacme-project-initiation.md) | Steps to validate and authorize new work, including the Project One-pager template and decision gate |
| [Project Planning](./octoacme-project-planning.md) | Backlog building, sprint planning, risk and dependency management, and the planning checklist |
| [Execution & Tracking](./octoacme-execution-and-tracking.md) | Team rhythm, project board workflow, quality practices, reporting metrics, and blocker escalation |
| [Risk Management & Communication](./octoacme-risks-and-communication.md) | Risk Register structure, risk lifecycle, stakeholder communication templates, and escalation paths |
| [Release & Deployment Guide](./octoacme-release-and-deployment.md) | Pre-release checklist, deployment steps, rollback procedures, and post-release verification |
| [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) | Retrospective formats, action item tracking, and continuous improvement practices |
| [Roles & Personas](./octoacme-roles-and-personas.md) | Detailed responsibilities and expectations for each role involved in OctoAcme projects |

> This index will grow as the team adds more process documents. To contribute a new doc, follow the existing naming convention (`octoacme-<topic>.md`) and add a row to the table above.
