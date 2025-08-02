# ollama-remote
Information to remotely connect to ollama instance

```
systemctl stop ollama.service
OLLAMA_HOST=0.0.0.0 ollama serve
ollama run qwen2.5-coder:7b --keepalive=-1m
```
