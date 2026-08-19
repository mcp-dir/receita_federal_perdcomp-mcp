# Instalação detalhada

Receita Federal PER: DCOMP é um servidor MCP remoto. Aponte seu cliente pra `https://api.mcp.ai/p_receita_federal_perdcomp`. Snippets rápidos: [INSTALL.md](../INSTALL.md).

| Cliente | URL | Auth |
|---|---|---|
| Claude Desktop | `https://api.mcp.ai/p_receita_federal_perdcomp` | OAuth 2.1 ou agent-auth |
| Cursor | `https://api.mcp.ai/p_receita_federal_perdcomp` | OAuth 2.1 ou agent-auth |
| VS Code (Copilot) | `https://api.mcp.ai/p_receita_federal_perdcomp` | OAuth 2.1 ou agent-auth |

A config JSON é a mesma em todos: só a URL, sem headers.

## Desinstalar

Remova o bloco `mcpServers.receita_federal_perdcomp` (ou `servers.receita_federal_perdcomp` no VS Code) do config do cliente e reinicie.
