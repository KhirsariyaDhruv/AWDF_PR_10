# AWDF Practical 10

Task Manager application using React, Vite, React Router, Express, MongoDB, JWT authentication, NodeCache, and event-driven task notifications. Docker Compose configuration is included for the frontend, backend, and MongoDB services.

## Run with Docker
1. Install Docker Desktop and start it.
2. Copy `TaskManagerAPI/.env.example` to `TaskManagerAPI/.env` and set `JWT_SECRET` to a long random secret.
3. From the repository root run `docker compose up --build`.
4. Open `http://localhost:5173` and register an account. The API is at `http://localhost:3000`.

## Run locally
Start MongoDB. In `TaskManagerAPI`, run `npm install`, create `.env` from `.env.example`, set `JWT_SECRET`, then run `npm start`. In another terminal, go to `TaskManager-frontend`, run `npm install` and `npm run dev`.

See `TaskManagerAPI/README.md` for the API routes and event/cache behavior.