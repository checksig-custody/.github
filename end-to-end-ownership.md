# Developer End-to-End Ownership

## 1. The Goal
We want to ship faster and with higher quality. To do this, we share the responsibility of releasing to production. By distributing this ownership, we avoid bottlenecks and empower everyone to ship with confidence.

**"You build it, you run it."**

## 2. What this means for you
Ownership doesn't stop when your PR is merged. It continues until your change is live and running smoothly for users.

As the **Task Owner** (the person implementing the change), you are responsible for:

1.  **Development**: Write code, add tests, and ensure it meets requirements.
2.  **QA**: Ask another developer via any channel to test and review your work. They should know what they should be testing for (e.g. edge cases, possible regressions, etc.)
3.  **Release**: Watch your change deploy to production.
4.  **Verification**: Once deployed, check that it actually works in the real world.
5.  **Support**: If something breaks related to your change, you are the first line of defense (but not the only one!).

## 3. The "Little Bit More"
This isn't a huge new burden. It’s mostly about **follow-through**.
- Instead of "merge and forget," it's "merge, monitor, and verify."
- Instead of waiting for someone else to find a bug, you proactively check your work in dev, test and prod.

## 4. You Are Not Alone
This is a shared responsibility.
- **We help each other**: If you need help verifying or deploying, ask!
- **Leadership supports you**: We prioritize quality and learning over blame.
- **Failures happen**: If something breaks, we fix it together and learn.

## 5. Definition of Done
A task is truly DONE when:
- [ ] E2E or Unit tests are added or updated
- [ ] Merged to `main` and deployed to `production`.
- [ ] Any release or feature toggles related to the task are activated.
- [ ] You have verified it behaves as expected in production (including edge cases and unhappy paths).
- [ ] You are confident it hasn't introduced obvious regressions.
