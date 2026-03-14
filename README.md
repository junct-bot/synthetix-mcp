# Synthetix MCP Server

MCP server for Synthetix. Agent-ready API for Synthetix.

Hosted at [synthetix.mcp.junct.dev/mcp](https://synthetix.mcp.junct.dev/mcp). Free to use. No auth. No API key required.

Part of [Junct](https://junct.dev) — the agent-readiness layer for the crypto stack.

## Quick Start

Add to your MCP client config (Claude Desktop, Cursor, Windsurf):

```json
{
  "mcpServers": {
    "synthetix": {
      "url": "https://synthetix.mcp.junct.dev/mcp",
      "transport": "streamable-http"
    }
  }
}
```

## About

This MCP server is **deterministically generated** from the Synthetix API specification. Every tool maps 1:1 to a real API endpoint — no hallucinated endpoints, no phantom tools.

- **Protocol:** Synthetix
- **Endpoint:** `https://synthetix.mcp.junct.dev/mcp`
- **Transport:** Streamable HTTP
- **Auth:** None required
- **Documentation:** [synthetix.mcp.junct.dev/llms.txt](https://synthetix.mcp.junct.dev/llms.txt)
- **Server card:** [synthetix.mcp.junct.dev/.well-known/mcp/server.json](https://synthetix.mcp.junct.dev/.well-known/mcp/server.json)

## Links

- [Junct Dashboard](https://junct.dev/servers/synthetix)
- [llms.txt](https://synthetix.mcp.junct.dev/llms.txt)
- [agents.md](https://synthetix.mcp.junct.dev/agents.md)
- [OpenAPI spec](https://synthetix.mcp.junct.dev/openapi.json)

## Keywords

Synthetix, MCP server, DeFi, AI agent, agent-ready API, crypto tools, Model Context Protocol, hosted MCP
