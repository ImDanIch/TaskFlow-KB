---
type: concept
tags:
  - architecture
  - taskflow
status: active
---

# TaskFlow Architecture

TaskFlow — навчальний застосунок для керування завданнями, побудований за принципами REST API.

## Основні компоненти

- FastAPI — обробка HTTP-запитів.
- Pydantic — валідація даних.
- SQLAlchemy — робота з базою даних.
- SQLite — збереження завдань.
- pytest — автоматизоване тестування.

## Потік обробки запиту

HTTP-запит → FastAPI → Pydantic → SQLAlchemy → SQLite → HTTP-відповідь.

## Зв'язки

- [[REST API]]
- [[FastAPI]]
- [[SQLite]]