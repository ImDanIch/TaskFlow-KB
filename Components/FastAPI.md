---
type: component
tags:
  - backend
  - api
status: active
relationships:
  - type: uses
    target: Components/Pydantic.md
---

# FastAPI

FastAPI — Python-фреймворк для створення веб-API.

У TaskFlow використовується для реалізації HTTP-маршрутів і автоматичної документації Swagger.

## Реалізація в TaskFlow

- app/main.py — створення застосунку та підключення маршрутів.
- app/tasks.py — операції CRUD.
- app/schemas.py — Pydantic-схеми запитів і відповідей.

## Зв'язки

- [[REST API]]
- [[TaskFlow Architecture]]