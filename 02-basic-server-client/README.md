# 02 — Basic MCP Server + Client

## Core Concepts

A minimal MCP system has:
1. A server that registers one or more tools
2. A client that connects, lists tools, and calls them

Most simple examples use **stdio** transport (process-to-process).

## Source Materials (original dump)

Look for basic server/client examples inside:
- `MCP Server and Client using SSE` (even though SSE is advanced, the basic pattern is similar)
- Any simple tool registration patterns in Clinisight or other folders

## Interview Questions

1. Walk through the lifecycle of an MCP tool call.
2. What is the difference between stdio and SSE transports?
3. How do you register a new tool on an MCP server?
4. What information does the client receive when it lists tools?

## Must-Do

Build (or deeply study) a server with 2 simple tools and a client that calls both.
