
## Project Structure
```
backend
│   .gitignore
│   docker-compose.yml
│   Makefile
│   README.md
│   requirements.txt
│   ruff.toml
│
├───app
│   │   errors.py
│   │   main.py
│   │   middlewares.py
│   │   models.py
│   │   openapi.py
│   │   router.py
│   │   settings.py
│   │   utils.py
│   │   __init__.py
│   │
│   ├───auth
│   │       depends.py
│   │       models.py
│   │       router.py
│   │       service.py
│   │       __init__.py
│   │
│   ├───comment
│   │       models.py
│   │       orm.py
│   │       router.py
│   │       service.py
│   │       __init__.py
│   │
│   ├───database
│   │   │   __init__.py
│   │   │
│   │   ├───postgres
│   │   │       core.py
│   │   │       orm.py
│   │   │       __init__.py
│   │   │
│   │   └───redis
│   │           core.py
│   │           __init__.py
│   │
│   ├───exc
│   │       core.py
│   │       handlers.py
│   │       utils.py
│   │       __init__.py
│   │
│   ├───follow
│   │       errors.py
│   │       models.py
│   │       orm.py
│   │       router.py
│   │       service.py
│   │       __init__.py
│   │
│   ├───message
│   │       errors.py
│   │       models.py
│   │       orm.py
│   │       router.py
│   │       service.py
│   │       __init__.py
│   │
│   ├───notification
│   │       models.py
│   │       orm.py
│   │       router.py
│   │       service.py
│   │       __init__.py
│   │
│   ├───reaction
│   │       models.py
│   │       orm.py
│   │       router.py
│   │       service.py
│   │       __init__.py
│   │
│   ├───tweet
│   │       errors.py
│   │       models.py
│   │       orm.py
│   │       router.py
│   │       service.py
│   │       __init__.py
│   │
│   └───user
│           errors.py
│           models.py
│           orm.py
│           router.py
│           service.py
│           __init__.py
│
└───tests
        __init__.py
```