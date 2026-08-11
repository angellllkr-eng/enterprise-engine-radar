# 01 — Enterprise checklist

Mark Pass / Fail / Partial. Record the evidence (doc link, screenshot, or dated vendor statement).

## Access
- [ ] SSO / SAML
- [ ] SCIM
- [ ] RBAC at workspace / project / prompt level
- [ ] Clear separation for domain experts vs engineers
- [ ] Audit log of prompt version changes (who / what / when)

## Compliance & data
- [ ] Current SOC 2 Type II (or equivalent)
- [ ] ISO 27001 if required
- [ ] HIPAA BAA if healthcare
- [ ] Data residency options (US / EU / other)
- [ ] Prompt + trace data can stay in buyer VPC or air-gapped

## Deployment
- [ ] Documented self-host path that actually works
- [ ] Official Helm or Terraform
- [ ] Clear open-core vs paid feature boundary
- [ ] Core features do not require phone-home
