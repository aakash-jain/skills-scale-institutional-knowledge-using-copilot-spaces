## Release Checklist (copyable)

Use this checklist before performing a release. Copy into release notes or release runbook.

- [ ] Feature acceptance criteria for release items are met
- [ ] All related PRs merged and linked to release
- [ ] CI: all pipelines green (unit, integration, lint)
- [ ] Security scans: no critical findings (or documented mitigation)
- [ ] Database migration plan reviewed and rollback tested (if applicable)
- [ ] Release notes drafted and reviewed
- [ ] Rollback plan documented and verified
- [ ] Staging deployment complete and smoke tests pass
- [ ] Schedule/announce release to stakeholders
- [ ] Production deployment performed (follow runbook)
- [ ] Post-deploy verifications completed (smoke checks)
- [ ] Monitor metrics and errors for at least X minutes/hours
- [ ] Post-release retrospective / lessons logged

Notes:
- Adjust the monitoring window and migration steps for your project scope.
