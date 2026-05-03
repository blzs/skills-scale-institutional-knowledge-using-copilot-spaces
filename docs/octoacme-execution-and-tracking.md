# OctoAcme — Execution & Tracking

## Purpose
Guidance for managing day-to-day execution and tracking progress toward project milestones.

## Team Rhythm
- Daily standups (15 min) — focus on progress, blockers, dependencies
- Weekly delivery sync — show progress, updates, and flagged risks
- Demo/Review at the end of each sprint or milestone

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
- Security scanning in CI — **Security Champion** triages results and tracks remediation
- Manual QA for feature acceptance when needed
- Usability validation — **UX Designer** conducts usability testing before milestone sign-off

## Reporting & Metrics
- Track velocity and burndown
- Monitor success metrics identified in the Project One-pager
- Use dashboards for key signals (errors, latency, usage) — **Data Analyst** owns dashboard design and maintenance
- **DevOps Engineer** monitors system health, performance alerts, and on-call response

## Blocker Escalation
- Level 1: Team-level triage in daily standup
- Level 2: PM escalates to Product Lead and dependent teams
- Level 3: Sponsor-level escalation for business-impacting issues
- Security incidents: **Security Champion** initiates the security incident runbook; see [Risk Management & Communication](octoacme-risks-and-communication.md)

## Execution Checklist
- [ ] Branching and PR conventions documented in repo
- [ ] CI configured for tests, lint, and security scanning (**DevOps Engineer** + **Security Champion**)
- [ ] Dashboards configured for key success metrics (**Data Analyst**)
- [ ] Usability testing scheduled for major user-facing changes (**UX Designer**)
- [ ] Regular demos scheduled
- [ ] Risk register updated weekly
