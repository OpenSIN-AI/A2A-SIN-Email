# A2A-SIN-Email — AGENTS.md

## Purpose

Email integration agent — full email agent with IMAP/SMTP for the OpenSIN fleet.

## Rules

- ALWAYS use opencode CLI for LLM calls
- NEVER store emails locally — process and forward
- ALWAYS log errors to GitLab LogCenter
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
