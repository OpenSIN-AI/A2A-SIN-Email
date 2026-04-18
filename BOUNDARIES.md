# A2A-SIN-Email Boundaries

## Role
`A2A-SIN-Email` owns email integration, IMAP/SMTP workflows, and email-specific contracts.

## This repo should own
- email ingestion, routing, and delivery workflows
- email evidence, recovery, Gmail/SMTP handling, and mailbox automation
- email contracts used by downstream communication automation agents
- runbooks tied to inbox processing, forwarding, and email delivery

## This repo must not own
- generic messaging ownership outside email
- unrelated social, meeting, or chat platform behavior
- organization SSOT docs or architecture canon

## Hard rules
- Keep changes scoped to email integration and mailbox workflows.
- Move non-email behavior back to the repos that own those surfaces.
- Keep reusable contracts focused on inbox routing, delivery, and mailbox automation.
