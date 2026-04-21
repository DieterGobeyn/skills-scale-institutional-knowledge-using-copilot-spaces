# OctoAcme — Release Coordination Checklist

Use this checklist to coordinate releases end-to-end and reduce missed deployment activities.

## 1) Release Planning
- [ ] Confirm release scope, goals, and target release date
- [ ] Confirm release type (patch, minor, major)
- [ ] Validate milestone dates with engineering, QA, and operations
- [ ] Confirm owners for all release-critical work items
- [ ] Document key dependencies and external constraints

## 2) Readiness Verification
- [ ] Confirm all planned PRs are merged and linked to release scope
- [ ] Verify CI pipelines and security scans are passing
- [ ] Confirm test execution status (unit, integration, e2e, regression as applicable)
- [ ] Review open defects and agree go/no-go defect thresholds
- [ ] Validate rollback plan and incident response contacts
- [ ] Confirm release notes draft is prepared

## 3) Pre-Deployment Coordination
- [ ] Confirm deployment window and maintenance notice (if required)
- [ ] Share final runbook and deployment checklist with all owners
- [ ] Confirm environment readiness (configs, secrets, feature flags, capacity)
- [ ] Ensure monitoring dashboards and alerts are active
- [ ] Confirm stakeholder communication plan and announcement channels

## 4) Deployment Execution
- [ ] Conduct go/no-go check with engineering, QA, and operations
- [ ] Execute deployment steps in agreed sequence
- [ ] Capture timestamps and owner confirmations for each critical step
- [ ] Validate smoke tests and critical user journeys
- [ ] Monitor system health, error rates, and performance immediately post-deploy

## 5) Post-Deployment Follow-up
- [ ] Announce release completion with key changes and known issues
- [ ] Confirm support and stakeholder teams received release notes
- [ ] Track and triage post-release incidents or regressions
- [ ] Schedule and run release retrospective
- [ ] Record lessons learned and action items with owners and due dates

