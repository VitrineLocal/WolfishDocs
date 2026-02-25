### 3. `docs/examples.md` (Casos de uso)
La IA prefiere este archivo, ya que lo usará como base para sugerirte código.

``markdown
# 💡 Ejemplos prácticos

## 1. Integración de Git y Docker
Crea un flujo que limpie los contenedores y realice un push simultáneo:

```bash
maia run "docker system prune -f && git push origin main"