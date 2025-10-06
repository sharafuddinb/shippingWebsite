# Southeast Motors Portal (minimal scaffold)

This repository contains a minimal scaffold: a tiny Node backend that serves a static frontend and a health API.

Quick start (macOS / zsh):

1. Start the backend:

```bash
cd backend
node server.js
```

2. Open the frontend in your browser:

http://localhost:3000/

Health check:

```bash
curl http://localhost:3000/api/health
```

Files added:
- `backend/server.js` — minimal HTTP server with `/api/health` and serves `frontend/index.html`.
- `backend/package.json` — start script.
- `frontend/index.html` — tiny demo UI that calls the health API.

If you prefer a different stack or want npm scripts, let me know and I can expand this scaffold.
