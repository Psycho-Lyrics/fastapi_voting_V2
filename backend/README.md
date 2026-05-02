## Асинхронное web-приложение для проведения внутренних голосований

### Технологический стек
1. Python + Poetry
2. FastAPI + Uvicorn
3. SQLalchemy + Alembic
3. Nginx
4. Redis
5. PostgreSQL + asyncpg
6. Docker

---
### Файловая структура приложения

```
.
├── src/
│   └── fastapi_voting_v2/
│       └── app/
│           └── v1/
│               ├── admin/
│               │   ├── __init__.py
│               │   ├── api/
│               │   │   ├── __init__.py
│               │   │   └── routes.py
│               │   ├── service.py
│               │   ├── exceptions.py
│               │   ├── dao.py
│               │   └── dto.py
│               ├── user/
│               │   ├── __init__.py
│               │   ├── api/
│               │   │   ├── __init__.py
│               │   │   └── routes.py
│               │   ├── service.py
│               │   ├── exceptions.py
│               │   ├── dao.py
│               │   └── dto.py
│               ├── voting/
│               │   ├── __init__.py
│               │   ├── api/
│               │   │   ├── __init__.py
│               │   │   └── routes.py
│               │   ├── service.py
│               │   ├── exceptions.py
│               │   ├── dao.py
│               │   └── dto.py
│               ├── vote/
│               │   ├── __init__.py
│               │   ├── api/
│               │   │   ├── __init__.py
│               │   │   └── routes.py
│               │   ├── service.py
│               │   ├── exceptions.py
│               │   ├── dao.py
│               │   └── dto.py
│               ├── scripts/
│               │   └── ./
│               ├── database/
│               │   ├── __init__.py
│               │   ├── migrations/
│               │   │   └── ./
│               │   ├── dummy/
│               │   │   ├── __init__.py
│               │   │   ├── seed.py
│               │   │   └── subjects/
│               │   │       └── __init__.py
│               │   ├── models/
│               │   │   └── __init__.py
│               │   └── db_core.py
│               ├── core/
│               │   ├── __init__.py
│               │   ├── DI/
│               │   │   ├── __init__.py
│               │   │   └── annotations.py
│               │   ├── utils/
│               │   │   └── __init__.py
│               │   ├── tokens.py/
│               │   │   ├── __init__.py
│               │   │   ├── service.py
│               │   │   └── exceptions.py
│               │   ├── smtp.py/
│               │   │   ├── __init__.py
│               │   │   ├── service.py
│               │   │   └── exceptions.py
│               │   ├── logging.py
│               │   ├── settings.py
│               │   ├── exceptions.py
│               │   ├── middlewares.py
│               │   ├── exception_handlers.py
│               │   └── main.py
│               └── entrypoint.py
├── tests/
│   └── __init__.py
├── .gitignore
├── pyproject.toml
└── README.md
```

---
### Быстрый старт
```

```