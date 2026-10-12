# Must-Do Projects — MCP

Complete these in roughly this order.

## 1. Basic Server + Client
**Goal:** Understand the protocol.  
**Source:** Any simple pair in the original dump (or build your own with the official SDK).  
**Deliverable:** Server with 2 tools + client that lists and calls them.

## 2. SSE Server & Client
**Goal:** Real transport.  
**Source:** `MCP Server and Client using SSE`  
**Deliverable:** Working SSE connection.

## 3. Multi-Server Client
**Goal:** Production-style client.  
**Source:** `MCP Client with Multiple Server Support`  
**Deliverable:** Client that loads servers from config and aggregates tools.

## 4. LangChain MCP Adapter
**Goal:** Use MCP inside agents.  
**Source:** `Langchain MCP Client using LangChain MCP Adapters`  
**Deliverable:** LangGraph or LangChain agent that calls MCP tools.

## 5. Domain Tools (Clinisight style)
**Goal:** Build useful tools.  
**Source:** `Clinisight`  
**Deliverable:** At least one new domain-specific MCP tool.

## 6. Full Application (AgentWriter style)
**Goal:** End-to-end product.  
**Source:** `AgentWriter-AI`  
**Deliverable:** Agent that uses tools and has a simple UI or clear notebook demo.

---

**Interview tip:** Be ready to explain tool design, error handling, security, and how you would scale or secure the system.
