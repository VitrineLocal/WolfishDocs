# 🐺 Wolfish.Maia

> O Orquestrador Inteligente de Ferramentas CLI para Windows e Linux.

**Wolfish.Maia** é uma ferramenta de automação avançada que permite agregar, organizar e disparar múltiplas aplicações de linha de comando (CLI) através de uma interface unificada e inteligente.

---

## ✨ O que é a Wolfish.Maia?

Diferente de um simples script, a Maia funciona como um **hub central**. Ela permite que você registre binários, scripts e outras CLIs (como Docker, Git, ou ferramentas customizadas) e as execute com sintaxe simplificada, aliases e automação assistida por IA local (**Ollama**).

### 🚀 Principais Recursos
- **Agregação de Ferramentas:** Registre qualquer executável no sistema para ser chamado via `maia`.
- **Multiplataforma Nativa:** Funciona perfeitamente em CMD/PowerShell e Bash.
- **Inteligência Artificial Local:** Integração nativa com Ollama para entender comandos em linguagem natural.
- **Ecossistema MCP:** Documentação preparada para ser lida por agentes de IA.

---

## 🛠️ Começo Rápido

### Instalação
Para começar a utilizar a Wolfish.Maia agora mesmo, consulte o nosso [Guia de Instalação](pt/instalacao.md).

### Comando Básico
```bash
# Adicionando uma ferramenta ao agregador
maia add --alias "limpar" --cmd "docker system prune -f"

# Executando a ferramenta agregada
maia limpar
