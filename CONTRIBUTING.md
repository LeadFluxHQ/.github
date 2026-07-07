# Contributing to LeadFlux

Thanks for putting time into this. Whether you're fixing a typo in the docs or shipping an SDK feature, this document covers how to do it.

## Before you start

- Check open issues and PRs so you don't duplicate work.
- For anything larger than a small fix — new SDK methods, breaking changes, new endpoints — open an issue first and tag it discussion. We'd rather align before code than review a large PR that goes a different direction than the roadmap.

## Branching

We use trunk-based development with short-lived feature branches:

main - always deployable
feat/short-name - new functionality
fix/short-name - bug fixes
chore/short-name - tooling, deps, non-functional changes
docs/short-name - documentation only

Branch off main, keep branches short-lived (days, not weeks), rebase before opening a PR.

## Commit messages

We follow Conventional Commits. Format:

type(scope): short description

Example: feat(sdk-js): add retry policy to client.calls.trigger()

Types: feat, fix, docs, style, refactor, perf, test, chore, ci, revert.

## Pull requests

1. Fork (external contributors) or branch (org members).
2. Make your change, with tests where behavior changes.
3. Run lint, typecheck, and tests locally before pushing.
4. Open a PR against main using the PR template — fill in every section.
5. One approving review and passing CI required to merge.
6. We squash-merge. Your PR title becomes the commit message on main.

## What we will not merge

- Changes without tests, where the change affects behavior.
- Anything that alters the public API surface of an SDK without a matching RFC.
- Dependency additions without a stated reason in the PR description.

## Code of Conduct

This project holds everyone to the standard in CODE_OF_CONDUCT.md.

## Questions

Open a Discussion rather than an issue for anything that isn't a concrete bug or feature request.
