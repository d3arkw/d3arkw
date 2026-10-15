# Hi, I'm Denis 👋

Python Backend Developer (FastAPI) · 1+ year of commercial experience · Remote

I build production-style REST APIs and backend services: async Python, PostgreSQL + SQLAlchemy, tests, Docker, CI. My main project — a live SaaS called Bildock.

## 🚀 Bildock — live SaaS, my main project

**[bildock.ru](https://bildock.ru)** — web workspace for backend developers: connect a local project via CLI, browse it in a file-tree UI, watch service state in real time (container load, CPU/RAM, processes) over WebSocket.

- Microservice backend on FastAPI (asyncio): auth, gateway, project services — 48 endpoints
- PostgreSQL (8 tables) + Alembic migrations, async SQLAlchemy 2.0
- JWT auth with refresh-token rotation in Redis, email login, OAuth2 (GitHub, Yandex)
- Rate limiting (slowapi + Redis), paid subscriptions via YooKassa (webhooks, payment idempotency)
- 171 pytest tests (81–93% coverage per service), GitHub Actions CI, Docker Compose deploy in Yandex Cloud with HTTPS

> Code lives in a private repo — I'll happily give access on request. The product itself is live: **[bildock.ru](https://bildock.ru)**.

## Stack

Python 3.13+ · FastAPI · asyncio · SQLAlchemy 2.0 (async) · Alembic · Pydantic v2 · PostgreSQL · asyncpg · Redis · Celery · RabbitMQ · JWT / OAuth2 · REST · WebSocket · Pytest · Docker · Docker Compose · Git · GitHub Actions · Yandex Cloud · uv

Learning: event-driven architecture (Kafka), deeper CI/CD, Linux.

## Other projects

📋 **[Tender Status Tracker](https://github.com/d3arkw/tender-status-tracker)** — tender status lifecycle (draft → active → won/lost) with full change history. Redis caching raised RPS 290 → 770, an index on tender_id cut a 100k-row query from 3.0 ms to 0.014 ms. 11 tests, 88% coverage, CI.

🏋️ **[Fitness Tracker API](https://github.com/d3arkw/FitnessTracker)** — workouts REST API: JWT + bcrypt, 14 endpoints, progress stats via SQL (GROUP BY + JOIN), 18 tests on a live DB, CI.

🛒 **[Microservice Market Study](https://github.com/d3arkw/market-microservise-study)** — three services (catalog, order, payment), database per service, HTTP + message broker.

More: [Password Manager](https://github.com/d3arkw/password_manager) · [Habit Tracker](https://github.com/d3arkw/habits-tracker) · [Finance CLI](https://github.com/d3arkw/finance-tracker-cli) · [Simple Terminal](https://github.com/d3arkw/simple-terminal)

## Contact

- Telegram: [@d3arkw](https://t.me/d3arkw) — fastest way to reach me
- Email: [d3arkw@icloud.com](mailto:d3arkw@icloud.com)

Open to Junior+ / Middle Python Backend positions (remote).
