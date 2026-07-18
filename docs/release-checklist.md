# Release Checklist (OctoAcme)

Purpose: A practical deploy checklist for Release Managers to reduce release risk and standardize communication.

Pre-release (at least 48–72 hours before release)
- [ ] Confirm all PRs for release are merged and linked to release milestone
- [ ] Verify CI is green and security scans passed
- [ ] Confirm that acceptance criteria and release notes draft are complete
- [ ] Confirm rollback plan and previous-good commit identified
- [ ] Notify stakeholders and schedule deployment window
- [ ] Confirm monitoring/dashboards and alerting are in place for key metrics

Release (deployment window)
- [ ] Create a release tag and trigger the deployment pipeline
- [ ] Monitor CI/CD pipeline for errors
- [ ] Run smoke tests in staging and production (post-deploy)
- [ ] Coordinate with SRE / Platform for any infra-level steps
- [ ] Record deployment start and end times

Post-release (first 24 hours)
- [ ] Run post-deploy verification checklist (smoke tests, critical flows)
- [ ] Monitor dashboards and error monitoring for regressions
- [ ] Communicate release outcome to stakeholders (success/fail/roll-forward)
- [ ] Open follow-up issues for any post-release bugs or improvements
- [ ] Update runbooks and deployment notes if procedures changed

Escalation
- [ ] If critical regressions are found, follow rollback playbook and notify on-call and PM
- [ ] Document incident and schedule a blameless post-mortem if appropriate

Usage
- Release Manager owns this checklist. Delivery Leads and SRE should be available during the window.