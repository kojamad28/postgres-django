# Postgres Django

This repository provides a Django project template connected with PostgreSQL database.

## How to use

```bash
docker compose build
docker compose run django python manage.py makemigrations accounts
docker compose run django python manage.py migrate accounts
docker compose run django python manage.py migrate
docker compose run django python manage.py createsuperuser
docker compose up -d --remove-orphans
```

```.gitignore
# Django stuff:
*.log
local_settings.py
db.sqlite3
db.sqlite3-journal
media/
#*/migrations/*
#!*/migrations/__init__.py
```
