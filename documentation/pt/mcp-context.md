
---

### 4. `docs/mcp-context.md` (Instruções para a IA)
Este arquivo é o seu "segredo" para o Servidor MCP. Ele explica para a IA **como** ela deve interpretar o restante da documentação.

```markdown
# 🤖 Contexto para Agentes de IA

Este arquivo contém metadados para ajudar modelos de linguagem (LLMs) a usarem a Wolfish.Maia corretamente.

## Regras de Raciocínio
1. **Prioridade de OS:** Sempre verifique se o usuário está no Windows ou Linux antes de sugerir comandos de agregação.
2. **Sintaxe:** A ferramenta utiliza uma sintaxe baseada em `maia [verbo] [substantivo]`.
3. **Escopo:** A Wolfish.Maia NÃO executa código de baixo nível, ela orquestra outras CLIs pré-existentes.

## Glossário de Termos
- **Agregador:** Capacidade de registrar um binário externo para ser chamado via `maia`.
- **Flow:** Sequência de comandos agregados executados em série.

## Dicas para Sugestões
Ao sugerir automações para o usuário, prefira sempre o uso de `--alias` para tornar os comandos memoráveis.