# Contributing to A2A-SIN-Email

## Scope first

Before changing code or docs, verify the change genuinely belongs to the **Email** surface.

Put the change here when it affects:
- email ingestion, routing, or delivery workflows
- email evidence, recovery, mailbox handling, or forwarding
- email contracts tied to inbox processing and delivery automation

Do **not** put the change here when it belongs to:
- generic messaging ownership outside email
- unrelated social, meeting, or chat platform behavior
- organization SSOT docs or architecture ownership

## Workflow

1. Branch from the latest `main`.
2. Make the smallest repo-scoped change possible.
3. Run validation command(s) relevant to the touched surface.
4. Include exact validation commands and evidence in the PR.

## Boundary checklist

- Does this change stay within Email ownership?
- Does another repo already own the adjacent platform behavior?
- Does this PR avoid redefining shared docs, runtime, or platform canon?

## Boundary Rules

Before adding a feature or top-level claim, answer:

1. Is this specifically email integration work?
2. Does another OpenSIN repo already own the canonical source of truth?

### Put it in `A2A-SIN-Email` if:
- it improves email integration
- it improves this repo's A2A agent behavior

### Do NOT put it in `A2A-SIN-Email` if:
- it claims broader messaging, product, ops, or docs ownership

## License

By contributing, you agree that your contributions will be licensed under the Apache License 2.0.
