# 01 — Enterprise Readiness Checklist

Mark every item Pass / Fail / Partial. Record the exact evidence (docs link, screenshot date, or vendor statement).

## Identity & access
- [ ] SSO / SAML
- [ ] SCIM provisioning
- [ ] Workspace / project / prompt-level RBAC
- [ ] Clear separation between engineer and domain-expert roles
- [ ] Immutable audit log of prompt version changes (who, when, from → to)

## Compliance & residency
- [ ] Current SOC 2 Type II (or equivalent) statement available
- [ ] ISO 27001 if the buyer requires it
- [ ] HIPAA BAA available when needed
- [ ] Data residency options that match the buyer’s policy (US / EU / other)
- [ ] Ability to keep prompts and traces inside the buyer’s VPC or air-gapped environment

## Deployment model
- [ ] Documented self-host path that an experienced platform engineer can follow without tribal knowledge
- [ ] Official Helm chart or Terraform modules
- [ ] Clear split between open-source core and commercial EE features
- [ ] No mandatory phone-home for core tracing, registry, or evaluation features

## Notes for the buyer conversation
Capture the date of the evidence and any open gaps. Gaps become the private scorecard content.
