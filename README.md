# Привет, я Денис — Python Backend (FastAPI / PostgreSQL)

1+ год в проде. Строю production-style REST API: PostgreSQL + SQLAlchemy, тесты, Docker, CI.
Главный проект — SaaS Bildock, живёт в проде.

## 🚀 Bildock — живой SaaS для backend-разработчиков

**Прод: [bildock.ru](https://bildock.ru) | Витрина: [bildock-showcase](https://github.com/d3arkw/bildock-showcase)**

Что это: подключаешь локальный проект через CLI, видишь файловое дерево + живое состояние сервисов (нагрузка контейнеров, CPU/RAM, процессы по WebSocket).

> Ядро — в приватном репо (полный воркспейс). В публичной витрине — архитектура, доки и ключевые куски бэкенда.

Бэкенд (мой):
- Модульный FastAPI (asyncio, async/await): auth, gateway, project — 48 эндпоинтов, 8 таблиц PostgreSQL, 10 миграций Alembic
- Auth: JWT с ротацией refresh в Redis, вход + OAuth2 (GitHub, Yandex), rate limiting (slowapi + Redis)
- Платежи: подписки YooKassa + webhook с идемпотентностью (транзакции, unique-ограничения, журнал событий)
- Качество: 171 pytest (unit + integration, ~85%+ на auth/платежи/webhook), GitHub Actions 60-75 сек
- Опс: Docker Compose, HTTPS, gateway, логи. Локальный замер: p95 <10мс

## 🛠 Стек

Python 3.13+ · FastAPI · SQLAlchemy 2.0 · Alembic · Pydantic v2 · PostgreSQL · Redis · Celery · RabbitMQ · JWT / OAuth2 · REST · pytest · Docker / Compose · Git · GitHub Actions · HTTPX · Django / DRF · Linux

## 📌 Другие бэкенды

- **[Tender Status Tracker](https://github.com/d3arkw/tender-status-tracker)** — FastAPI + PG + Redis, жизненный цикл draft/active/won/lost с историей. Кэш Redis RPS 290→770, индекс на 100к записей, 11 тестов, CI.
- **[Freelance CRM API](https://github.com/d3arkw/freelance-crm-api)** — Django 6.1 + DRF: клиенты/заказы/платежи, SimpleJWT + права на свои данные, django-filter, аналитика на ORM, Swagger, pytest-django, PG + Redis.
- **[FitnessTracker](https://github.com/d3arkw/FitnessTracker)** — FastAPI REST + JWT, SQL-аналитика, тесты, CI.

## 📫 Контакты

- Telegram: [@d3arkw](https://t.me/d3arkw)
- Почта: [d3arkw@icloud.com](mailto:d3arkw@icloud.com)
- Резюме на hh: Python Backend (FastAPI / PostgreSQL)

Открыт к Junior+ / Middle, удалённо. Готов к тестовому.
