# 04 — Multi-Server Clients

## Core Concepts

Production systems often need tools from **multiple MCP servers**. A good client can:
- Load server configurations from a config file
- Connect to several servers
- Aggregate available tools
- Route calls to the correct server

## Source Materials

- Folder: `MCP Client with Multiple Server Support`
  - Contains `config.json` and `langchain_mcp_client_wconfig.py`

## Interview Questions

1. How would you design a client that talks to multiple MCP servers?
2. How do you handle tool name collisions across servers?
3. What should a config file for MCP servers contain?

## Must-Do

Study (and ideally run) the multi-server client that uses a config file.
