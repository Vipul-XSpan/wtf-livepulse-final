# WTF LivePulse — Real-Time Multi-Gym Intelligence Engine

## Quick Start

Prerequisites:
- Docker Desktop

Run:
docker compose up --build

Access:
Frontend: http://localhost:3000
Backend: http://localhost:3001

First boot seeds full dataset automatically.

## Features
- Real-time dashboard (WebSockets)
- Analytics (heatmap, churn, revenue)
- Anomaly detection
- Simulator engine

## Reset
docker compose down -v
docker compose up --build

## Run Tests
docker exec -it wtf-livepulse-backend node --test
