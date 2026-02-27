# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Purpose

This is an organization-wide `.github` repository for CheckSig. It contains shared GitHub templates, developer guidelines, and commit tooling — not application code.

## Setup

```bash
yarn install   # installs husky + commitlint
```

Husky is configured via `prepare` script and sets up git hooks automatically after install.

## Commit Convention

Commits are enforced by commitlint using `@commitlint/config-conventional`. The config is in `commitlint.config.ts`. All commits must follow the Conventional Commits format:

```
<type>(<optional scope>): <description>
```

Valid types: `feat`, `fix`, `docs`, `style`, `refactor`, `test`, `chore`, `ci`, `perf`, `revert`.

## Repository Structure

- `.github/` — GitHub-specific templates (issue template, PR template) used across the org
- `developer-task-checklist.md` — step-by-step guide for taking a task from idea to production
- `end-to-end-ownership.md` — ownership philosophy: "you build it, you run it"
- `commitlint.config.ts` — commitlint configuration extending `@commitlint/config-conventional`

## Branching & Merging

- Branch from `main`
- PR to `main`, requires at least one review from a developer on the project
- **Squash & Merge** PRs into `main`
- Production releases are tagged (e.g., `prod-2026.01.21`)

## Issue Title Convention

Issues follow the format: `Area - Component - Action`

## Definition of Done

A task is done when:
- E2E or unit tests are added/updated
- Merged to `main` and deployed to production
- Feature/release toggles activated if applicable
- Verified working in production (including edge cases)
- No obvious regressions introduced
