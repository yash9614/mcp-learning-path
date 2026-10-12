# MCP Learning Path

**Structured path for mastering the Model Context Protocol (MCP) — servers, clients, transports, LangChain integration, and real projects.**

This repository is a clean, concept-driven learning path built around your existing MCP project materials. It focuses heavily on **concepts**, **interview questions**, and **must-do projects**.

Original raw projects are left untouched: [MCP_PROJECTS_oo3](https://github.com/yash9614/MCP_PROJECTS_oo3)

---

## Related Learning Repos (Your Ecosystem)

| Repo | Focus | Link |
|------|-------|------|
| Generative AI Learning Path | Broad GenAI + LangChain foundations | [generative-ai-learning-path](https://github.com/yash9614/generative-ai-learning-path) |
| Ultimate RAG Bootcamp | Deep RAG techniques + agentic RAG | [Ultimate-RAG-Bootcamp](https://github.com/yash9614/Ultimate-RAG-Bootcamp-LangChain-LangGraph-LangSmith) |
| Agentic AI Learning Path | LangGraph, ReAct, Agentic RAG, HITL, workflows | [agentic-ai-learning-path](https://github.com/yash9614/agentic-ai-learning-path) |
| This repo | MCP servers, clients, SSE, multi-server, adapters | You are here |

**Recommended order:** GenAI → RAG → Agentic systems → MCP (this repo).

---

## Learning Path Overview

| Stage | Folder | Focus | Priority |
|-------|--------|-------|----------|
| 1 | `01-mcp-foundations` | What is MCP, why it exists, core concepts | High |
| 2 | `02-basic-server-client` | Simple MCP server + client | Critical |
| 3 | `03-sse-transport` | Server-Sent Events transport | High |
| 4 | `04-multi-server-clients` | Multiple servers, config-driven clients | High |
| 5 | `05-langchain-mcp-adapters` | LangChain / LangGraph + MCP | Critical |
| 6 | `06-practical-projects` | AgentWriter-AI, Clinisight, and more | Critical |
| 7 | `07-projects-and-interview` | Must-do projects + interview Q bank | Critical |

Work the folders in order. Each has a detailed README with concepts, what to study, interview questions, and pointers to the original project folders.

---

## Must-Do Projects (Priority Order)

1. **Basic MCP Server + Client** — Understand the protocol flow.
2. **SSE Server and Client** — Real-time transport.
3. **Multi-Server Client** — Config-driven connection to multiple servers.
4. **LangChain MCP Adapter Client** — Use MCP tools inside LangChain / LangGraph agents.
5. **Clinisight-style domain tools** — Build domain-specific MCP tools (medical, research, etc.).
6. **AgentWriter-AI style full app** — End-to-end agent that uses tools (optionally via MCP).

Details are in `07-projects-and-interview/MUST-DO-PROJECTS.md`.

---

## Key Concepts You Must Master

- What MCP is and the problem it solves
- Tools, Resources, Prompts (MCP primitives)
- Server vs Client roles
- Transports: stdio, SSE, Streamable HTTP
- Tool discovery and calling
- LangChain MCP adapters
- Multi-server orchestration
- Security and process isolation

---

## Setup (uv)

```bash
# Install uv if needed: https://docs.astral.sh/uv/getting-started/installation/

uv sync
cp .env.example .env   # fill in keys if required

uv run python -m your_script
# or for notebooks
uv run jupyter lab
```

Most projects in the original dump already use `uv` / `pyproject.toml`. Prefer that pattern.

---

## How to Use This Repo

1. Read each module README (concepts + interview questions).
2. Explore the corresponding folders in the original [MCP_PROJECTS_oo3](https://github.com/yash9614/MCP_PROJECTS_oo3) dump.
3. Complete the Must-Do Projects.
4. Practice the interview questions.
5. Connect MCP tools into your Agentic AI / LangGraph work.

Start with `01-mcp-foundations/README.md`.

Happy building with MCP!
