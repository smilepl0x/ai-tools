# Docker Compose files for
- Ollama
- Open-Webui
- Opencode

### How to use

1. Ensure Docker is installed on your machine
2. Change filenames from .env.dist to .env and update vars as you see fit
3. Navigate to projects and run `docker compose up -d'

The Open-webui and Opencode files both assume a network called `ollama` which is set up automatically with the Ollama container.

Combine the definitions into one file if you wish.
