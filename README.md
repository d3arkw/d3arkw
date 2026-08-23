# Hi, I'm Denis 👋

Python Backend Developer. College student, Information Systems and Programming.

I build REST APIs and backend services with Python and FastAPI. I care about async Python, PostgreSQL and SQLAlchemy, and code that has tests, runs in Docker, and passes CI — not just works on my machine.

Started with small CLI tools, moved to production-style REST APIs, and now I'm building a microservices platform: independent services, database per service, a shared internal library, JWT auth with refresh tokens in Redis. The next step is event-driven architecture — RabbitMQ and Kafka.

Open to internship and Junior Python Backend positions.

## Stack

Python 3.13+ · FastAPI · SQLAlchemy 2.0 (async) · Alembic · Pydantic v2 · PostgreSQL · asyncpg · Redis · JWT · REST · Pytest · Docker · Docker Compose · Git · GitHub Actions · uv

Learning: microservices architecture, event-driven design (RabbitMQ, Kafka), deeper CI/CD, Linux.

## Projects

🚀 **[Bildock](https://github.com/d3arkw/bildock)** — web workspace for backend developers: Docker monitoring, logs, errors, Swagger, architecture map, AI analysis. SaaS-ready.
Microservices monorepo (uv workspace): 6 services, shared library (config, database, security, exceptions), database per service, Alembic migrations, JWT auth with refresh tokens in Redis, CI (ruff + pytest) on every pull request. Auth service is fully implemented; gateway and the rest are in progress.

🏋️ **[Fitness Tracker API](https://github.com/d3arkw/FitnessTracker)** — production-style REST API for a fitness app.
JWT authentication, password hashing (bcrypt), CRUD for exercises and workouts, progress statistics, async SQLAlchemy 2.0 + asyncpg, Alembic, Pytest, Docker Compose, GitHub Actions CI.

📋 **[Tender Status Tracker](https://github.com/d3arkw/tender-status-tracker)** — tender status tracking service.
Status lifecycle (draft → active → won/lost) with validation and full change history, Redis caching, async SQLAlchemy, Docker Compose, CI.

🛒 **[Microservice Market Study](https://github.com/d3arkw/market-microservise-study)** — educational microservices project.
Three services (catalog, order, payment), database per service (3 PostgreSQL), HTTP communication between services, message broker integration planned.

More: [Password Manager](https://github.com/d3arkw/password_manager) · [Habit Tracker](https://github.com/d3arkw/habits-tracker) · [Finance CLI](https://github.com/d3arkw/finance-tracker-cli) · [Simple Terminal](https://github.com/d3arkw/simple-terminal)

## Currently working on

- Bildock: gateway, GitHub OAuth, project and analytics services
- RabbitMQ practice: FastAPI producer → exchange → queue, finishing the consumer side
- Next up: Kafka, event-driven patterns, CI/CD, Linux

## Contact

- Telegram: [@d3arkw](https://t.me/d3arkw)
- Email: [d3arkw@icloud.com](mailto:d3arkw@icloud.com)
