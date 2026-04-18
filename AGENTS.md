# A2A-SIN-Email — AGENTS.md

## Purpose

Email integration agent — full email agent with IMAP/SMTP for the OpenSIN fleet.

## Rules

- ALWAYS use opencode CLI for LLM calls
- NEVER store emails locally — process and forward
- ALWAYS log errors to the approved artifact storage surface
- ALWAYS follow Google account matrix for Gmail

## PARALLEL-EXPLORATION MANDATE (PRIORITY -4.5)

Bei grossen Codebases MUESSEN Agenten **5-10 parallele explore + 5-10 librarian-Agenten** starten.

## Subagenten-Modelle

| Subagent | Modell |
|:---|:---|
| **explore** | `nvidia-nim/stepfun-ai/step-3.5-flash` |
| **librarian** | `nvidia-nim/stepfun-ai/step-3.5-flash` |

## Agent Config System v5

→ [Full Documentation](https://github.com/OpenSIN-AI/OpenSIN-documentation/blob/main/docs/guide/agent-configuration.md)

## Boundary Guidance

When modifying this repo:

- Prefer email integration, inbox processing, and delivery work.
- Do not turn this repo into a generic messaging bucket.
- Do not redefine organization docs, architecture, runtime canon, or non-email ownership here.
- Move non-email behavior back to the repos that own those surfaces.

## License

Apache-2.0
