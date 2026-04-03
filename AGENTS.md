# Agent: A2A-SIN-Email

**Team:** OpenSIN-AI
**Protocol:** A2A (Agent-to-Agent)
**Status:** Active
**Repository:** https://github.com/OpenSIN-AI/A2A-SIN-Email

## Capabilities

A2A agent for Email integration within the OpenSIN ecosystem.

## Communication

- **Input:** A2A messages from orchestrator
- **Output:** A2A messages to other agents
- **MCP:** Standard OpenSIN MCP servers

## Security

- All operations logged to OpenSIN-Ledger
- Requires authorization token
- Guardrails enforced on all inputs/outputs

## Setup

```bash
git clone https://github.com/OpenSIN-AI/A2A-SIN-Email.git
cd A2A-SIN-Email
npm install
npm start
```

## License

MIT
