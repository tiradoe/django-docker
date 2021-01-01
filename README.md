# django-docker
Starter for creating dockerized Django apps with Django Rest Framework and Postgresql pre-configured for development.

### Setup

1. Rename `.env_examples` to .env and update as needed.
2. Run `docker-compose up` in the project's root directory
3. Run `migrate_db.sh` to apply migrations
4. Go to `localhost:8000/api` in your browser
