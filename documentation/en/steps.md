### 4. How to Publish to GitHub Pages
1. In your GitHub repository, go to **Settings** > **Pages**.

2. Under **Build and deployment**, choose the `main` (or `master`) branch and the `/(root)` folder.

3. Click save. In minutes, your site will be live at `https://your-username.github.io`.

### 5. Why is this good for your MCP?

When you build the MCP server (the `index.js` we made before), you will configure the `DOCS_DIR` to point exactly to this `/docs` folder.

* **The Human** will see the site rendered by Docsify.

* **The AI** will read the raw `.md` files, which are clean and well-structured.

Do you want me to prepare the contents of the **`mcp-context.md`** file, which would be a dedicated file to "explain" to the AI ​​how it should use the other manuals to help you program?