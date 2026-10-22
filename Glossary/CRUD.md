---
type: glossary
tags:
  - terminology
  - api
status: active
---

# CRUD

CRUD — скорочення від Create, Read, Update, Delete.

Це чотири основні операції керування даними.

## CRUD у TaskFlow

- Create — POST /tasks.
- Read — GET /tasks та GET /tasks/{task_id}.
- Update — PATCH /tasks/{task_id}.
- Delete — DELETE /tasks/{task_id}.

## Зв'язки

- [[REST API]]
- [[FastAPI]]
- [[TaskFlow Architecture]]