### 4. Como publicar no GitHub Pages
1. No seu repositório no GitHub, vá em **Settings** > **Pages**.
2. Em **Build and deployment**, escolha a branch `main` (ou `master`) e a pasta `/(root)`.
3. Clique em salvar. Em minutos, seu site estará no ar em `https://seu-usuario.github.io`.

### 5. Por que isso é bom para o seu MCP?
Quando você for construir o servidor MCP (o `index.js` que fizemos antes), você vai configurar o `DOCS_DIR` para apontar exatamente para essa pasta `/docs`.

*   **O Humano** verá o site renderizado pelo Docsify.
*   **A IA** lerá os arquivos `.md` brutos, que estão limpos e bem estruturados.

Você quer que eu prepare o conteúdo do **`mcp-context.md`**, que seria um arquivo exclusivo para "explicar" para a IA como ela deve usar os outros manuais para te ajudar a programar?
