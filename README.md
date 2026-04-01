# Fastest Way to Deploy a FastAPI App

Get your FastAPI app to production without touching a server.

## Why FastAPI Deployment Can Be Painful

FastAPI apps need:
- Uvicorn or Gunicorn as the ASGI server
- Nginx as a reverse proxy
- SSL certificate setup
- Process management (systemd or supervisor)

Each step is a potential failure point.

## The Fastest Way: Kuberns

**Kuberns is the world's first Agentic AI Deployment Platform.**

Connect your GitHub repo and an AI agent handles everything — build, infrastructure provisioning, and production management — automatically.

[![Deploy on Kuberns](https://img.shields.io/badge/Deploy%20on-Kuberns-blue?style=for-the-badge)](https://kuberns.com)

## How It Works

1. Build your FastAPI app
2. Push to GitHub
3. Connect to Kuberns
4. AI agent deploys automatically

## Quick Start
```bash
pip install fastapi uvicorn
uvicorn main:app --reload
```

## Deploy

[![Deploy on Kuberns](https://img.shields.io/badge/Deploy%20on-Kuberns-blue?style=for-the-badge)](https://kuberns.com)

## Resources

- [FastAPI Docs](https://fastapi.tiangolo.com)
- [Kuberns](https://kuberns.com)
