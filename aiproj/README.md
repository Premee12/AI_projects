## MCP Memory Chat (Intro Project)

This project is a minimal interactive chat application that integrates a Groq-hosted large language model with MCP-based tools. It connects an LLM (`ChatGroq`) to external capabilities defined in an mcp_browser configuration file (playwright, airbnb, duckduckgo-search), enabling tool-augmented reasoning directly from the terminal.

The agent runs with built-in conversation memory, maintaining context across turns and allowing the user to clear history when needed. The application is fully asynchronous, using `asyncio` to manage model calls and tool interactions efficiently.

This repository serves as a lightweight starting point for experimenting with MCP, agent-tool integration, and memory-enabled conversational workflows.