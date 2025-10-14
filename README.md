# Hospital Management System - Fullstack (Frontend + Backend)

This workspace contains two projects:

- `hospital-backend`: Spring Boot API (port 8081)
- `hospital-frontend`: React (Vite) frontend (port 5173)

Quick commands

Run locally with Docker Compose (builds images and starts services):

```powershell
cd C:\Users\CHARAN\OneDrive\Desktop\in-sem-lab
docker compose up --build
```

This will start:
- MySQL on 3306
- Backend on 8081
- Frontend served by nginx on 5173 (mapped to container port 80)

GitHub Actions

- Workflows are defined in `.github/workflows/` and will build and push images to GitHub Container Registry (`ghcr.io/<owner>/...`) on pushes affecting each project.
