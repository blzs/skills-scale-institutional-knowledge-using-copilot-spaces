# OctoAcme — Role RACI & Responsibility Checklist

Use this checklist during project **initiation and planning** to confirm which roles are required and that ownership is clear before execution begins.

> **RACI key:**  R = Responsible | A = Accountable | C = Consulted | I = Informed

---

## Core Delivery Roles

| Role | Present on Project? | Key Owner / Assignee |
|------|--------------------|--------------------|
| Project Manager (PM) | ☐ Yes ☐ No | |
| Product Manager (PdM) | ☐ Yes ☐ No | |
| Developers | ☐ Yes ☐ No | |
| QA / Testing | ☐ Yes ☐ No | |
| Stakeholders | ☐ Yes ☐ No | |

## Extended / Specialist Roles

| Role | Required? | Owner / Assignee | Engagement Phase |
|------|-----------|-----------------|-----------------|
| UX Designer | ☐ Yes ☐ No | | Initiation, Planning, Execution |
| DevOps Engineer | ☐ Yes ☐ No | | Planning, Execution, Release |
| Security Champion | ☐ Yes ☐ No | | Initiation, Execution, Release |
| Data Analyst | ☐ Yes ☐ No | | Planning, Execution, Post-release |

---

## RACI by Process Area

| Process Area | PM | PdM | Dev | QA | UX | DevOps | Security | Data |
|-------------|----|----|-----|-----|-----|--------|----------|------|
| Project One-pager | A | C | I | I | C | C | C | C |
| Backlog & prioritisation | C | A | R | C | C | I | C | C |
| Architecture & design | C | C | R | C | R | R | C | I |
| UI/UX design & usability | I | C | C | R | A | I | I | I |
| CI/CD pipeline & environments | C | I | C | C | I | A/R | C | I |
| Security review & scanning | C | C | C | C | I | C | A/R | I |
| Test plan & QA execution | C | C | C | A/R | C | C | C | I |
| Metrics & dashboards | C | C | C | I | I | C | I | A/R |
| Risk Register | A | C | C | C | C | C | R | I |
| Release & deployment | A | I | C | C | I | R | C | I |
| Stakeholder communication | A | R | I | I | I | I | I | C |
| Post-release retrospective | A | R | R | R | R | R | R | R |

---

## Sign-off

- [ ] All required roles identified and confirmed above
- [ ] Each required role has a named assignee
- [ ] Roles without a named owner are documented as a risk in the Risk Register
- [ ] This checklist added to the project repo `docs/` folder
