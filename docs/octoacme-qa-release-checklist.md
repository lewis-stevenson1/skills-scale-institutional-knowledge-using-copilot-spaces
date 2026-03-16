# OctoAcme — QA Release Checklist

## Purpose
Provide a structured checklist for the QA Lead and delivery team to complete before, during, and after each release to ensure quality gates are met and defects do not escape to production.

---

## Pre-Release QA Checklist

### Test Coverage Verification
- [ ] Test plan reviewed and updated for this release
- [ ] All new features have corresponding unit tests
- [ ] Integration tests cover new feature interactions
- [ ] Regression test suite has been executed and results reviewed
- [ ] End-to-end (E2E) tests cover the critical user flows affected by this release
- [ ] Flaky tests investigated and either fixed or explicitly deferred with documented rationale

### Acceptance Criteria Sign-Off
- [ ] All user stories in the release have been reviewed against their acceptance criteria
- [ ] Product Manager has confirmed acceptance criteria are met for each feature
- [ ] Any deferred acceptance criteria are documented and approved by Product Manager and Project Manager
- [ ] Definition of Done (DoD) is satisfied for all items in the release

### Defect Review
- [ ] All critical and high-severity defects are resolved or explicitly accepted with stakeholder approval
- [ ] Medium-severity defects are reviewed; unresolved ones are documented in release notes as known issues
- [ ] Defect backlog reviewed for any items that could be impacted by release changes
- [ ] No regression in previously passing tests

### Environment & Build Verification
- [ ] Build deployed to staging environment matches the exact build to be deployed to production
- [ ] Smoke tests executed successfully in the staging environment
- [ ] Performance and load testing completed if this release affects high-traffic or critical paths
- [ ] Security scanning completed with no new critical or high vulnerabilities introduced

### Compliance & Documentation
- [ ] Release notes drafted and reviewed by Product Manager and Release Coordinator
- [ ] Known issues documented in release notes
- [ ] Rollback plan reviewed and confirmed as executable
- [ ] Any regulatory or compliance requirements validated (if applicable)

---

## Release Day QA Checklist

- [ ] Final build verified in staging immediately before production deployment
- [ ] QA Lead confirms go/no-go to Release Coordinator
- [ ] Deployment window confirmed and all stakeholders notified by Release Coordinator
- [ ] QA team on standby during the deployment window for immediate post-deploy verification
- [ ] Production smoke tests executed immediately after deployment
- [ ] Critical user flows validated in production
- [ ] Monitoring dashboards reviewed for any anomalies after deployment
- [ ] Incident response team confirmed as ready if rollback is needed

---

## Post-Release QA Checklist

- [ ] Post-deploy smoke test results documented
- [ ] Defects reported from production (if any) triaged and prioritized
- [ ] QA metrics recorded: test pass rate, defect escape rate, regression coverage
- [ ] Lessons learned captured for the next retrospective
- [ ] Test plan updated to include any new test cases discovered during this release
- [ ] QA sign-off documented and shared with Project Manager and Release Coordinator

---

## QA Metrics to Track Per Release

| Metric | Target | Actual | Notes |
|--------|--------|--------|-------|
| Test Pass Rate | ≥ 95% | | |
| Critical Defects Escaped to Production | 0 | | |
| Regression Test Coverage | ≥ 80% of affected areas | | |
| Days to Sign-Off After Feature Complete | ≤ 3 business days | | |
| Post-Release Defects (within 24 hrs) | 0 critical / ≤ 2 low | | |

---

## QA Sign-Off Record

Complete this record for each release before confirming go/no-go with the Release Coordinator.

**Release Name / Version:** ___________________________

**Release Date:** ___________________________

**QA Lead:** ___________________________

**Sign-Off Status:** ✅ Approved / ❌ Not Approved / ⚠️ Conditional Approval

**Conditions (if conditional approval):**
> List any unresolved items and the agreed acceptance criteria for proceeding.

**Outstanding Known Issues:**
> List any known defects included in the release, with impact assessment and stakeholder approval status.

**Sign-Off Date:** ___________________________

---

## Related Documents
- `docs/octoacme-roles-and-personas.md` — QA Lead and Release Coordinator role descriptions
- `docs/octoacme-release-and-deployment.md` — Release and deployment guide
- `docs/octoacme-execution-and-tracking.md` — Quality and testing workflow during execution
- `docs/octoacme-project-planning.md` — Test plan drafting during planning phase
