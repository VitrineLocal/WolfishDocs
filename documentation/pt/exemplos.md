
---

### 3. `docs/exemplos.md` (Casos de Uso)
Este arquivo é o preferido da IA, pois ela o usará como base para sugerir códigos para você.
```markdown
# 💡 Exemplos Práticos

## 1. Agregando o Git e o Docker
Crie um fluxo que limpa containers e faz um push simultâneo:
```bash
maia run "docker system prune -f && git push origin main"