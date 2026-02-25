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

📖 Navegue pela Documentação
Use o menu lateral ou os links abaixo para explorar as funcionalidades:
Instalação: Como configurar no Windows e Linux.
Guia de Comandos: Lista completa de verbos e argumentos da CLI.
Exemplos Práticos: Receitas prontas para automações comuns.
Contexto MCP: Detalhes técnicos para desenvolvedores e agentes de IA.

---

### Dicas para as outras versões (EN/ES):
1.  **Mantenha os links relativos:** No `README.md` em inglês (`docs/en/README.md`), certifique-se de apontar para `en/instalacao.md` etc.
2.  **Sincronia de Comandos:** No corpo do texto, mantenha os exemplos de código idênticos, mudando apenas a explicação, para que a IA não se confunda com sintaxes diferentes entre idiomas.

### Por que este README é bom para o seu Servidor MCP C#?
Quando a IA chamar a ferramenta `obter_diretrizes` ou `ler_manual("README.md")`, ela lerá a seção **"O que é a Wolfish.Maia?"** e entenderá imediatamente que a ferramenta é um "Orquestrador/Hub", o que evita que ela tente usá-la para tarefas que ela não faz (como edição de imagem ou compilação de código).

**Deseja que eu te ajude a criar o arquivo `index.html` final do Docsify para que esse README já apareça com um tema bonito e barra de busca assim que você subir para o GitHub?**




🤝 Contribua
A Wolfish.Maia é um projeto em constante evolução. Siga o projeto no GitHub para novidades e reportar bugs.
Documentação gerada automaticamente para humanos e IAs via Model Context Protocol.
