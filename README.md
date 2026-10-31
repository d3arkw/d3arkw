# Hi, I'm Denis — Python Backend (FastAPI / PostgreSQL)

1+ year in production. I build production-style REST APIs: PostgreSQL + SQLAlchemy, tests, Docker, CI.
Main project — SaaS Bildock, live in prod.

## 🚀 Bildock — live SaaS for backend developers

**Live: [bildock.ru](https://bildock.ru) | Showcase: [bildock-showcase](https://github.com/d3arkw/bildock-showcase)**

What it is: connect a local project via CLI, see file-tree UI + live service state (container load, CPU/RAM, processes via WebSocket).

> Core repo is private (full workspace). Public showcase has architecture, docs and key backend slices.

Backend (mine):
- Modular FastAPI (asyncio, async/await): auth, gateway, project — 48 endpoints, 8 tables PostgreSQL, 10 migrations Alembic
- Auth: JWT with refresh rotation in Redis, login + OAuth2 (GitHub, Yandex), rate limiting (slowapi + Redis)
- Payments: YooKassa subscriptions + webhook with idempotency (transactions, unique constraints, event log)
- Quality: 171 pytest (unit + integration, ~85%+ on auth/payments/webhooks), GitHub Actions 60-75s
- Ops: Docker Compose, HTTPS, gateway, logging. Local load check: p95 <10ms

## 🛠 Stack

Python 3.13+ · FastAPI · SQLAlchemy 2.0 · Alembic · Pydantic v2 · PostgreSQL · Redis · Celery · RabbitMQ · JWT / OAuth2 · REST · pytest · Docker / Compose · Git · GitHub Actions · HTTPX · Django / DRF · Linux

## 📌 Other backends

- **[Tender Status Tracker](https://github.com/d3arkw/tender-status-tracker)** — FastAPI + PG + Redis, lifecycle draft/active/won/lost with history. Redis cache RPS 290→770, index on 100k rows, 11 tests, CI.
- **[Freelance CRM API](https://github.com/d3arkw/freelance-crm-api)** — Django 6.1 + DRF: clients/orders/payments, SimpleJWT + own-data permissions, django-filter, ORM analytics, Swagger, pytest-django, PG + Redis.
- **[FitnessTracker](https://github.com/d3arkw/FitnessTracker)** — FastAPI REST + JWT, SQL analytics, tests, CI.

## 📫 Contacts

- Telegram: [@d3arkw](https://t.me/d3arkw)
- Mail: [d3arkw@icloud.com](mailto:d3arkw@icloud.com)
- HH resume: Python Backend (FastAPI / PostgreSQL)

Open to Junior+ / Middle, remote. Ready for test task.
