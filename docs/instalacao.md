# Instalação detalhada

Cálculo de Juros e Multa é um servidor MCP remoto. Aponte seu cliente pra `https://api.mcp.ai/p_calculo-juros-e-multa`. Snippets rápidos: [INSTALL.md](../INSTALL.md).

| Cliente | URL | Auth |
|---|---|---|
| Claude Desktop | `https://api.mcp.ai/p_calculo-juros-e-multa` | nenhuma (grátis) |
| Cursor | `https://api.mcp.ai/p_calculo-juros-e-multa` | nenhuma |
| VS Code (Copilot) | `https://api.mcp.ai/p_calculo-juros-e-multa` | nenhuma |

A config JSON é a mesma em todos: só a URL, sem headers.

## Desinstalar

Remova o bloco `mcpServers.calculojurosemulta` (ou `servers.calculojurosemulta` no VS Code) do config do cliente e reinicie.
