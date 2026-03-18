---
name: Issue template
about: Standardize the issues content
title: "Area - Component - Action"
labels: ''
assignees: ''

---

**Feature branch:** <!-- e.g., feat/area-component-action -->

## Context
<!-- Why does this matter? -->
<!-- What problem are we solving, or what risk/opportunity are we addressing? -->
<!-- Link to incidents, tickets, discussions, or metrics if relevant -->

## Requirements
<!-- What must be true when this is implemented? -->
<!-- Describe behavior, not implementation -->
<!-- - User can do X -->
<!-- - System prevents Y -->
<!-- - Failure case Z is handled -->

## Definition of Done
<!-- How will we know this is finished? -->
<!-- Focus on verification, not implementation details -->
- [ ] E2E or Unit tests added or updated
- [ ] Merged to `main` and deployed to `production`.
- [ ] Any release or feature toggles related to the task are activated.
- [ ] You have verified it behaves as expected in production (including edge cases and unhappy paths).
- [ ] You are confident it hasn't introduced obvious regressions.
