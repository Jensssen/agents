---
"agents": minor
---

MCP client: `addMcpServer()` no longer reconnects a registered server; use the new `reconnectMcpServer(id)` to retry. See [Reconnecting on request](https://github.com/cloudflare/agents/blob/main/docs/agents/mcp-client.md#reconnecting-on-request).
