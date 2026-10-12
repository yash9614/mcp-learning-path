# 03 — SSE Transport

## Core Concepts

**Server-Sent Events (SSE)** is a common transport for MCP that works well over HTTP. The client opens a persistent connection and receives events from the server.

Useful when the server and client are not on the same machine or when you want a long-lived connection.

## Source Materials

- Folder: `MCP Server and Client using SSE` in [MCP_PROJECTS_oo3](https://github.com/yash9614/MCP_PROJECTS_oo3)
  - Contains both server and client implementations
  - Look at `client_sse.py` and the terminal_server examples

## Interview Questions

1. When would you choose SSE over stdio?
2. How does the client keep the connection alive with SSE?
3. What are the trade-offs of SSE vs Streamable HTTP?

## Must-Do

Run the SSE server and client from the original dump and understand the connection flow.
