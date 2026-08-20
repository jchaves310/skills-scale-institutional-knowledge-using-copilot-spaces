# OctoAcme Project Management Documentation

## Overview
OctoAcme follows a structured, iterative approach to delivering customer value through small, testable increments and clear ownership. Projects move through defined phases — Initiation, Planning, Execution, Release, and Close/Retrospective — with emphasis on data-informed decisions, psychological safety, and continuous improvement. This README serves as the central entry point to the OctoAcme project management process documents in this folder.

## Project management processes (brief)
- Initiation: Validate the business need and capture the project One‑pager to align stakeholders and decide whether to move into planning.
- Planning: Turn approved initiatives into a prioritized backlog, define the Definition of Done (DoD), identify risks and dependencies, and create milestone and release plans.
- Execution: Track work on the project board (Backlog → Ready → In Progress → In Review → QA → Done). Use daily standups, weekly delivery syncs, small pull requests with CI and linting, and required reviews before merging.
- Release: Follow a pre-release checklist (passing CI/security scans, release notes, rollback plan), verify in staging, deploy via automated pipelines when possible, and run post-deploy verifications and smoke tests.
- Close & Retrospective: Capture learnings after releases or milestones, convert action items into backlog work, and measure the impact of improvements.

## Key workflows, roles & communication
- Workflows: Project board workflow, small PRs (aim ≤ 400 lines), CI and security scans before review, formal release checklist, and a documented rollback playbook. Maintain a Risk Register for tracking and escalation.
- Personas/Roles: Project Manager (delivery coordination), Product Manager (outcomes and prioritization), Developers (implementation, tests, reviews), QA/Testing (acceptance validation), and Stakeholders (approvals and input).
- Communication: Daily standups for blockers and progress, weekly delivery syncs for progress and flagged risks, regular demos at the end of sprints/milestones, and a single source of truth (project README or release doc). Escalation path: Team → PM → Product Lead → Sponsor; security incidents follow the security runbook.
- Quality: Unit and integration tests, end‑to‑end smoke tests for critical flows, CI security scanning, and manual QA where needed. Release gates require passing CI and meeting acceptance criteria.

## Documentation index
### Getting started
- Project Management Overview – octoacme-project-management-overview.md
- Roles and Personas – octoacme-roles-and-personas.md

### Phases & processes
- Project Initiation – octoacme-project-initiation.md
- Project Planning – octoacme-project-planning.md
- Execution & Tracking – octoacme-execution-and-tracking.md
- Release & Deployment – octoacme-release-and-deployment.md
- Retrospective & Continuous Improvement – octoacme-retrospective-and-continuous-improvement.md

### Cross-cutting
- Risk Management & Communication – octoacme-risks-and-communication.md

## Quick start for new team members
1. Read the Project Management Overview to understand principles and key artifacts.
2. Review Roles and Personas to find responsibilities relevant to your role.
3. For a new idea, follow Project Initiation to create the one‑pager and align stakeholders.
4. Use Project Planning to build backlog, estimates, and DoD; then execute using the project board and PR workflow.
5. During execution, follow the Risk Management & Communication guide for escalations and status reporting.

---

*This README was added to centralize OctoAcme project management processes and improve discoverability for new and existing team members.*
