# Threatora Production Deployment Configurations

Deployment manifests, networking scripts, and orchestration configurations for Threatora.

## Supported Deployment Targets

1. **Render Cloud (PaaS)**
   - Configured via root `render.yaml` with free tier CPU PyTorch optimizations.
2. **Docker & Docker Compose**
   - Multi-container architecture (`docker-compose.yml`) containing the Threatora web server and PostgreSQL state store.
3. **Local Air-Gapped Network / Tactical Field Unit**
   - Run directly via `start_server.bat` or `python server/app.py` on offline LAN segments.

Refer to root `DEPLOYMENT.md` for full step-by-step setup guides.
