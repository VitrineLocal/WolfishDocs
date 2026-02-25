### 4. `docs/mcp-context.md` (Instrucciones para la IA)
Este archivo es su "secreto" para el servidor MCP. Explica a la IA **cómo** debe interpretar el resto de la documentación.

``markdown
# 🤖 Contexto para agentes de IA

Este archivo contiene metadatos para ayudar a los modeladores de lenguaje (LLM) a utilizar Wolfish.Maia correctamente.

## Reglas de razonamiento
1. **Prioridad del sistema operativo:** Siempre verifique si el usuario usa Windows o Linux antes de sugerir comandos de agregación.

2. **Sintaxis:** La herramienta utiliza una sintaxis basada en `maia [verbo] [sustantivo]`.

3. **Alcance:** Wolfish.Maia NO ejecuta código de bajo nivel; orquesta otras CLI preexistentes.

## Glosario de términos
- **Agregador:** Capacidad de registrar un binario externo para ser llamado mediante `maia`.

- **Flujo:** Secuencia de comandos agregados ejecutados en serie.

## Consejos para sugerencias
Al sugerir automatizaciones al usuario, siempre es preferible usar `--alias` para que los comandos sean fáciles de recordar.