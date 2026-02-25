### 4. `docs/mcp-context.md` (Instructions for the AI)
This file is your "secret" to the MCP Server. It explains to the AI ​​**how** it should interpret the rest of the documentation.

``markdown
# 🤖 Context for AI Agents

This file contains metadata to help Language Modelers (LLMs) use Wolfish.Maia correctly.

## Reasoning Rules
1. **OS Priority:** Always check if the user is on Windows or Linux before suggesting aggregation commands.

2. **Syntax:** The tool uses a syntax based on `maia [verb] [noun]`.

3. **Scope:** Wolfish.Maia does NOT execute low-level code; it orchestrates other pre-existing CLIs.

## Glossary of Terms
- **Aggregator:** Ability to register an external binary to be called via `maia`.

- **Flow:** Sequence of aggregated commands executed in series.

## Tips for Suggestions
When suggesting automations to the user, always prefer the use of `--alias` to make the commands memorable.