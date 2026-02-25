

### 3. `docs/examples.md` (Use Cases)
This file is preferred by the AI, as it will use it as a basis for suggesting code for you.

``markdown

# 💡 Practical Examples

## 1. Integrating Git and Docker
Create a flow that cleans containers and performs a simultaneous push:

```bash
maia run "docker system prune -f && git push origin main"