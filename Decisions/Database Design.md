---
type: decision
tags:
  - architecture
  - database
status: accepted
relationships:
  - type: depends_on
    target: Components/SQLite.md
  - type: depends_on
    target: Components/SQLAlchemy.md
---

# Database Design

## Контекст

TaskFlow потребує збереження завдань між перезапусками застосунку.

## Прийняте рішення

Використовувати SQLite як локальну базу даних та SQLAlchemy для взаємодії з нею.

## Обґрунтування

- SQLite не потребує окремого сервера.
- Спрощує встановлення та тестування.
- Достатня для навчального застосунку.
- SQLAlchemy дозволяє відокремити модель даних від HTTP API.

## Обмеження

- Рішення орієнтоване на локальне використання.
- Міграції схеми бази даних поки не реалізовані.
- Для масштабного багатокористувацького сервісу може знадобитися інша СУБД.

## Зв'язки

- [[SQLite]]
- [[SQLAlchemy]]
- [[TaskFlow Architecture]]