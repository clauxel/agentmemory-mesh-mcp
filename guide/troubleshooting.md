# Troubleshooting

## Public Website Does Not Load

Check the clean homepage first:

- https://agentmemorymcp.clauxel.com/

Then use the tracked documentation link:

- https://agentmemorymcp.clauxel.com/?utm_source=github&utm_medium=documentation&utm_campaign=agentmemorymcp_public_docs&utm_content=troubleshooting_home

## Checkout Link Fails

Use the public checkout route and avoid adding private account information to GitHub issues.

- https://agentmemorymcp.clauxel.com/checkout/?utm_source=github&utm_medium=documentation&utm_campaign=agentmemorymcp_public_docs&utm_content=troubleshooting_checkout

## MCP Request Fails

- Confirm the endpoint is exactly `https://agentmemorymcp.clauxel.com/mcp`.
- Confirm the request is POST JSON-RPC.
- Confirm the bearer token is stored outside public files.
