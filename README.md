# InnerOS Alexa → AMD demo

Pedido por voz (Ambient Guardian / Inner Oz): **a 1 page AMD hackathon status dashboard**

- Draft: `draft-fdd43a5fc3a7`
- Ops: `ops_6422b787b51a`
- Inferencia local: Qwen3-Coder en AMD (ROCm/vLLM)
- Orquestación: InnerOS agentes

## Dashboard (1 página)

Archivos:

- `index.html` — vista única (workstreams, hitos, infra)
- `status.json` — datos editables; la página recarga cada 30s

Servir en local:

```bash
python3 -m http.server 8080
```

Abrir [http://localhost:8080/](http://localhost:8080/).
