# Developer Task Checklist

This is a guide, not a form. Use it to own your task from idea to production.

## 1. Start Right
- **Clarify Implementation**: Know exactly what you are building. Ask about edge cases and constraints.
- **Define "Done"**: Know how you will verify success.

## 2. Build & Merge
- Create a branch from `main`.
- Implement and test locally.
- Open a PR to `main` and get at least one review from a **developer on your project**.
- **Verification**: Ensure your change explains how to test it.

## 3. Merge to Main
- Squash & Merge your PR to `main`.
- Verify the continuous deployment passes.
- Verify the implementation works as expected.

## 5. Release to Production
- Ask for a QA check.
- If successful create a production release tag (e.g., `prod-2026.01.21`) to deploy to `prod`.
- **Monitor**: Once published, watch the release and verify it works for users.

## 6. Follow Through
- You own the change until it's running smoothly in production.
- Be available to fix issues if they arise.
