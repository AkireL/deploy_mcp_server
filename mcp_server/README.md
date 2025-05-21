```bash
uv init

# Crea un entorno virtual y actívalo:
uv venv

source .venv/bin/activate

# Instala las dependencias:
uv add mcp arxiv

# Lanza el inspector:
npx @modelcontextprotocol/inspector uv run research_server.py
```