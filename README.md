# AgentMemory Mesh MCP

AgentMemory Mesh remote MCP for agent memory MCP.

Paid remote MCP for agent memory MCP, structured receipts, usage logs, and audit-ready evidence for agent and CI workflows.

## Public Endpoints

- Website: https://agentmemorymcp.clauxel.com/?utm_source=github&utm_medium=directory&utm_campaign=sbl202605
- MCP endpoint: https://agentmemorymcp.clauxel.com/mcp
- Server card: https://agentmemorymcp.clauxel.com/server-card.json
- Registry name: `com.clauxel.agentmemorymcp/agentmemorymcp-mcp`

## Access

This is a paid hosted remote MCP. Production calls require a bearer token issued from the product website.

```http
Authorization: Bearer <token>
```

Unauthenticated browser visits to `/mcp` return a clear JSON error instead of internal details.

## Tools

- `memory_smart_search`
- `memory_save_observation`
- `memory_session_summary`
- `memory_graph_query`

## Quick Start

1. Open the website and choose a plan.
2. Create or request an API token.
3. Add the endpoint to an MCP client that supports Streamable HTTP remote servers.
4. Send JSON-RPC requests with the bearer token.

## Useful Links

- Product page: https://agentmemorymcp.clauxel.com/?utm_source=github&utm_medium=directory&utm_campaign=sbl202605
- Pricing: https://agentmemorymcp.clauxel.com/?utm_source=github&utm_medium=directory&utm_campaign=sbl202605#pricing
- Server card: https://agentmemorymcp.clauxel.com/server-card.json
- MCP endpoint: https://agentmemorymcp.clauxel.com/mcp

## Status

This repository is a public documentation and directory-submission reference for the hosted service. It does not contain the private production source code.
