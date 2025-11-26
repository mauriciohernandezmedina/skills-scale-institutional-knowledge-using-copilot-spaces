# Release Readiness Checklist

This checklist ensures all necessary steps are completed before a release. Each item is assigned to a specific owner. For role definitions, see the [Roles and Personas](../octoacme-roles-and-personas.md) document.

For release types and deployment guidance, refer to the [Release & Deployment Guide](../octoacme-release-and-deployment.md).

---

## Pre-Release Preparation

| Item | Owner | Status |
|------|-------|--------|
| Release scope finalized and communicated | **Product Manager** | [ ] |
| All acceptance criteria met and PRs merged | **Developers / Engineering Lead** | [ ] |
| Release schedule communicated to stakeholders | **Release Manager** | [ ] |
| Deployment window scheduled (if needed) | **Release Manager** | [ ] |

---

## Quality Assurance

| Item | Owner | Status |
|------|-------|--------|
| Test plan executed and results documented | **QA Lead** | [ ] |
| All critical/high-severity bugs resolved or accepted | **QA Lead** | [ ] |
| Passing CI and automated tests | **Developers** | [ ] |
| End-to-end smoke tests prepared and passing | **QA Lead** | [ ] |
| QA signoff provided | **QA Lead** | [ ] |

---

## Security

| Item | Owner | Status |
|------|-------|--------|
| Security scans completed (CI/CD) | **Security Representative** | [ ] |
| Security review completed and documented | **Security Representative** | [ ] |
| Known vulnerabilities addressed or mitigated | **Security Representative** | [ ] |
| Security signoff provided | **Security Representative** | [ ] |

---

## Documentation & Communication

| Item | Owner | Status |
|------|-------|--------|
| Release notes drafted and reviewed | **Technical Writer** | [ ] |
| Migration steps documented (if applicable) | **Technical Writer** | [ ] |
| Known issues documented | **Technical Writer** | [ ] |
| Stakeholder communication sent | **Project Manager** | [ ] |

---

## Deployment Readiness

| Item | Owner | Status |
|------|-------|--------|
| Rollback / mitigation plan documented | **Release Manager** | [ ] |
| Backup or snapshot taken (if applicable) | **Release Manager** | [ ] |
| Staging deployment completed | **Release Manager** | [ ] |
| Staging smoke tests passed | **QA Lead** | [ ] |

---

## Monitoring & Support

| Item | Owner | Status |
|------|-------|--------|
| Monitoring and alerting configured | **On-call/Support Engineer** | [ ] |
| On-call schedule confirmed | **On-call/Support Engineer** | [ ] |
| Incident playbook reviewed and accessible | **On-call/Support Engineer** | [ ] |
| Support team briefed on release changes | **On-call/Support Engineer** | [ ] |

---

## Final Signoff

| Item | Owner | Status |
|------|-------|--------|
| Release Manager final approval | **Release Manager** | [ ] |
| Product Manager approval | **Product Manager** | [ ] |
| Go/No-Go decision documented | **Release Manager** | [ ] |

---

## Post-Release

| Item | Owner | Status |
|------|-------|--------|
| Production deployment completed | **Release Manager** | [ ] |
| Post-deploy verifications passed | **QA Lead** | [ ] |
| Release announced to stakeholders | **Project Manager** | [ ] |
| Monitoring confirmed (no critical alerts) | **On-call/Support Engineer** | [ ] |

---

## Notes

- Complete all items before proceeding to production deployment
- Document any exceptions or accepted risks
- Update the [Risk Register](../octoacme-risks-and-communication.md) if new risks are identified
