# 01 — Enterprise Readiness Checklist

Run this against every shortlisted platform. Mark Pass / Fail / Partial.

## Identity & Access
- [ ] SSO / SAML available
- [ ] SCIM provisioning
- [ ] Granular RBAC (workspace / project / prompt level)
- [ ] Role separation between engineers and domain experts
- [ ] Audit log of who changed what prompt version and when

## Compliance & Residency
- [ ] Current SOC 2 Type II (or equivalent)
- [ ] ISO 27001 if required by buyer
- [ ] HIPAA BAA available (if healthcare)
- [ ] Data residency options (US / EU / other)
- [ ] Ability to keep prompt + trace data inside buyer VPC / air-gapped

## Deployment Model
- [ ] True self-host path documented and tested
- [ ] Official Helm chart or Terraform modules
- [ ] Clear separation between open-source core and commercial EE features
- [ ] No forced phone-home for core functionality

## Notes for Buyer Conversation
Record exact evidence (screenshot, docs link, or vendor statement date).
