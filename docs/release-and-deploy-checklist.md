# Release & Deployment — checklist (updated)

Pre-release
- [ ] All acceptance criteria met and merged PRs approved
- [ ] CI tests passing on release branch
- [ ] Security scan completed and no high-severity findings
- [ ] Release notes drafted and reviewed
- [ ] Rollback plan documented and validated (backup/snapshot steps where applicable)
- [ ] Smoke tests defined and owner assigned

Deployment
- [ ] Deploy to staging and run smoke tests (record results)
- [ ] Run any migration scripts in staging and verify
- [ ] Schedule production deploy and notify stakeholders

Post-deploy verification
- [ ] Run production smoke tests and verify success
- [ ] Monitor dashboards & alerts for 30–60 minutes (or longer for risky releases)
- [ ] If emergent issues appear, follow rollback playbook

Rollback playbook (summary)
- Trigger rollback to last known-good release (automated pipeline preferred)
- Notify on-call and stakeholders with incident summary
- Capture timeline and actions, then run a blameless retrospective

Optional: include a short shell script checklist for smoke tests (path to test commands or k6/postman collection)
