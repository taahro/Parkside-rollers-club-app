# Parkside-rollers-club-app

Modular Club Manager app starter for Parkside Rollers FC.

## Project structure

- `frontend/` - static frontend scaffold (HTML/CSS).
- `Dockerfile` - container image for serving the frontend with Nginx.
- `docker-compose.yml` - local orchestration for running the frontend service.

## Run locally with Docker

```bash
docker compose up --build
```

Open `http://localhost:8080`.
