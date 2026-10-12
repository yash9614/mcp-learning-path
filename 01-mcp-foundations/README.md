# 01 — MCP Foundations

## Core Concepts

**Model Context Protocol (MCP)** is an open standard that lets AI applications (clients) securely connect to external tools, data sources, and services (servers).

It solves the problem of every AI app having to implement its own custom tool integrations.

### Main Primitives
- **Tools** — Functions the model can call
- **Resources** — Data the model can read
- **Prompts** — Reusable prompt templates

### Roles
- **Server** — Exposes tools/resources/prompts
- **Client** — Discovers and calls them (usually inside an agent or IDE)

## What to Study

Official docs: https://modelcontextprotocol.io

In your dump, look at the high-level structure of any server/client pair.

## Interview Questions

1. What problem does MCP solve?
2. Difference between MCP Tools, Resources, and Prompts?
3. Why is process isolation useful for tools?
4. How does an agent discover available tools from an MCP server?
5. Compare MCP to simply hardcoding tools inside your agent code.

## Must-Learn Takeaway

MCP turns tools into a standardized, reusable interface that any MCP-compatible client can consume.
