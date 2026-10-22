---
type: component
tags:
  - backend
  - validation
status: active
---

# Pydantic

Pydantic — бібліотека Python для опису структур даних та їх валідації.

## Використання в TaskFlow

У TaskFlow Pydantic перевіряє дані HTTP-запитів і формує структуру відповідей API.

Основні схеми визначені у файлі app/schemas.py:

- TaskCreate — створення завдання.
- TaskUpdate — часткове оновлення завдання.
- TaskResponse — відповідь API.

## Валідація

- Перевірка обов'язкових полів.
- Контроль допустимих статусів і пріоритетів.
- Відхилення некоректних значень.
- Формування помилки HTTP 422.

## Зв'язки

- [[FastAPI]]
- [[REST API]]
- [[TaskFlow Architecture]]