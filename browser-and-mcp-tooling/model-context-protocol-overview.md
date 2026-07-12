# Model Context Protocol (MCP)

> Sources: Anthropic / MCP steering group, Unknown date
> Raw: [What is the Model Context Protocol (MCP)?](../../raw/browser-and-mcp-tooling/model-context-protocol-overview.md)

## Overview

An open standard for connecting AI applications to external systems: data sources, tools, and workflows, described with the analogy "MCP is like a USB-C port for AI applications." Aims to let developers "build once and integrate everywhere" instead of writing custom integrations per data source per AI app.

## Value Proposition

For developers: less integration work per external system. For AI applications/agents: access to a growing ecosystem of pre-built connectors. For end users: assistants that can actually reach their data and take action, not just talk about it. Supported clients cited include Claude, ChatGPT, VS Code, Cursor, and MCPJam.

Concrete reference servers and SDKs are catalogued in [MCP Reference Servers](mcp-reference-servers.md); browser automation over MCP is implemented by [Playwright MCP](playwright-mcp.md).

## See Also

- [MCP Reference Servers](mcp-reference-servers.md)
- [Playwright MCP](playwright-mcp.md)
