# ALISON NEXUS — God Panel

A from-scratch visual layer for the existing FastAPI network/subscription backend.

## UI modules
- Command Center
- Network Lab / Inbounds
- Client Forge
- Access Passport subscriptions
- Plan Studio
- Signal Monitor
- Event Stream
- Security Core
- System Core

## Run
```bash
pip install -r requirements.txt
uvicorn main:app --host 0.0.0.0 --port ${PORT:-8000}
```

Docker uses the same Railway/Render-friendly command and `${PORT:-8000}`.

The dashboard preserves the existing backend API routes and state logic while replacing the visible admin UI and customer subscription portal.
