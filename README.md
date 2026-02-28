# MemoNight (DevOps Project)

MemoNight is a Node.js (Express) web application using MySQL database.
This repository is part of a DevOps assignment: Docker, Docker Compose, and CI/CD with GitHub Actions.

## Tech Stack
- Node.js + Express
- EJS Templates
- MySQL (mysql:8.0)
- Docker + Docker Compose
- GitHub Actions (CI)

## Services & Ports
- App: http://localhost:3001 (container listens on 3000)
- MySQL: localhost:3307 (container 3306)

## Run with Docker Compose (Recommended)

### Build & Run
```bash
docker compose up -d --build
