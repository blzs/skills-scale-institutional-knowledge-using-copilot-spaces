# OctoAcme — Cross-Functional Readiness Checklist

Complete this checklist **before execution begins** (end of planning phase) to confirm that UX, DevOps, Security, and Analytics considerations have been addressed for the upcoming increment or milestone.

---

## UX / Design Readiness

- [ ] User research or discovery sessions completed for key user flows
- [ ] Wireframes or prototypes available for all user-facing features in scope
- [ ] Accessibility requirements (e.g., WCAG level) defined and communicated to Developers
- [ ] Usability testing plan drafted (who, when, how)
- [ ] UX Designer has reviewed and approved designs ready for development

## DevOps / Infrastructure Readiness

- [ ] Environments required for this milestone are provisioned (dev, staging, production)
- [ ] CI/CD pipeline is configured and passing for the current codebase
- [ ] Deployment runbook updated for any new services or configuration changes
- [ ] Rollback procedure documented and tested
- [ ] Monitoring and alerting configured for new or changed services

## Security Readiness

- [ ] Threat model reviewed or updated for new features or integrations
- [ ] Security scanning (SAST, dependency checks) enabled in CI/CD pipeline
- [ ] Outstanding security findings from previous scan triaged and tracked in Risk Register
- [ ] Sensitive data handling reviewed (storage, transmission, access controls)
- [ ] Security Champion briefed on scope and any high-risk areas

## Analytics / Data Readiness

- [ ] Success metrics and KPIs defined for this milestone (with Data Analyst)
- [ ] Data instrumentation requirements specified in backlog items
- [ ] Dashboards or reporting views identified / created for post-release monitoring
- [ ] Data privacy and retention requirements reviewed for any new data collection
- [ ] Data Analyst confirmed as available for post-release analysis

---

## Sign-off

| Role | Name | Sign-off |
|------|------|---------|
| Project Manager | | ☐ Ready |
| Product Manager | | ☐ Ready |
| UX Designer | | ☐ Ready / ☐ N/A |
| DevOps Engineer | | ☐ Ready / ☐ N/A |
| Security Champion | | ☐ Ready / ☐ N/A |
| Data Analyst | | ☐ Ready / ☐ N/A |

> Any item marked incomplete should be captured as a risk in the [Risk Register](octoacme-risks-and-communication.md) before execution starts.
