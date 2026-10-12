# Interview Question Bank — MCP

## Foundational

1. What is the Model Context Protocol and what problem does it solve?
2. Explain the difference between Tools, Resources, and Prompts in MCP.
3. What are the main transports used by MCP?
4. Why is process isolation valuable for tool execution?

## Implementation

5. Walk through how a client discovers and calls a tool on an MCP server.
6. How would you implement a simple MCP server with one tool?
7. Difference between stdio and SSE transports?
8. How do you handle authentication and API keys in MCP tools?

## Integration & Production

9. How do LangChain MCP adapters work?
10. How would you use MCP tools inside a LangGraph agent?
11. How do you design a client that talks to multiple MCP servers?
12. What security considerations exist when exposing tools via MCP?
13. How would you add observability or logging to MCP tool calls?
14. Compare hardcoding tools vs exposing them via MCP.

**Practice tip:** Be able to sketch the architecture of a multi-server MCP setup.
