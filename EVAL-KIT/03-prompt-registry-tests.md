# 03 — Prompt Registry & Release Tests

## Core
- [ ] Create a prompt with variables
- [ ] Version history with readable diffs
- [ ] Named labels or environments (dev / staging / prod)
- [ ] Protected or locked production labels
- [ ] Rollback by re-assigning a label (no application redeploy)
- [ ] Traffic split or A/B between versions if the platform claims it

## Collaboration
- [ ] Non-engineer can edit and propose a version through the UI
- [ ] Review or approval step before production promotion
- [ ] Clear ownership and last-modified metadata

## Integration
- [ ] SDK or API returns the correct version by label
- [ ] Label change takes effect without restarting the application
