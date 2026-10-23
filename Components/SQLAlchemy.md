---
type: component
tags:
  - database
  - backend
status: active
relationships:
  - type: uses
    target: Components/SQLite.md
---

# SQLAlchemy

SQLAlchemy — бібліотека Python для роботи з реляційними базами даних.

У TaskFlow використовується ORM-підхід: записи бази даних представлені об'єктами Python.

## Реалізація в TaskFlow

- app/database.py — підключення до SQLite та керування сесіями.
- app/models.py — ORM-модель Task.
- app/tasks.py — операції з даними через сесії SQLAlchemy.

## Основні можливості

- Створення та читання записів.
- Оновлення й видалення завдань.
- Керування транзакціями.
- Перевірка обмежень на рівні бази даних.

## Зв'язки

- [[SQLite]]
- [[Database Design]]
- [[TaskFlow Architecture]]